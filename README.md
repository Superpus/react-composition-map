# react-composition-map
Creates a composition map over components in a react project

Example usage:
var doc = require('react-composition-map');
var options = {
    "components":"./frontend/components/*.jsx", //folder to components in react project
    "singleFiles":[ //Add single files if you want them included
        "./frontend/main.jsx"
    ],
    "format":"png",
    "output":"./test/map.png"
};

doc.generateDoc(options);