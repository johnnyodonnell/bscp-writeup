
# Review of the Burp Suite Certified Practitioner certification

### Introduction

I attained the Burp Suite Certified Practitioner (BSCP) certification on
June 4th, 2023 after about 2 months of study. Jorge Sanchez, my
manager at Anvil Secure, purchased an exam attempt from PortSwigger
on April 11th, 2023; and I started working through the labs a few
days after that.

I had previously attained the OSCP and OSWE certifications from
Offensive Security, so I was already familiar with a number
(but not all) of the topics that would be tested on the exam.


### My Study Plan

As part of my study plan, I completed all novice- and
practitioner-level labs, which totalled to 204 labs at the time of
this writing. Also, as part of PortSwigger's recommended study plan,
I completed 5 practitioner-level mystery labs and completed the
practice exam.

It took me two attempts to pass the practice exam. The reason
that I failed on the first attempt of the practice exam was because
I attempted an INSERT operation during an SQLi exploit, and that
for some reason caused the admin panel to become inaccessible. I
believe that PortSwigger intentionally designed the application to
exhibit this behavior in order to illustrate the drawbacks of
executing imprecise mutating exploits.

The most important lesson/lab module was
[Using Burp Scanner during manual testing](https://portswigger.net/web-security/essential-skills/using-burp-scanner-during-manual-testing).
This module was so important because it teaches you how to find
vulnerabilities quickly with Burp's active scanner. In all other labs
you know which vulnerability to look for, and oftentimes the lab will
give you a strong hint as to where to look for that vulnerability. During
the exam, you have no idea which vulnerabilities to look for or where
within the application to look for them; thus, you will have to rely
on Burp's active scanner to find most of these vulnerabillities.


### The Exam

For the exam, you have 4 hours to capture a flag in each of the two
web applications. The hardest part of the exam is the short time
window that you have to capture these flags. You have to be quick,
and you need to use Burp's active scanner to help find most
vulnerabilities for you.

It took me two attempts to pass the exam. On my first attempt
I felt that I was so close to passing that I took my second attempt
immediately after.


### Comparison to OSCP

I think that the BSCP and OSCP are about equally difficult,
and the skills that are tested in each are quite different;
so comparing the two is a bit like comparing apples to oranges.
The OSCP covers a broad range of topics including web application
testing, but it does not go deep on web application testing.
The BSCP only covers web application testing, and it goes very deep
on it.


### Comparison to OSWE

The OSWE and BSCP test a very similar set of skills, and the OSWE
is quite a bit harder than the BSCP. For the BSCP, you have an
extremely powerful tool (Burp Suite Professional) at your disposal
for finding vulnerabilities; whereas, for the OSWE, all vulnerabilites
must be found manually. The course content for the BSCP is much
better than the OSWE, and so I wish I had taken the BSCP before I
had taken the OSWE.


