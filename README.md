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
      
      


