# Egan Property Maintenance
Business website for Egan Property Maintenance — East Granby, CT.
Built with vanilla HTML, CSS, and JavaScript.

## Deployment
Deployed via Vercel. To deploy:
1. Push this repo to GitHub
2. Import the repo in Vercel (vercel.com/new)
3. Vercel auto-detects static site — no build settings needed
4. Click Deploy

## Contact Form — REQUIRED SETUP

Quote requests are delivered by [Web3Forms](https://web3forms.com) (free, no
backend). **The form will not send until an access key is filled in.**

1. Go to web3forms.com and enter `Ashtonegan12@gmail.com`
2. They email back a free access key
3. In `index.html`, find `WEB3FORMS_ACCESS_KEY` (in the `<script>` block near
   the bottom) and replace `PASTE-YOUR-ACCESS-KEY-HERE` with that key
4. Submit a test request and confirm it arrives — **check the spam folder**,
   the first one often lands there. Mark it "not spam" so later ones don't.

Until step 3 is done, submissions fail safely: the customer sees an error
telling them to call (860) 999-3161, and their typed details stay in the form.
They are never told the request went through when it didn't.

Free tier covers 250 submissions/month. Replies go to the customer's own
address, so Ashton can just hit Reply.

## To Add Real Photos
See the comments inside index.html marked with: <!-- PHOTO SLOT -->
