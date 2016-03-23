#WebKick
##Introduction

!! This Repo is no longer maintained.

This project used to be my empty projecttemplate for new templates.
With further enhancement, Webkick becomes the following.

WebKick is a lightweight Template/Directory scheme to kickstart your HTML/CSS/JS Templates which you can use for any CMS or Application.
Equipped with a lightweight modernizr alternative, it is suited for small and big projects of any kind.

Like any other project - it includes a lot of other open source to accelerate development.
This is not just another boilerplate, it is much more a way to organize your stuff with the benefits of easy and fun workflow.
WebKick contains a Toolset of scripts which can make work a lot more easy.

###Based on the SMACSS principles

The folder structure and the code is based on the SMACSS principles for organizing CSS.
WebKick adds another bunch of standards to organize templates. This template of a template works best with TYPO3. But you can however, use it for any other basic templating engine or just build upon this work.

###Uniting Best Practices

Getting to know webdevelopment and/or design together with HTML and CSS is hard work. Getting it right together with applying coding guidelines and standards is another pair of shoes. Seperating content from structure is the first step into a reasonable environment which you can extend and build upon.
Another hint: there is no minified version yet.
I am using the ISO C Standard for line indentation and bracket placing.

##Framework

###Grouping

Live example: http://codepen.io/MartinMuzatko/pen/bgpnc

Evenly divided elements can be achieved really quick!
you just have to give the parentelement the class `group` and it will divide all subelements.
The markup is independent, you just need to assign one class only.

```html
<ul class="group">
	<li>item 1</li>
	<li>item 2</li>
	<li>item 3</li>
	<li>item 4</li>
	<li>item 5</li>
</ul>
```


####Work in progress

If you do not like evenly sized columns, especially for layout, you can assign 1-4 (one forth) for the first column.
I currently work on syntax and usage. But I guess everything will be controllable my one class.

yet just a concept.

```html
<section class="group-1-4">
	<div>25% Lorem ipsum dolor sit.</div>
	<div>75% Lorem ipsum dolor sit.</div>
</section>
```

##Appendix

###Vendor Scripts and Stylesheets

Prefixfree - Lea Verou - https://github.com/LeaVerou

Livereload - https://livereload.com

Reset - Eric Meyer - http://meyerweb.com/eric/tools/css/reset/

###Browser Testing Results

The Framework works with every modern browser. However, IE8 does not support the CSS3 autoframework.
