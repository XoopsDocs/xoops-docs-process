# XOOPS Docs Starter-Kit

In order to simplify the process of creating XOOPS Documentation, we have provided a Starter-Kit, containing at this moment:
- starter-kit for a XOOPS Tutorial
- starter-kit for a generic book (based on work of  [MrMaximize](https://github.com/MrMaksimize/gitbook-starter-kit))
 
You can download or fork the XOOPS Docs Starting-Kit from [GitHub XOOPS Docs](https://github.com/XoopsDocs/gitbook-starterkit)


1) if you have forked the XOOPS Docs Starter Kit, please:

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

