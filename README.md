# Bosphorus Lounge AI Receptionist — Next.js Vercel Version

This is the clean Next.js version made specifically for Vercel.

## Upload to GitHub

Your GitHub repo must look like this at the top level:

```txt
app/
package.json
next.config.js
README.md
.env.example
```

Do **not** put these files inside another folder.

## Deploy on Vercel

1. Push this project to GitHub.
2. Go to Vercel.
3. Import the GitHub repo.
4. Framework should auto-detect as **Next.js**.
5. Add environment variables:

```txt
RESEND_API_KEY=your_resend_key
OWNER_EMAIL=bananabigbrain70@gmail.com
FROM_EMAIL=Bosphorus Lounge <onboarding@resend.dev>
```

6. Click Deploy.

## Email setup

This project uses Resend.

For testing, you can use:

```txt
FROM_EMAIL=Bosphorus Lounge <onboarding@resend.dev>
```

For production, verify a domain in Resend and use your real sender email.

## Features

- Smart reservation chatbot
- Change date/time/contact/guests
- Go back
- Restart
- Validation
- Confirmation before sending
- Automatic email via `/api/reservation`
- Mobile-friendly design
