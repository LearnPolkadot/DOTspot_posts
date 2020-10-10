![](https://www.dotspot.io/assets/images/dotspot_learnlogo3.png)

DOTspot is community driven project that aims to give an open place for ecosystem projects to share their latest news. Contributions are from the ecosystem and for the community,

**<a href="https://www.dotspot.io" target="_blank">DOTspot** (dotspot.io)</a>

---

- <a href="https://www.dotspot.io/projects/" target="_blank">Projects Building in the Ecosystem</a>

- <a href="https://www.dotspot.io/web3grants/" target="_blank">Web3 Foundation Grant Receipts</a>

- <a href="https://share.hsforms.com/1LtBuOi1bSs-p8XGXC_hoyw4752a" target="_blank">Sign up to join the Ambassador Program</a>

---

👷 **Contributing**

Project updates, articles, or other contributions come from the community. Not only can projects post about their latest updates but Polkadot community members, apprentices, and ambassadors are welcome to write updates about the lastest trends in the space. 

### Project listing information:

- <a href="https://www.dotspot.io/listing/submit/" target="_blank">Submit a Project</a>
- <a href="https://www.dotspot.io/listing/update/" target="_blank">Update a Project</a>
- <a href="https://www.dotspot.io/listing/remove/" target="_blank">Remove a Project</a>

### Publish a Article 

_Note: You will need a GitHub account to contribute to posts(articles/news). If you do not have a GitHub account, you may <a href="https://github.com/join" target="_blank">sign up for one for free</a>._

_It is helpful to open links mentioned below in a New Window so you can have these instrutions handy (CTRL+click on Windows and Linux or CMD+click on MacOS)_

1. Sign in to your GitHub account

2. Browse to the folder where you want your article to appear.  *Example*:

   - if writing about a project select the <a href="https://github.com/LearnPolkadot/DOTspot_posts/blob/master/projects" target="_blank">project folder</a> then the appropriate project
   - if writing a general article about Polkadot, Kusama, or Substrate select the <a href="https://github.com/LearnPolkadot/DOTspot_posts/blob/master/general" target="_blank">general folder</a>

3. Select Add file > Create new file

   - this will FORK the repo to your current github account

4. Name your file in the following format *FORMAT IS IMPORTANT*

   - YYYY-MM-DD-articletitle.md

     **replace articletitle with the name of your article with NO spaces*

5. Paste the following code below in the Edit new file window

```
---
title: "This is a title"
# ^^^Enter the TITLE for your POST 
date: 2020-10-09
# ^^^Enter the CREATED DATE of your POST YYYY-MM-DD do NOT change this if your updating a article.  Please update the last modified date below.
last_modified_at: 2020-10-09
# ^^^Enter the UPDATED DATE of your POST YYYY-MM-DD if new article this will be the same as created date 
author: DOT spot
# ^^^Enter the AUTHOR of your POST this is what will be displayed as the author 
#
# DO NOT BELOW THIS LINE
proj: 
  - 1
categories:
  - applications
tags:
  - kusama
sidebar:
  nav: "posts"
# DO NOT CHANGE ABOVE THIS LINE
---
```

6. Edit the following FOUR lines in the code you just pasted.  Adjust the values to fit your article.  *Example*:
   - title: "Polkadot is run on DOTs" <br />
     **leave the title wrapped in quotes*
     
   - date: 2020-11-23 <br />
     **no quotes - publish date of the article YYYY-MM-DD*
     
   - last_modified_at: 2020-11-23 <br />
     **no quotes - this will be the same as date if your creating a article*

   - author: DOT spot <br />
     **no quotes*

7. Now your ready to write your article starting anywhere after line 21---.  

   - Articles use the markdown language format. 
   - A markdown language cheat sheet can be [found here](https://www.markdownguide.org/cheat-sheet/).  
   - If your have a favorite [Markdown file editor](https://typora.io/) you can create your article and past the code after line 21 ---
8. Once you are ready to submit your article we will PULL the article back to the main Learn Polkadot Posts repo. 
   - Scroll to the bottom of the GitHub page your creating your new file and click Propose new file
   - Feel free to add any description you see fit... ie: article is being crated in the Acala folder but should show up under Acala, Bitfrost, and Chainlink
9. Click - Create pull request
   - This will take you to a Open a pull request page. 
   - Leave Allow edits by maintainers checked
   - Click - Create pull request again to submit your article
10. That's it! You have just submitted your article for listing on the DOTspot and upon review will recieve a email when your article has been Approved.  Articles are reviewed and once approved you will receive a GitHub notification that your articles has been merged to the master branch and will be displayed on the site.
