HIFZULLAH.IN — FINAL PRODUCTION GITHUB PAGES PACKAGE WITH EMAILJS (v6)

1. BEFORE DEPLOYING — PASTE YOUR NEWLY REFRESHED EMAILJS PUBLIC KEY:
   Open `index.html`, find `EMAILJS_CONFIG` (near the bottom of the file), and replace:
     publicKey: 'YOUR_EMAILJS_PUBLIC_KEY'
   with your newly refreshed EmailJS Public Key from https://dashboard.emailjs.com/admin/account.
   (Never paste your Private Key or Titan SMTP password into `index.html`.)

2. EMAILJS SERVICE & TEMPLATE CONFIGURATION (FIXED):
   - Service ID : service_9egkxkc
   - Template ID: template_t62cxqt
   - Recipient  : md@hifzullah.in (fixed in EmailJS dashboard template)
   - Reply-To   : {{email}} (configured in EmailJS dashboard template)
   - Subject    : New {{inquiry_type}} — {{name}}
   - Template Variables Sent:
       {{inquiry_type}}, {{name}}, {{email}}, {{company}}, {{job_title}}, {{subject}}, {{message}}, {{time}}

3. GITHUB PAGES DEPLOYMENT:
   - Extract this ZIP and upload all contents (`index.html`, `CNAME`, `README.md`, `README_PUBLISH.txt`, and `assets/`) directly to the ROOT of the `main` branch in `HifzCodes/HifzCodes.github.io`.
   - Ensure `hifzullah.in` is added under Allowed Origins / Domain Restrictions in your EmailJS dashboard.
