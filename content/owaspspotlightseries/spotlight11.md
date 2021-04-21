---
title: "OWASP Spotlight - Project 11 - Nettacker"
date: 2021-01-15
draft: false
video: https://www.youtube.com/embed/OGv7OtG127A
---


This project is an automated penetration testing tool, but it can be used for all sorts of interesting things because it is modular and basically it's written in Python, and it allows you to do three different things. So it allows us to Perform scans Of the network. Originally it was created as an IoT scanner to scan IoT devices. So you can scan the network, it can discover your service your hosts, it can scan for open ports and it doesn't really quickly. And it's written in Python. So

1. We can attack your own networks, but you can also attack.
2. We can use it as a penetration testing tool or for example as a bug bounty
3. It also performs brute forcing so you can use it to, for example, scan your network and perform brute forcing and find all the hosts and service which have, for example, default credentials like admin admin or you can download password listen and run

It allows us to scan hundreds or maybe thousands of service all sub domains or your network and you can check for one thing, or you can check for many things. It comes as a command line tool and as a web UI as well. And we can also launch it in Docker. That's where it's pretty cool. It can work on Windows. Windows, Linux or Mac OS.

The tool gathers all that information and puts all the reports that it compiles into a one simple table one simple spreadsheet and you can output that data into a CSV file and use it in Excel or we can output it into a JSON file. And then you can consume that JSON file and pass it on, and integrate with other tools if you want. I think this is one of the greatest advantages because these days.

Organizations have a problem that they need to scan the networks from inside and from outside. So they have to go out and buy quite expensive commercial vendor solutions and not many companies, especially smaller companies are able to afford this tools. So say this is an open source and free tool and it actually solves this task. It basically will let People to go and scan their network from inside from outside, find out everything they have legacy. This is the table that they talked about and you can output this into an Excel spreadsheet Or into a JSON file and see if you're a large organization, you will see like thousands and thousands of entries in there, but it will it will show you exactly which hosts that you have are vulnerable

About the project : https://owasp.org/www-project-nettacker/​

Github : https://github.com/OWASP/Nettacker