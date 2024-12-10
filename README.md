# form-contact


This is a copy of the [Red Cross Contact page](https://www.rodekors.no/om/kontakt/)
You can open it by clicking on this link
[https://norwegianredcross.github.io/form-contact/](https://norwegianredcross.github.io/form-contact/
)

What we are doing here is to add a contact form that talk to our backend.

The form is in the [public/contact-form](public/contact-form.js)

To embedd it into the website you need to add two lines.

The script

```html
<!-- THECONTACTFORM script -->                                        
<script src="https://norwegianredcross.github.io/form-contact/public/contact-form.js"></script>
````

And the css for the form

```html
    <!-- THECONTACTFORM styles -->
    <link rel="stylesheet" href="https://norwegianredcross.github.io/form-contact/public/contact-form.css">
````

Our backend will receive the form on this enpoint: `https://api-dev.redcross.no/forms/contact-form/v1`
