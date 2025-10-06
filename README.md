# Email Signup Landing Page

A clean, responsive landing page with Formspree email signup integration.

## Setup Instructions

### 1. Get Your Formspree Form ID

1. Go to [formspree.io](https://formspree.io)
2. Sign up for a free account (or log in)
3. Create a new form
4. Copy your form ID (it looks like `xwkgabcd`)

### 2. Update the Form Action

Open `index.html` and replace `YOUR_FORM_ID` with your actual Formspree form ID:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

Should become:

```html
<form action="https://formspree.io/f/xwkgabcd" method="POST">
```

### 3. Deploy to Netlify

#### Option A: Drag & Drop
1. Go to [netlify.com](https://netlify.com)
2. Sign up or log in
3. Drag the entire `landing-page` folder to the deploy area

#### Option B: Git Deploy
1. Initialize git in this folder: `git init`
2. Create a new repo on GitHub
3. Push this code to GitHub
4. Connect your GitHub repo to Netlify
5. Deploy!

## Features

- ✅ Clean, modern design
- ✅ Fully responsive (mobile-friendly)
- ✅ Formspree integration
- ✅ Success message after submission
- ✅ Form validation
- ✅ No build process required - pure HTML/CSS/JS

## Customization

You can easily customize:
- **Colors**: Edit the gradient colors in the CSS
- **Text**: Update the h1 and p tags
- **Form fields**: Add/remove fields as needed

## Free Tier Limits

Formspree free tier includes:
- 50 submissions per month
- Email notifications
- Spam filtering
