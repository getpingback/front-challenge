# Lead Capture Embed Form Challenge

## Overview

Welcome to the Pingback Frontend Developer Challenge! In this project, you will create an embeddable form component for lead capture, similar to those used in email marketing platforms. This challenge is designed to test your skills in React, TypeScript, and modern frontend development practices.

## Project Requirements

### Technologies to Use

- React
- TypeScript
- CSS (approach of your choice)
- Build tool of your choice (e.g., Webpack, Vite)

### Core Features

1. **Embeddable Form Component**

   - Create a React component that can be compiled into a single JavaScript file for easy embedding in any website.
   - The component should be customizable through HTML attributes.

2. **Field Types**

   - Implement the following field types:
     - Text input
     - Dropdown (select)
     - Textarea

3. **Validation**

   - Include built-in validation for:
     - Email addresses
     - Phone numbers
   - Allow fields to be marked as required or optional

4. **Customization**

   - Enable customization of field types and properties via HTML attributes

5. **Styling**
   - Use CSS for styling (approach of your choice)
   - Ensure the form is responsive and looks good on various screen sizes

### Detailed Requirements

#### Embeddable Script

- The final output should be a single JavaScript file that can be included in an HTML page.
- Users should be able to render the form by adding a custom element to their HTML, e.g.:
  ```html
  <pingback-form id="lead-capture"></pingback-form>
  ```

#### Field Configuration

- Allow users to configure fields using data attributes, for example:
  ```html
  <pingback-form
    id="lead-capture"
    data-fields='[
      {"name": "name", "type": "text", "label": "Full Name", "required": true},
      {"name": "email", "type": "email", "label": "Email Address", "required": true},
      {"name": "phone", "type": "tel", "label": "Phone Number", "required": false},
      {"name": "role", "type": "select", "label": "Your Role", "options": ["Developer", "Designer", "Manager"], "required": true},
      {"name": "message", "type": "textarea", "label": "Message", "required": false}
    ]'
  >
  </pingback-form>
  ```

#### Validation

- Implement client-side validation for all fields
- Display error messages for invalid inputs
- Ensure email and phone number fields have specific validation rules

#### Submission

- On form submission, collect all form data and log it to the console (in a real-world scenario, this would be sent to a server)
- Display a success message after successful submission

#### Styling

- Use CSS for styling (approach of your choice)
- Ensure the form is visually appealing and matches modern design standards
- Make the form responsive, working well on both desktop and mobile devices

## Development Instructions

1. Set up a new React project with TypeScript support
2. Choose and implement your preferred CSS approach
3. Develop the form component according to the specifications above
4. Set up a build process that compiles your React component into a single JavaScript file
5. Create a sample `index.html` file demonstrating how to use the embedded form

## Deliverables

1. Source code for the React component
2. Compiled JavaScript file for embedding
3. Sample `index.html` file showing usage of the embed
4. Brief documentation on how to use and customize the form

## Evaluation Criteria

Your submission will be evaluated based on:

1. Code quality and organization
2. Proper use of React and TypeScript
3. Implementation of required features
4. Validation and error handling
5. Styling and responsiveness
6. Build process and ease of embedding

## Submission Instructions

1. Create a GitHub repository for your project
2. Push your code to the repository
3. Include all necessary documentation in the README.md file
4. Ensure your repository is public or provide access to reviewers
5. Send the link to your repository to pedro.ladeira@getpingback.com

Good luck! We look forward to seeing your creative and technical solutions to this challenge.
