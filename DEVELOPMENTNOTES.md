kgserrano.com / block-- Development Notes
==================================

Introduction
------------
This is where I'll be documenting most of the early development process until I can get a blog system up and running. Here I'll reference all of the features, bugs, annoyances, links, and tools I'll have used to develop each part of the website.


General Development Tools / References
------

### Design

* __Brackets__: [http://brackets.io/](http://brackets.io/)

The main IDE I use to develop the HTML and CSS. The Live Preview feature allows instant feedback on changes I make to the HTML/CSS.

* __Adobe Color__: [https://color.adobe.com/](https://color.adobe.com/)

I use this as a starting point for the color scheme to use in the website.

* __0 to 255__: [http://www.0to255.com/](http://www.0to255.com/)

This is helpful for finding colors similar to a primary color I'm focusing on.

* __Adobe Photoshop CC__: [http://www.adobe.com/products/photoshop.html](http://www.adobe.com/products/photoshop.html)

Although I only use this out of availability and experience, it's a great product to use for most design tasks. I recommend a free program like GIMP though if you're on a budget or don't have access to CC.

### Favicons
* __Favicon Cheat Sheet__: [https://github.com/audreyr/favicon-cheat-sheet](https://github.com/audreyr/favicon-cheat-sheet)

Details of the specifications for all the favicon formats you'll need.

* __treehouse: How to Make a Favicon__: [http://blog.teamtreehouse.com/how-to-make-a-favicon](http://blog.teamtreehouse.com/how-to-make-a-favicon)

An article related to the design and production of favicons.

### Logistics

* __Dreamhost__: [https://www.dreamhost.com/](https://www.dreamhost.com/)

This is where I host my website. Personally, I use a VPS. I also have some domains held here.

* __101domain__: [https://www.101domain.com/](https://www.101domain.com/)

Another domain marketplace I use for non-standard top-level domain names (such as .moe).

* __Daring Fireball: Markdown Basics__: [https://daringfireball.net/projects/markdown/basics](https://daringfireball.net/projects/markdown/basics)

This was my starting point for learning Markdown, a useful markup language that quickly converts into HTML. This document is written in Markdown as well as the README.

* __Git__: [https://git-scm.com/](https://git-scm.com/)

This is the version control software I use to keep track of the changes in my code.

* __GitHub__: [https://github.com/](https://github.com/)

The web-based repository I use with Git. This is where you're seeing the repository right now!

* __PuTTY__: [http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)

A remote terminal program for Windows. This allows me to SSH into my server and perform console commands there. I also use Pageant and PuTTYgen to allow for passwordless logins.

* __WinSCP__: [https://winscp.net/eng/docs/introduction](https://winscp.net/eng/docs/introduction)

An FTP/SFTP client that allows file transfer between my computer and the website's server. Useful for when I want to bypass the github repo.

* __envatotuts+__: The Perfect Workflow, with Git, Github, and SSH: [http://code.tutsplus.com/tutorials/the-perfect-workflow-with-git-github-and-ssh--net-19564](http://code.tutsplus.com/tutorials/the-perfect-workflow-with-git-github-and-ssh--net-19564)

A very useful tutorial for automating your server to pull from the GitHub repository after you push. Reduces the need to manually pull via SSH.

Issues
-------

### Photoshop
* Be careful when trying to upscale or downscale your favicons in Photoshop. There is a bug in Photoshop CC that does not allow you to properly change the interpolation settings during image resizes. Instead, you have to go to your preferences and change the interpolation settings in the General tab inside. 

Source: [http://feedback.photoshop.com/photoshop_family/topics/photoshop_cc_2014_nearest_neighbour_no_longer_works_properly](http://feedback.photoshop.com/photoshop_family/topics/photoshop_cc_2014_nearest_neighbour_no_longer_works_properly)



