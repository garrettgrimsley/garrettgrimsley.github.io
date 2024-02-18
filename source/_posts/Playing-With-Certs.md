---
title: Playing with Certs
date: 2023-09-20 21:07:36
tags:
---
# Certificates

I have recently been doing a lot of work around TLS Certificates and was looking  
into creating a browser extension to be able to quickly view the contents of a  
certificate. I searched around and found one that advertised this functionality,  
but unfortunately it did not work. The source code for the extension was on GitHub  
and when I looked into it, it turns out that the certificate is being sent to a  
remote host for decoding, and the domain for that remote host had expired.

So, I registered the domain. More to follow.