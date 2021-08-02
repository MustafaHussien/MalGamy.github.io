---
title: Anti-debugging and anti-tracing techniques part3
classes: wide
header:
  teaser: /img/h1.png
ribbon: MidnightBlue
categories:
  - Revese Enginnering 
toc: true
---

# Introduction


# Examine Emotet with DIE
I will open malware with Detect It Easy tool to see some information about Emotet malware like compiler,type of packer if malware author use commercial packer to pack malware with it and type of linker and more information, so we can see the results in the next figure.

![figure01](https://user-images.githubusercontent.com/74544712/127772190-8b6f3a3d-963a-4f58-a486-ce2ac796b4f7.PNG)

From the previous figure 1, we can identify some information about Emotet malware like as compiler and linker and the time that malware has been compiled on it and malware author can fake the time and the number of the sections that find in malware. Now I will examine the entropy to see if malware is packed or not and entropy is a good indicator that use by malware analysts to detect packed and some other techniques and we can see the results in the next figure.

![figure02](https://user-images.githubusercontent.com/74544712/127772891-12dd2423-1e7f-4874-8758-b8c8c60d5de2.PNG)

From the previous figure we can see the four sections and packed section which called rdata and see the 7.15835 number which give us good indicator that Emotet malware is packed