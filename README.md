# Egan Property Maintenance
Business website for Egan Property Maintenance — East Granby, CT.
Built with vanilla HTML, CSS, and JavaScript.

## Deployment
Deployed via Vercel. To deploy:
1. Push this repo to GitHub
2. Import the repo in Vercel (vercel.com/new)
3. Vercel auto-detects static site — no build settings needed
4. Click Deploy

## Contact Form

Quote requests are delivered by [Web3Forms](https://web3forms.com) (free, no
backend) to **Ashtonegan12@gmail.com**. Verified working against the live API.

The `WEB3FORMS_ACCESS_KEY` constant in `index.html` is what routes submissions
to that inbox — the destination is bound to the key, so **changing who receives
leads means generating a new key**, not editing a recipient field. The key is
public by design; it ships in client-side JS on every page load.

If a submission ever fails, the customer sees an error telling them to call
(860) 999-3161 and their typed details stay in the form so they can retry.
They are never told a request went through when it didn't.

Free tier covers 250 submissions/month. Replies go to the customer's own
address, so Ashton can just hit Reply.

Two things worth doing in the Web3Forms dashboard: turn on the domain
allowlist (restrict to eganpropertymaintenance.com) so the public key can't be
used from other sites, and check that the first notification email didn't land
in spam — mark it "not spam" if it did.

## To Add Real Photos
See the comments inside index.html marked with: <!-- PHOTO SLOT -->
