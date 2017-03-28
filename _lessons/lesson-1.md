---
title:  "Using version control and static site building to turn in your homework"
description: "Use Git (version control software) and Jekyll (a static site building platform) to publish to Github Pages (a hosting platform)."
class_date:   2017-04-03
image: lessons/software-freedom.jpg
image_credit: Jonathan Gibby
hide_image: true
---

# Overview

*Tools:* Git, Jekyll, Github.

*Concepts:* Version control, static site building, markup languages.

*Philosophy:* Reproducibility, sustainable development.

# Assignment

Read [How to murder media in 2017](https://medium.com/splicenewsroom/how-to-murder-media-in-2017-93fd933b15e5#.79xsgtqm6).

Complete the "Hello world" [Github tutorial](https://guides.github.com/activities/hello-world/).

Watch or read:

* [Why use a static site generator](http://jekyll.tips/jekyll-casts/why-use-a-static-site-generator/)
* [Blogging in Jekyll](http://jekyll.tips/jekyll-casts/blogging/) (note that instead of a text editor, you'll use Github directly)

Fork the class repository, add a post to your copy of the repo, and use it to write your first digital journalism critique.

For your critique:

* Screenshot the piece in question and make sure it is referenced in your post's front matter.
* Link to the piece in question in your post.
* Write at least 3 paragraphs.

# Lesson

There's a tendency to start a class about data and digital journalism with definitions of the field and big philosophical ideas. I prefer a more direct approach.

For your first lesson, you're going to learn how to turn in your homework.

It turns out that to turn in your homework, you're going to need to learn a little bit about version control, markup languages, text editors, and static site building. This exercise is going to be frustratingly incomplete -- I'll wave my hands at a bunch of crucial concepts and you'll probably be confused by many of the steps. That's the nature of learning this stuff. The key thing is that you're going to edit a file on your computer and that file is going to become part of a published website.

In this class, we'll get at the philosophical ideas by doing hands-on work. And we'll skip the grand definitions of what data journalism is or isn't altogether. I'm going to show you some things I know about data journalism and try my best to situate them within the broader ecosystem. I don't care if you leave this course knowing any better what data journalism is or isn't, but I do care that you leave this class knowing better how you are going to use data and design to deepen and strengthen whatever kind of journalism you aspire to do.

## How to turn in your homework: The 10,000 foot view

The full workflow for turning in your homework consists of setting up your computer with the tools needed to publish (which you'll need to do once/infrequently) and adding posts to your personal blog and contributing them back to the class blog (which you'll do every week).

Initial setup:

1. Get the Github app and Atom text editor
1. Fork the class blog repository so that you can work in parallel with all the other students
1. Clone your fork of the class blog repository so you can edit files on your computer

Turning in your homework:

1. Create or edit your post. Most assignments are expected to be submitted as blog posts.
1. Write a description of the changes you made and "commit" your work to the log of changes.
1. "Push" your changes to your fork of the class repository so that they will publish on your personal blog.
1. Create a "pull request" that will allow me to review your homework submission so that it will be published on the team blog.

## Install requirements

### Download Atom

Atom is a text editor. You'll need a text editor for writing structured text, code, and other basic data journalism tasks.

[Download Atom for Windows or Mac at https://atom.io/](https://atom.io/).

If you end up writing a lot of code, you'll want to get to know your text editor very well. If not, take my word for it -- Atom is pretty nice and should let you handle basic text editing tasks just fine.

### Get a Github account

Github is a platform for sharing and coordinating code, data, and content. It helps people track changes to code, tasks, and even can publish websites.

[Sign up for Github at https://github.com/join](https://github.com/join).

### Download Github Desktop

Github Desktop is a Mac and Windows app that provides the Git version control system, integrated with the Github code hosting platform.

[Download Github Desktop for Windows or Mac at https://desktop.github.com/](https://desktop.github.com/).

## Hello version control

Git and Github are foundational technologies for data journalism. I know people who strongly disagree with teaching Git and Github in an introductory class, much less in the first lesson. The critics are right that Git is confusing as hell, and for as magic as it is, Github just makes things even more confusing.

Unfortunately for all of us, you still need to learn it. This part of the process is just gonna hurt a little. That's why we're going to skip a lot of concepts in favor of getting you using it for just a few basic publishing tasks over and over. Happily, the Github Desktop app is more accessible and forgiving than other ways of using Git and Github and will let you get started quickly so that you can start building up your version control skills and mental model.

Why is version control so important? Because being able to share and reproduce your work is crucial to developing as a data journalist.

Version control is everywhere. If you've ever saved multiple versions of a file, used the Google Docs "history" feature, or Microsoft Word's "track changes", you've used some kind of version control.

Git is version control software. It lets you track changes in useful, sophisticated ways. But it's a pretty low-level tool with a learning curve like a steep cliff.

That's where Github and the Github Desktop app comes in. Github is a website that wraps a bunch of handy Git features in a nice user experience. The Github Desktop app makes it easier to synchronize work you do on your local computer with the Github site. Not only that, Github can publish pages for us.

Let's start by creating your own copy of the class repository so that you can make changes to the site and submit them back to the main class site. Creating your own, parallel line of work in Github is known as "forking".

### Fork the class repository

Visit https://github.com/digitalframeworks-spring2017/digitalframeworks-spring2017.github.io in your browser. You should be logged in to Github, or at least have an account.

Now, click the "fork" button in the upper-left corner of the screen below the black toolbar. You may have to pick an account to fork to if you belong to multiple Github organizations. Otherwise, the process will just begin.

When the forking process is done, you'll be dropped onto a page with a URL like https://github.com/eads/digitalframeworks-spring2017.github.io.

If you take a look at the URL structure, you'll see the name of the repository (the last part of the URL) remains the same, but the name of the user/organization (`digitalframeworks-spring2017` and `eads`) varies. The `<yourusername>` version is your copy of the repository. You can experiment with you copy, goof around, and learn without screwing up the main line of development.

### Clone your fork of the repository

Now, open the Github Desktop application and add _your_ version of the class repository.

TKTK

## Hello static site building

We haven't talked much about what's _in_ the class repository. The class repository consists of Jekyll source code. You're going to learn a fair amount about basic Jekyll usage in this class, but for now the important thing to understand is that a Jekyll site is a bunch of files that get stitched into a published website. Web

### Copy and edit a post

TKTK

### Commit and synchronize your changes

TKTK

### Enable website hosting

TKTK

### Create a pull request

TKTK

##
