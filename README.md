# VisualStudioIssues
Issues and how I resolved them


* using angular 4 in visual studio
  Install TypeScript for VisualStudio   for visual studio 2015 -- https://www.microsoft.com/en-us/download/details.aspx?id=48593
copy  angular code into project 
 Show all files and include eveything besides bin , obj  and  node modules  folders
 npm install on project 
 
 In _layout.cshtml

<!-- Angular2 Code -->
    <base href="/">
    <link rel="stylesheet" href="styles.css">
    <!-- Polyfill(s) for older browsers -->
    <script src="https://cdn.polyfill.io/v2/polyfill.min.js?features=Intl.~locale.en"></script>
    <script src="node_modules/core-js/client/shim.min.js"></script>
    <script src="node_modules/zone.js/dist/zone.js"></script>
    <script src="node_modules/reflect-metadata/Reflect.js"></script>
    <script src="node_modules/systemjs/dist/system.src.js"></script>
    <script src="systemjs.config.js"></script>
    <script>
      System.import('app').catch(function(err){ console.error(err); });
    </script>
    <!-- Angular2 Code -->
    
 In Index.cshtml
 
 @{
    ViewBag.Title = "Home Page";
}

        <my-app>Loading...</my-app>
 
