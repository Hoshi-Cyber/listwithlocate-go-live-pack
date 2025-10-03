
provider: "REQUIRED  # Formspree | Netlify Forms | Resend | AWS SES + Lambda | Other"
intake_endpoint: "REQUIRED"
contact_endpoint: "REQUIRED"
spam_protection: "REQUIRED  # reCAPTCHA v3 | hCaptcha"
data_retention_days: 365
notification_emails:
  - "REQUIRED"
