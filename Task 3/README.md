# Advanced Job Application Form

## 📝 Project Description

This project is an advanced job application form webpage built entirely with HTML. It is designed to collect comprehensive information from job applicants, including personal details, desired position, availability, skills, experience, and resume upload. The form incorporates a variety of HTML elements and attributes, focusing on semantics and accessibility best practices.

This project was completed as part of Lecture 3.

## 🛠️ HTML Tags and Attributes Used

Below is a list of key HTML tags and attributes utilized in this project:

### Document Structure:
- `<!DOCTYPE html>`: Defines the document type.
- `<html lang="en">`: The root element, specifying the language.
- `<head>`: Contains meta-information about the HTML document.
  - `<meta charset="UTF-8">`: Specifies character encoding.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configures the viewport for responsiveness.
  - `<meta name="description" content="...">`: Provides a description for search engines.
  - `<title>`: Sets the title of the browser tab or window.
  - `<style>`: (Used for internal CSS in this example, could be an external stylesheet link).
- `<body>`: Contains the visible page content.

### Content Structure:
- `<header>`: Represents introductory content or a set of navigational links.
  - `<h1>`: Main heading of the page.
  - `<p>`: Paragraph text.
- `<main>`: Specifies the main content of a document.
- `<form action="#" method="post">`: Creates an HTML form for user input.
  - `action`: Specifies where to send the form-data when a form is submitted.
  - `method`: Specifies the HTTP method to use when sending form-data (`post` or `get`).
- `<fieldset>`: Groups related elements in a form.
  - `<legend>`: Defines a caption for the `<fieldset>` element.

### Form Elements:
- `<label for="inputId">`: Defines a label for an `<input>` element.
  - `for`: Binds the label to an input element by its `id`.
- `<input>`: Used to create interactive controls for web-based forms.
  - `type="text"`: Single-line text input.
  - `type="email"`: For email addresses (includes basic client-side validation).
  - `type="tel"`: For telephone numbers.
  - `type="url"`: For URLs (includes basic client-side validation).
  - `type="number"`: For numerical input.
    - `min`: Specifies the minimum value.
  - `type="password"`: For password input (characters are masked).
    - `minlength`: Specifies the minimum number of characters.
  - `type="checkbox"`: Allows selection of zero or more options from a set.
  - `type="radio"`: Allows selection of one option from a set.
    - `checked`: Pre-selects a radio button.
  - `type="file"`: Allows users to upload files.
    - `accept`: Specifies the types of files that the server accepts.
  - `type="hidden"`: For data that should not be visible to the user but sent with the form.
  - `id`: Specifies a unique id for an element.
  - `name`: Specifies the name of an input element (used when submitting the form).
  - `required`: Makes an input field mandatory.
  - `placeholder`: Provides a hint to the user of what can be entered.
  - `list`: Refers to a `<datalist>` element that contains pre-defined options for an input field.
- `<datalist id="positionsId">`: Contains a list of pre-defined options for an `<input>` element.
  - `<option value="value">`: Defines an option in a `<datalist>` or `<select>` list.
- `<textarea rows="" cols="">`: Multi-line text input.
  - `rows`: Specifies the visible number of lines.
  - `cols`: Specifies the visible width.
- `<select name="selectName">`: Creates a drop-down list.
- `<button type="submit">`: Defines a clickable button.
  - `type="submit"`: Submits the form data.

### Accessibility Attributes:
- `aria-label="description"`: Provides an accessible label for an element when a visible label is not practical or sufficient.

### General Attributes:
- `class`: Specifies one or more class names for an element (used for CSS styling).

## 🧑‍💻 Author

- **Amal Fathieh**

---

*This README was created based on the requirements of the Lecture 3 task.*