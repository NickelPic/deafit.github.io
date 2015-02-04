# DeafIT Website

This website is powered by Jekyll. See on Jekyll website for more information how Jekyll works. 
Github supports Jekyll hosting for free so we host our website on github. 

Here you will be explained how the website is structuered and about where you can start.
Let's talk about the directory structure and files, first.


## Directory structure and files

 - `_includes`: Collection of all partials that are included in the templates.
 - `_layouts`: Some layouts you can pickup for your page.
 - `_posts`: Collection of posts whose filename is concencated from date_title.md (YYYY-MM-DD-title.md)
 - `blog`: Here you find the layout template for our blog.
 - `public`: Collection of assets like JavaScript, CSS, images files.
 - `team`: Here you find pages for our team page.

 - `_config.yml`: It's the main configuration file for this webpage. 
 - `atom.xml`: Our XML feed
 - `*.md`: All pages whose filename ends with .md are the pages that you can modify. 


## How the page is built

The primary file format is choosen as Markdown. It's templating language for writing content. 
It's quite readable. The documentation you can find about Markdown, just go to http://xxxx. 

Let's talk about an example:

	---
	layout: default
	title: Home
	---

	![DeafIT Teaser](http://placehold.it/800x400)

	## Herzlich willkommen ...

	... auf unserer Webseite der Deaf IT Conference! Deaf IT Conference richtet sich an alle deutschsprachigen Gehörlosen, Schwerhörigen und CI-Träger, aber auch Hörende, die in der Informations- & Technologie Branche arbeiten und arbeiten möchten. Es 

The first four lines you can setup the layout and the title of the page. Then you can bring the content on the page with Markdown syntax. It's simple to understand. "##" marks the line as headline with "h2". The "#" is the "h1" and so. Each line is a paragraph, so you don't have to take care of formatting paragraphs. Markdown converts that automatically for you.


## Deployment of changes

So, we host our website on github. It's using git as version control system. As team member, you can use github directly to modify or add the pages without having to take care of repository management. For larger changes you can fork the project and send pull request so the team member can review your changes and accept the pull request in order to merge your changes into master branch. Every change on the master branch is deployed automatically to production. 
