# Sideline Sprint (Misc.)

This repo contains miscellaneous code related to the Sideline Sprint project I worked on.

This primarily involves two things:
- Database tables
- Email templates

The database tables were used for the general operation of the newsletter. They housed
things including our readers, staff, and feedback from readers. These were all run
against a Postgres database hosted on DigitalOcean.

The email templates covered everything from signup welcomes, to the daily newsletter,
to referral rewards. There were also email templates used for special events like
Olympics coverage and inviting users to our Discord server. These templates were
written using MJML, then exported to HTML and/or text files depending on the use
case.