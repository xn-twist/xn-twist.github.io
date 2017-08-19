---
layout: default
---

## What is XN-Twist?

XN-Twist is a project whose goal is to help individuals and organizations identify [internationalized domain names](https://wikipedia.org/wiki/Internationalized_domain_name) (also known as "Unicode domain names") that may be setup to attack their organization.

To read more about how attackers can use Unicode domain names to attack your organization and/or your customers, read more about [why](why) the project exists.

For now, suffice it to say that the XN-Twist project is comprised of four, crucial components:

1. The dataset classifier
2. The XN-Twist API
3. The XN-Twist algorithm
4. You!

![XN Twist](xn-twist.png)

The dataset classifier makes it easy to crowd-source the creation of a dataset (which is stored in the API) that captures which characters may be used to spoof basic, Latin characters. For example, an attacker may replace the Latin character `a` with `А` (a character from the Cyrillic alphabet) or `Α` (a character from the Greek alphabet). The dataset classifier lets us work together to create mappings which capture which characters may be used to spoof another. This data (again, which is stored in the XN-Twist API), is used in the XN-Twist algorithm to help organizations protect and defend themselves.

Just 30 seconds of your time can help make the internet a safer place! [Get started now!](http://xntwist.tk)
