# formspree-contact-form
This contact form is useful to create quick functionality with formspree implimentation on HTML forms
NO JS/PHP/AJAX
Note that this form uses https://formspree.io/ as a third party.

Please note some additional id's and classes are included.

The primary form necessary is:

<form action="https://formspree.io/your@email.com"
      method="POST">
    <input type="text" name="name">
    <input type="email" name="_replyto">
    <input type="submit" value="Send">
</form>
