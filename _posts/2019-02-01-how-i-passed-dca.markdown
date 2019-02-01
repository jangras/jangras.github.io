---
layout: post
title:  "how I passed Docker Certified Associate exam"
date:   2019-02-01 15:42:55 +0530
categories: jekyll update
---

I have passed `Docker Certified Associate` (DCA) exam on 31st December 2018. I am happy to share my experience of Docker Certified Associate exam & how to study for the exam. Before going further let me quickly introduce myself. I am having 12+ years of experience in IT infrastructure services which includes Linux, Unix, VMware, Servers, Storage, Networking & Security, AWS & Openstack. I have been playing with Docker since an year but occasionally. So, lets start with -> how I prepared for the exam:

u started with Docker Deep Dive by Nigel Poulton. It took me about one week to complete the 400+ pages of this book with all included practicals in parallel. This book is just awesome. Nigel has done a great job, kudos to him. So, I suggest you to go through this book. Additionally, you can refer to his video course on pluralsight.com, but I haven't taken video course.
 
After that, I spent 4-5 days on reading the official documentation. I recommend everyone to go through the official documentation at least once --> [github devops academy] [github devops academy] .But here is one issue, there are lots of links & you may get frustrated referring them. I am making it easy for you, i have printed all links in PDFs and attaching below. They may have some duplicate topics, but you can skip them easily. I used kindle app to read all the PDFs. Kindle app made it easy for me to bookmark & highlight the points to revise on the day of exam. 

Also, I practiced on Docker CE & EE, created UCP cluster with DTR, performed backup & restore. Don't worry, Nigel has made it very easy to perform practicals by referring his book. I took the benefit of free trail of Google Cloud in order to spin up few compute instances for creating cluster. Used the free SSL certificate from Let's Encrypt but that's optional, self signed certificates are also good to go.

Finally, I revised all the stuff, specially Nigel's book, & scored >85% in the exam. I must say exam includes enough tricky questions, Docker seems serious about having 6 months of experience before going for the exam. You must practice around swarm, storage, network, service create/update, dockerfile options, namespaces & cgroups. Otherwise, you may confuse while choosing the best answer. 

Links to PDFs :

1. Orchestration - 25% of Exam
2. Image Creation, Management, and Registry - 20% of Exam
3. Installation & Configration - 15% of Exam
4. Networking - 15% of Exam
5. Security - 15% of Exam
6. Storage and Volumes - 10% of exam


[github devops academy]: https://github.com/DevOps-Academy-Org/dca-prep-guide
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
