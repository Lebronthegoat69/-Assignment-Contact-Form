# Contact Form
## Description
This project is an ASP.NET Core Razor Pages contact form. Users can enter their name, email address, and message and submit the form.
## Features
- Contact form with Name, Email, and Message fields
- Required field validation
- Email address validation
- Thank You page after a successful submission
- Saves contact submissions to `data/contacts.json`
- Supports multiple contact submissions
## Pages
- `/Contact` — Contact form
- `/ThankYou` — Confirmation page after submitting the form
## Technologies
- C#
- ASP.NET Core
- Razor Pages
- JSON
 How to Run
1. Open the project in Visual Studio.
2. Build the solution.
3. Run the project.
4. Open the Contact page.
5. Enter a name, email, and message.
6. Click **Send Message**.
7. The submission will be saved in `data/contacts.json`.