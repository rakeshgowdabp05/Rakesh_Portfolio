# Rakesh Gowda B P — Portfolio

A clean, responsive personal portfolio website for **Rakesh Gowda B P**, built with HTML, CSS, and Vanilla JavaScript.

## Highlights

- Responsive portfolio layout
- First-uploaded ZIP color palette restored
- Profile photo section retained
- Resume PDF included
- Contact form integrated using EmailJS
- Premium HTML email template included
- No Node.js or Express.js backend files

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- EmailJS for no-backend contact form sending

## Run locally

Open terminal inside the project folder and run:

```bash
jwebserver -p 5500
```

Then open:

```text
http://127.0.0.1:5500
```

## Contact form setup

Read `CONTACT_FORM_SETUP.md` and replace the EmailJS placeholders inside `index.html`:

```js
publicKey: "PASTE_YOUR_EMAILJS_PUBLIC_KEY",
serviceId: "PASTE_YOUR_EMAILJS_SERVICE_ID",
templateId: "PASTE_YOUR_EMAILJS_TEMPLATE_ID",
```

Then copy `premium-emailjs-template.html` into the EmailJS template editor.

## Author

**Rakesh Gowda B P**  
Java Full Stack Developer
