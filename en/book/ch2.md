# Process requirements

The process of creation XOOPS Documentation using GitBook and GitHub requires:

- Account on **GitHub** (http://www.github.com)
    - basic knowledge of using GitHub Website
    - basic understanding of using Git as Versioning system
    - basic knowledge of **Markdown** 
- Account on **GitBook** (http://www.gitbook.com)
    -   to learn more about GitBook, please read this

#### 1) Creating a GitHub Repository 


There are two ways to contribute to XOOPS Documentation:

**a) Fork an existing book/tutorial**

To do so, go to an existing tutorial on **[GitHub XOOPS Docs](https://github.com/XoopsDocs)**, and fork it by clicking on the Fork Button: ([screenshot](http://mrm-screen.s3.amazonaws.com/MrMaksimizegitbookstarterkit_20140707_085000_20140707_085006.png))
* Rename the repo to what you want your book to be called:
  * Click settings from the home screen of the forked repo (forking creates a copy of the repository under your username). ([screenshot](http://mrm-screen.s3.amazonaws.com/MrMaksimizegitbookstarterkit_20140707_100321_20140707_100325.png))
  * Rename the repo ([screenshot](http://mrm-screen.s3.amazonaws.com/Options_20140707_100417_20140707_100421.png))
* Clone the repo to your machine.  Remember our assumptions.  I will walk through how I would do it:
  * Find the URL of the new forked repo. ([screenshot](http://mrm-screen.s3.amazonaws.com/MrMaksimizegitbookstarterkit_20140707_085400_20140707_085418.png))
  * Open terminal back up and execute the following:
  * `git clone YOUR_REPO_URL ~/Code/BookName`
  * `cd ~/Code/BookName`
  * `gitbook serve`
  * The last command will start a local server at port 4000 which you can access at http://localhost:4000;  It will automatically refresh on changes.  Now you're ready to start writing!

**b) Creating a new book/tutorial from scratch**




