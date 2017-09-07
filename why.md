---
layout: default
---

## Why is XN-Twist? (Why does it exist?)

I'm going to answer in two ways. **First**, I'll answer why XN-Twist exists in the sense of what caused and motivated me to start the project. **Second**, I'll describe the goals and objectives of the project.

### XN-Twist's Cause(s)

To answer the first question, the XN-Twist project came about I found an [internationalized domain name](https://en.wikipedia.org/wiki/Internationalized_domain_name) (or more appropriately 'Unicode domain name') being used as part of a [phishing](https://wikipedia.org/wiki/Phishing) campaign for the first time. I hadn't heard of Unicode/Internationalized domains before this time and I was shocked that these domains where not being used more often. As I began to investigate further, it quickly became apparent that internationalized domains posed a bit of a one-way problem. It is very easy, given an internationalized domain spoofing a legitimate domain, to identify what the internationalized domain name is trying to spoof, but it is more difficult to work in the other direction (finding the possible internationalized domain squats of a given domain name).

```
EASY: internationalized domain spoof ==> legitimate domain name
```

```
HARDER: legitimate domain name ==> internationalized domain spoof
```

Thus, this project began when I realized that most organizations only have the capability to *react* to internationalized domain squats rather than pro-actively identifying, monitoring, and registering potentially dangerous domains.

### XN-Twist's Objective(s)

XN-Twist's primary objective is to solve the problem described above. As such, I summarize our mission by saying:

> The mission of the XN-Twist project is to provide individuals and organizations with a means of pro-actively identifying and monitoring internationalized domain squats.

Sound like something you're interested in? To help us out, it literal takes less than 60 seconds! Find out [how](how).
