# EJS Partials

EJS Partials help us avoid repetition of the same code on several web pages. For example, you may want the same header for several web pages. EJS partials work like EJS layouts too in creating a single fix content on a web page.


* How do you add partials in EJS?

Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.

        <%- include('partials/partial') %>
            <h4> Home Page</h4>


EJS partials work like EJS layouts too in creating a single fix content on a web page.

