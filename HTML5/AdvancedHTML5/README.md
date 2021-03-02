# Advanced HTML5

## form tag

> The `<form>` tag is used to create an HTML form for user input.
>
> The `<form>` element can contain one or more of the following form elements:
>
> - `<input>`
> - `<textarea>`
> - `<button>`
> - `<select>` 
> - `<option>`
> - `<optgroup>`
> - `<fieldset>`
> - `<label>`
> - `<output>`
>
> The method attribute specifies how to send form-data (the form-data is sent to the page specified in the action attribute).
>
> The form-data can be sent as URL variables (with `method="get"`) or as HTTP post transaction (with `method="post"`).
>
> #### Notes on GET
>
> Appends form-data into the URL in name/value pairs. The length of a URL is limited (about 3000 characters).
>
> Never use GET to send sensitive data! (will be visible in the URL).
> Useful for form submissions where a user wants to bookmark the result
>
> GET is better for non-secure data, like query strings in Google
>
> #### Notes on POST
>
> Appends form-data inside the body of the `HTTP` request (data is not shown in URL
>
> Has no size limitations
> Form submissions with POST cannot be bookmarked

### Helpful Links

[w3schools](https://www.w3schools.com/)
