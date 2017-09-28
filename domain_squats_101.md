---
layout: default
---

## An Introduction to Domain Squats

If you are not familiar with the term "Domain Squat", here 
is a basic definition:

> A domain squat is a domain name that is registered because it looks like the domain belonging to another entity or organization.

It is common for someone who wants to attack a company to register a domain that *looks* similar to a domain name belonging to the organization they are targeting (you can see some examples [here](https://app.threatconnect.com/auth/browse/index.xhtml?filters=typeName%20in%20(%22Address%22%2C%20%22EmailAddress%22%2C%20%22File%22%2C%20%22Host%22%2C%20%22URL%22%2C%20%22ASN%22%2C%20%22CIDR%22%2C%20%22Mutex%22%2C%20%22Registry%20Key%22%2C%20%22User%20Agent%22)%20and%20tag%20in%20(%22Typosquatting%22)&intelType=indicators&owners=631)). For example, if some adversaries were targeting Apple as a company or even Apple customers, they may register domain squats of apple.com like `aple.com`, `appie.com`, and `appb.com`. They could then setup each of these websites to look like apple.com and send emails with links to these domains prompting users to login to their accounts for some fictitious reason (usually the email will say that something is wrong with the user's account or offer a reward). If you user isn't careful and clicks the link, they will go to a domain squat and may enter their user name and password. Because they are visiting a domain squat rather than the real site, their user name and password are sent to the adversaries instead of logging into their apple account.
