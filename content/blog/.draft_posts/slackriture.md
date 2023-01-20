---
title: "Creating automated literature searches within Slack : A primer to Bash tools, APIs and Webhooks"
date: 2020-09-10T00:45:28+11:00
---

Keeping up-to-date with literature in research is really important. Since research is by its nature bleeding edge, being informed and constantly innundated at the very frontier is necessary for any budding researcher. 

However, what are the kinds of solutions that are there for our needs? Well there is Google Scholar. But it sends updates on your specific search queries to your emails. Where it can get lost within updates.

![]()


I, for one, had unique requirements. I like keeping my feeds separate and I spend most of my time on Slack and wasn't particularly happy with looking into my email (as I use email more of a formal communication tool). On the other hand, I have been always very intrigued by the Unix philosophy of "modularity" and creating "microservices" that do one thing and full its specific purpose very well. 


Now, with this there are many things 

> Disclaimer : This is a guide explaining how to create a bot using commandline tools. It is geared towards users who have little experience with the command line. However, it is meant to be moreso a primer on the various concepts of modularity and using different tools to solve problems and the approach can be extended to other tools. So it may not be apt towards those who are more well-versed with the commandline.

# The Anatomy of a Literature Search Query

A search query is defined as follows : 

> A systematic 

# Introducing the PUBMED API 

The PubMeD

# What are Webhooks 

# Cron Jobs and how they work 

# The Script 

Curl is a Unix commandline tool that helps us send and recieve API get requests. Think of it as a text-based way to interact with webservers, a command line browser (if you will, but its so much more).

```{bash}
#!/bin/bash
curl -wx

```

# Tying it all together 

# Learning More, Links and Resources 

Anyone who has used posted on Linux forums will tell you that it is important to RTFM (look).

Since many of the tools I've discussed here are very well documented, you might find it wise to have a look at  `man`.

`man` is a generic Unix command to find the manual. So type in `man cron` or `man curl` to find out more about the specific command used and the various *options* or *command-line arguments* that can be passed on. 


1. Link to the github with the `slackriture.sh`
2. Learning more about Webhooks. 
