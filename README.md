# MODX-GDPR
Crowdsourced ideas/tools/checklists/resources for complying with the GDPR on MODX-powered sites/appes

## General

**Do your own research**. How you collect and process data is different from one organization to the next, so while this list attempts to be useful in getting you on your way, it is by no means meant as legal advice or authoritative on what you should or should not do with relation to the GDPR.

## Cookies

- The `PHPSESSID` cookie in MODX is a functional cookie used for managing sessions. It can be renamed with the `session_cookie_name` system setting. You do not require specific consent for functional cookies, but if you perform additional tracking or personalisation in the related session, you will need to communicate that clearly to customers. 

## Common Extras

- FormIt allows you to collect form submissions, which contains personal data like names and email address. Make sure FormIt is set to encrypt forms to protect the data and that if you use hooks to process it further (signup to a newsletter or add to another list) that the customer explicitly consents to that processing.

- With the Login package you can accept registrations and manage user accounts. Make sure to use the UpdateProfile extra to comply with the right to correct and see stored personal information.
