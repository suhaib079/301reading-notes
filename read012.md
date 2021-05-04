# EJS Partials

EJS Partials help us avoid repetition of the same code on several web pages. For example, you may want the same header for several web pages. EJS partials work like EJS layouts too in creating a single fix content on a web page.


* How do you add partials in EJS?

Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.

        <%- include('partials/partial') %>
            <h4> Home Page</h4>


EJS partials work like EJS layouts too in creating a single fix content on a web page.

### How to use
In the files you want to use this element you add it like this:

```ejs
<%- include( PARTIAL_FILE ) %>
```

### Why use partials
using partials makes it easier to track and modify your elements making sure they're still the same across all your pages.
### Linking Partials in Templates
This new command include is telling Express to pull the contents of the named template and place it in place of this command.

We know that Express is already looking in the views directory for our templates, so when we give the name of the template to be included we consider that to be the root directory, but we still have to tell it to look in the partials folder that we made. so our template name would look like this.