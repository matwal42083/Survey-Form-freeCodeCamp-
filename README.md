# freeCodeCamp Form Practice

A learning project for practicing HTML forms and CSS. Although the repository name mentions a survey, the page currently builds a **registration form**: it asks for account details and includes a short referral question.

## Project origin

<a href="https://www.freecodecamp.org/learn/">
  <img src="https://raw.githubusercontent.com/matwal42083/myPortfolio/main/src/assets/images/freeCodeCampLogo.jpg" alt="freeCodeCamp logo" width="150">
</a>

Built while learning with freeCodeCamp's [Learn HTML Forms by Building a Registration Form](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-html-forms-by-building-a-registration-form/step-1) lesson.

## What the form includes

- Name, email, and password fields.
- Personal or business account selection.
- Optional profile picture, age, referral source, and bio fields.
- A required terms-and-conditions checkbox and submit button.
- A dark color scheme and a centered layout sized with CSS.

## What you can learn

This repository is for learners practicing the foundations of web forms:

- **HTML form structure:** group related controls with `fieldset` and `legend`, and connect labels to inputs.
- **Form controls:** use text, email, password, radio, file, number, checkbox, select, and textarea fields.
- **Browser validation:** try `required`, email input validation, age limits, and a password `pattern`.
- **CSS styling:** practice selectors, colors, spacing, width constraints, and styling different controls.
- **Form submission:** inspect the form's `method` and `action` to see where submitted data is sent.

> [!IMPORTANT]
> The form posts to freeCodeCamp's demo registration endpoint. Do not enter real passwords or sensitive information. Browser validation alone does not make a form secure, and this is not a production registration system.

## Run locally

No dependencies or build step are needed. For example, in Ubuntu on WSL2, clone it into a `dev/learning` directory:

```bash
mkdir -p ~/dev/learning
cd ~/dev/learning
git clone https://github.com/matwal42083/Survey-Form-freeCodeCamp-.git
cd Survey-Form-freeCodeCamp-
```

Open `index.html` in a browser to explore the form. You can also download the repository and open the file directly.

## Project files

- `index.html` — form structure, fields, labels, and validation attributes.
- `styles.css` — layout, colors, spacing, and form control styling.

## Ideas for practice

- Experiment with field labels, placeholders, and validation rules.
- Add survey questions and try different input types.
- Adjust the layout and colors, then check the form at different screen widths.

Make changes locally and compare how the HTML and CSS affect the page. These exercises are for learning, not for collecting real user data.
