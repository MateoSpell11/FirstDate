path: /sfdc/sync/changeCredentials
body: {
    "userEmail": "logan1@corporatealliance.net.sbx1"
      }
route: 
    name: 'sfdc',
    route: '/sfdc/sync',
    method: 'all',
    auth: true,
    mw: [
      {
        path: '@trackland/sfdx-integration/connect/changeCredentials',
        route: '/changeCredentials',
        method: 'post',
        order: 100,
        description: 'Change SF credentials into AWS and env variables.',
      },

      
