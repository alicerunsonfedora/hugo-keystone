# Keystone Career Profile Template

## About this project
When I started working on my career profile for Consumer Economics, I wanted to create a static site with Hugo that allows me to post my content as needed.

This is a template that anyone can use to build their own projects.

## Instructions
### Pre-requisites

* A way of publishing your static site (I personally use Heroku with the Hugo buildpack)
* Hugo binary (if you plan to test your site locally)
* A capable text editor ([Atom](http://atom.io) is a good example)
* Basic terminal skills
* A GitHub account (for publishing source code and automating the process)


> Note: This tutorial will assume you are setting up your keystone project site with Heroku.


### Setting up Heroku
1. Register for a Heroku account if you haven't already.
2. Create a new app and name it whatever you like.
3. In the app's *Settings* tab, click 'Add buildpack' and copy the following line into the text box: `https://github.com/roperzh/heroku-buildpack-hugo.git`.

### Installing this Template
1. Register for a GitHub account if you haven't already.
2. On this template's source code page, hit the "Fork" button to fork the repository into your account.

### Editing your Settings
1. In the *Deploy* tab of your Heroku app, click "Connect to GitHub" under the Deployment method section.
2. Verify and allow Heroku to access your repositories.
3. When returning to Heroku, type in the repository name. It should appear in the list.
4. Follow any missing steps to complete the process.

## Template Modifications
### `config.toml`
This file is responsible for all of the primary settings used. These are the following values you should change:

```toml
baseurl = "https://example.org/"
# Replace this with "http://(name-of-your-project).herokuapp.com"
title = "Keystone Template"
# Replace this with your site title
```

> Note: the following sections requires a basic understanding of the Markdown language. [Click here for a cheat sheet &rsaquo;](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)


### Making *posts* and *pages*
You can take a copy of one of the posts and edit it to match your needs. The same way works for pages. Whenever you make a change to the file in the online GitHub editor or push a commit to your repository, your website will *automatically* build and should respond within a few minutes.

### Using existing content
#### Cover Letter and Resume
This file is located under `content/page/about.md` and is used for your cover letter. Your resume is located similarly: `content/page/resume.md`.This is what you want your employers to see!

#### Keystone blog
All posts in the `content/post` folder are attributed to your **keystone blog**. This may include vision boards, thoughts about your future, and much more. This is not necessary for your professional profile, but it offers some insight.

##### Career Outlook paper
If you are writing a research paper concerning your outlook of your career of choice, this is one of the posts in your keystone blog. This file is located under `content/post/career-outlook.md`. You can use the following template areas to guide your post.

### Hosting images
Images should be placed in the `static/_images` folder and should be referenced with the URL: `[Name of URL](/_images/nameoffile.ext)`.

## Help and Information
When in doubt, you should always check the Hugo documentation, found at http://gohugo.io/documentation/. This site contains information regarding how to do some things that you may want to do. If you need further assistance, you can alway email me at [software@marquiskurt.net](mailto:software@marquiskurt.net) or file an issue on GitHub with the tag 'question'.
