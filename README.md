# fire-up

## Week 1 (May 24, 2018)

// Use pod structure
Modify .ember-cli to add `usePods: true`

ember g controller application
ember g template application
    - Add {{outlet}}

git rm -r app/templates
git rm -r app/controllers

"component-driven development"


// Install ember-freestyle
ember install ember-freestyle
ember s


// Create a route
ember g route component-guide
ember g controller component-guide


// Move the content of controllers/freestyle.js to component-guide/controller.js
// Move the content of templates/freestyle.hbs to component-guide/template.hbs
// We can remove the controllers and templates folders


// Clear the template in component-guide/template.hbs
// Clear the controller in component-guide/controller.js after emberFreestyle