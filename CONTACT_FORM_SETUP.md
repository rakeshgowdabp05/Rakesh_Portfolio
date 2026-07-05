# Contact Form Setup — EmailJS No-Backend Version

This portfolio contact form uses **EmailJS**. It does not need Node.js, Express.js, Java backend, database, or server code.

## Files changed

- `index.html` — contact form now sends using EmailJS from browser JavaScript.
- `premium-emailjs-template.html` — copy this HTML into the EmailJS template editor.

## Setup steps

1. Create/login to EmailJS.
2. Add your email service, for example Gmail.
3. Create a new email template.
4. Copy all content from `premium-emailjs-template.html` and paste it into the EmailJS template HTML editor.
5. In the EmailJS template settings, keep these variables:
   - `{{from_name}}`
   - `{{from_email}}`
   - `{{reply_to}}`
   - `{{subject}}`
   - `{{message}}`
   - `{{submitted_at}}`
   - `{{portfolio_owner}}`
6. Open `index.html` and replace:

```js
publicKey: "PASTE_YOUR_EMAILJS_PUBLIC_KEY",
serviceId: "PASTE_YOUR_EMAILJS_SERVICE_ID",
templateId: "PASTE_YOUR_EMAILJS_TEMPLATE_ID",
```

with your real EmailJS values.

## Test checklist

- Run the portfolio locally using `jwebserver -p 5500`.
- Open `http://127.0.0.1:5500`.
- Fill the contact form.
- Submit.
- You should see a success message and redirect to `thank-you.html`.
- Check your Gmail inbox/spam folder for the designed email.

## Important

Until you replace the three EmailJS placeholder values, the form will show a setup warning instead of sending. This avoids silent errors.
