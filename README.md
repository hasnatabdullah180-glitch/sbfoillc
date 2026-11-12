# SBFOI Business Solutions Website

Brand direction: balanced digital agency + e-commerce consulting, targeting the United States first and expanding internationally over time.

Public-facing brand: **SBFOI Business Solutions**  
Business inquiry email: **sbfoiweb@gmail.com**

A responsive Next.js website for SBFOI LLC, positioned as a digital business, e-commerce consulting and global commerce solutions company.

## Run locally
1. Install Node.js 20 or newer.
2. Run `npm install`.
3. Copy `.env.example` to `.env.local` and update values if you want email delivery.
4. Run `npm run dev` and open http://localhost:3000.

## Deploy to Vercel
1. Push this folder to a GitHub repository.
2. Import the repository at https://vercel.com/new.
3. Deploy using the default Next.js settings.
4. Add environment variables from `.env.example` in Vercel Project Settings.
5. Connect your domain in Vercel.

## Contact form
The contact form uses `/api/contact`. To send email, configure a Resend API key and a verified sender domain. Without configuration, the form provides a clear email fallback instead of pretending the message was sent.

## Before publishing
- Verify the exact legal entity name against the filed New Mexico formation documents.
- Replace `sbfoiweb@gmail.com` with your active business email if needed.
- Confirm your domain and social links.
- Review service scope, prices, privacy policy and terms with appropriate professional advice.
- Only publish services that you can actually deliver. Pricing is illustrative starting pricing, not a binding quote.
- Do not present the registered/principal address as a staffed office unless that is accurate.


## Finalized brand direction
- Public brand: SBFOI Business Solutions
- Business focus: digital services and e-commerce equally
- Initial target market: United States; international markets later
- Contact inbox: sbfoiweb@gmail.com

## Important production setup
- In Vercel, set `CONTACT_TO_EMAIL=sbfoiweb@gmail.com`.
- Configure `RESEND_API_KEY` and a verified sender address/domain in `CONTACT_FROM_EMAIL`. The recipient can be a Gmail inbox; the sender should be a domain you control and have verified with your email provider.
- Set `NEXT_PUBLIC_SITE_URL` to your actual deployed domain.
- Replace the placeholder domain in metadata when the domain is selected.
