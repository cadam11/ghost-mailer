# Mailer

A Ghost app for sending mail from forms.

------------------------------------------------------------------------

## Plan

The plan is for this app to expose an API endpoint that will accept a form post of data which will be the data used to render a template to generate HTML, which is then sent to the email address(es) configured.

### Parts

- REST endpoint
- Access the mail functions in Ghost
- Use Handlebars to format the email
- A way to build forms