# Frontend Mentor - Contact form solution

This is a solution to the [Contact form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/contact-form--G-hYlqKJj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- Overview

  > The challenge
  > Screenshot
  > Links

- My Process

  > Built with
  > What I learned
  > Continued development
  > Useful resources

- Author

Acknowledgments

## Overview

### The challenge

Users should be able to:

- Complete the form and see a success toast message upon successful submission
- Receive form validation messages if:
  - A required field has been missed
  - The email address is not formatted correctly
- Complete the form only using their keyboard
- Have inputs, error messages, and the success message announced on their screen reader
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

!C:\Users\pc\Desktop\Screenshot contact form.jpg

### Links

- Solution URL: https://github.com/catherine-chioma/contact-form-project
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

Semantic HTML5 markup
CSS custom properties
Flexbox for responsive design
Mobile-first workflow
[JavaScript]
[PHP]

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!-- A snippet of the form structure I implemented -->
<div class="name-container">
  <div class="form-group">
    <label for="firstname">First Name *</label>
    <input type="text" id="firstname" name="firstname" required />
  </div>
  <div class="form-group">
    <label for="lastname">Last Name *</label>
    <input type="text" id="lastname" name="lastname" required />
  </div>
</div>

/* Some CSS code I'm proud of */ .name-container { display: flex; gap: 20px; }
@media (max-width: 768px) { .name-container { flex-direction: column; } }
##Author - Linkedln -https://www.linkedin.com/in/catherinechioma/ -
FrontendMentor[@catherine-chioma](https://www.frontendmentor.io/profile/catherine-chioma)
- Twitter - [@c_ihuaku](https://www.twitter.com/c_ihuaku) ##Acknowledgments A
Big thank you to Frontend Mentor for providing this challenge, which helped me
improve my skills in building responsive forms.
```
