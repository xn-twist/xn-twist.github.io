---
layout: default
---

## An Introduction to Domain Squats

If you are not familiar with the term "Domain Squat", here 
is a basic definition:

> A domain squat is a domain name that is registered because it looks like the domain belonging to another entity or organization.

It is common for someone who wants to attack a company to register a domain that *looks* similar to a domain name belonging to the organization they are targeting (you can see some examples [here](https://app.threatconnect.com/auth/browse/index.xhtml?filters=typeName%20in%20(%22Address%22%2C%20%22EmailAddress%22%2C%20%22File%22%2C%20%22Host%22%2C%20%22URL%22%2C%20%22ASN%22%2C%20%22CIDR%22%2C%20%22Mutex%22%2C%20%22Registry%20Key%22%2C%20%22User%20Agent%22)%20and%20tag%20in%20(%22Typosquatting%22)&intelType=indicators&owners=631)). For example, if some adversaries were targeting Apple as a company or even Apple customers, they may register domain squats of apple.com like `aple.com`, `appie.com`, and `appb.com`. They could then setup each of these websites to look like apple.com and send emails with links to these domains prompting users to login to their accounts for some fictitious reason (usually the email will say that something is wrong with the user's account or offer a reward). If you user isn't careful and clicks the link, they will go to a domain squat and may enter their user name and password. Because they are visiting a domain squat rather than the real site, their user name and password are sent to the adversaries instead of logging into their apple account.

### Types of Domain Squats

Here is a break-down of some of the most common types of domain squats:

#### Typosquats

A typosquat is a domain squat that is registered because it would be easy for someone to visit that page if they mistyped something. For example, if I am trying to type `amazon.com`, I may type "n" instead of "m" and end up typing `anazon.com`. If someone registered `anazon.com`, I would end up going to their website. Even worse, if the page is designed to look like Amazon's, I may not even notice I'm in the wrong place and may give away my user name and password by trying to login to the fake site.

#### Bitsquats

A bitsquat is a particularly insidious flavour of domain squat in which computer hardware errors (at the electrical level) cause a computer to a make an incorrect [DNS](https://en.wikipedia.org/wiki/Domain_Name_System) request. To learn more about this type of domain squat, I recommend the original presentation on the subject here: [https://www.youtube.com/watch?v=aT7mnSstKGs](https://www.youtube.com/watch?v=aT7mnSstKGs).

#### Homovisio Domain Squats

This type of domain squats include domains that are intentionally created to *look* or *appear* like another domain. For example, `goggle.com` is a rather convincing homovisio domain squat of `google.com`. At a quick glance, the domains appear to be the same. It is not a typosquat (it is unlikely that someone would type "g" when trying to type "o"), but it would be very effective if you sent a link to this site in an email. A subcategory of homovisio domain squats are Unicode (a.k.a internationalized) domain squats.

##### Unicode (Internationalized) Domain Squats

Unicode, or Internationalized, domain squats are homovisio domain squats that use [Unicode](https://en.wikipedia.org/wiki/Unicode) characters in a domain name to look like another domain. For example, if you wanted to spoof `google.com`, you might replace the last letter "e" with the character "è", thus forming: `googlè.com`. Like other homovisio domain squats, the difference between the two domains is very subtle and if you aren't careful you wouldn't even notice the difference. You can read more about internationalized domain names here: [https://en.wikipedia.org/wiki/Internationalized_domain_name](https://en.wikipedia.org/wiki/Internationalized_domain_name). The XN-Twist project is designed to help identify and monitor this type of domain squat.
