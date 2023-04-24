# crossroads-website


[![Netlify Status](https://api.netlify.com/api/v1/badges/5507b474-10fe-4df8-9224-fafc560d7f2a/deploy-status)](https://app.netlify.com/sites/crossroadschurch/deploys)

#\ Adding users 

This has to be done on the Identity Integrations page
https://app.netlify.com/sites/crossroadschurch/integrations/identity/netlify


The website can be edited at https://xrd.org.uk/admin/


## Hugo Theme 

This site uses a customizable theme 

The theme can be found at:

- https://themes.gohugo.io/themes/gohugo-theme-ananke/

And is hosted on GitHub at 

- https://github.com/theNewDynamic/gohugo-theme-ananke


##Custom CSS
In order to complement the default CSS with your own, you can add custom css files to the project.

Just add a assets/ananke/css directory to your project and add the file(s) in it.
Register the files using the custom_css key in your site's parameter. The path referenced in the parameter should be relative to the assets/ananke/css folder.
The css files will be added in their registered order to final main.css file.

For example, if your css files are assets/ananke/css/custom.css and assets/ananke/special.css then add the following to the config file:

  [params]
    custom_css = ["custom.css","special.css"]

# Adding CMS Users

You may add more users of the Netlify CMS at https://app.netlify.com/sites/crossroadschurch/integrations/identity/netlify
