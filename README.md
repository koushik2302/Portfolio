# Portfolio — Koushik C

Personal portfolio. MBA (Operations major, Business Analytics minor), PES University.
Targeting operations and analyst roles.

**Live:** https://portfolio-three-rho-5hjlv8xfgl.vercel.app

## Structure

```
index.html    Single-file site — HTML, CSS and JS inline. No build step.
assets/       Résumé PDF, profile image
```

Deploys as static files. Vercel, Netlify, GitHub Pages — anything works.

## Contact form

Backed by [Web3Forms](https://web3forms.com). The access key sits in `index.html`
and that is intentional — it's a **public submission key**. It can only send mail
to the form owner; it cannot read submissions or access any account data. Web3Forms
documents it as safe for client-side use.

A honeypot field (`botcheck`) catches naive bots. If spam becomes a problem,
Web3Forms offers free hCaptcha integration.

## Local

Open `index.html`. That's it.
