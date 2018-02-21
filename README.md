# VisualStudioIssues
Issues and how I resolved them


* Using angular 4 in visual studio 2015 asp.net web app
* Install TypeScript for VisualStudio   for visual studio 2015 -- https://www.microsoft.com/en-us/download/details.aspx?id=48593
* Download angular quickstart https://github.com/angular/quickstart
* follow steps on https://angular.io/guide/visual-studio-2015
* Change the systemjs.config.js to the following 
 
    paths: {
     
      'npm:': '/node_modules/'
    },

    map: {
   
      'app': '/src/app',
      
      }
      
      
    *  Temporary solution if you get error in withrjxs and typescript compatibility issues
           add the following code      In tsConfig.json in compiler Options:
      
            "noStrictGenericChecks": true
            
            
            
   ## Adding angularCli Functionality to Generate Componenets
    * ng new in a temporary folder 
    * copy AngularCli.Json, polyfill.ts , tsConfig.app.Json and include in project
    
    ----Note: I am not yet able to use ng serve properly (i.e many things dont load properly)
   
   
      
      ### issues with starting Vs 2015 
      https://stackoverflow.com/questions/10963241/visual-studio-cannot-open-new-project


