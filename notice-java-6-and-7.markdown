---
layout: post
title: 'Notice: Java 6 and 7 users: SSL Protocol upgrades coming to Central'
date: '2018-06-13T07:57:53+00:00'
permalink: notice-java-6-and-7
---
<p>The march of standards continues unabated. Legacy TLS protocols 1.0
and 1.1 have varying weaknesses that could lead to a false sense of
security.</p>
<p>
In June, in an effort to raise security and comply with modern
standards, the insecure TLS 1.0 & 1.1 protocols will no longer be
supported for SSL connections to Central. This should only affect
users of Java 6 that are also using https to access central, which by
our metrics is less than .2% of users.</p>

<p>
At the same time, this conversion will allow Central to support HTTP/2
with potential performance gains for modern http clients.</p>
<p>
The details about why, when and what you need to do are documented at
the link below. As questions come up, we will continue to update this
faq.</p>
<p>
If there is specific information required for non-maven build systems,
please send it along and we will include that as well.</p>

<a href="https://central.sonatype.org/articles/2018/May/04/discontinue-support-for-tlsv11-and-below/">https://central.sonatype.org/articles/2018/May/04/discontinue-support-for-tlsv11-and-below/
</a>
<p>
The same content has been posted as a blog to make it easier to
disseminate here:
<a href="https://blog.sonatype.com/enhancing-ssl-security-and-http/2-support-for-central">https://blog.sonatype.com/enhancing-ssl-security-and-http/2-support-for-central</a>
</p>
