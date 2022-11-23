# sendgrid-account-monitor

The scheduled GitHub action sends mails to keep your SendGrid account active.

## Set up

You need to set below Action secrets:

- `RECIPIENT` : A recipient mail address
- `SENDER` : A sender mail address. You'd better use a qualified domain with Domain Authentication in your SendGrid account.
- `SG_APIKEY` : A SendGrid API Key. You just have to set Mail Send permission with it.

## How to use

You don't need to do anything else.
Github Actions sends email automatically and periodically.
This makes constant MailSend activity, so your SendGrid account is not inactive anymore.

