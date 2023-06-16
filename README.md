# Sign-Up Form

Form created using HTML and CSS only.

🔗 [Live preview](https://thaysmartinez.github.io/sign-up-form/)

![alt text](./img/signup-form_img.png)

## Main challenges

The default email validation for email input type elements matches only for
i.e. `username@domain`. I wanted to add a more robust e-mail validation,
matching also for domain extension i.e.: `username@domain.domainextension`

I tried several different patterns of regexp but warning message was not being
displayed upon change of focus nor submission.

This proved to be more complex than expected so I decided to keep the default
validation for now and add JavaScript validation for a future codebase refactor.
By then I'll also validate phone number against a predefined pattern and if both
password fields matches. These improvements were added in the
**_What can be improved_** section below for future reference.

## Concepts I learned and put into practice

- CSS Units
- CSS Properties
- Advanced selectors
- CSS Positioning: relative, absolute
- CSS Functions
- Custom Properties
- Form
- Form validation
- Form styling
- Regular expressions

## What can be improved

- Validate email address to match against username, domain and domain extension
- Validate phone number against a predefined pattern and/or character length
- Check if `PASSWORD` and `CONFIRM PASSWORD` fields match
- Add responsive layout to accomodate for small screens
