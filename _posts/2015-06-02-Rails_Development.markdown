---
layout: post
title:  "Rails Development"
date:   2015-06-02 12:24:46
categories: jekyll update
---
<h1>Development of first blog using ruby on rails</h1>
<br>
<p1>Scaffolding provides a basic framework</p1>
<br>
<p2>Without scaffolding development:
Resource is used to club together entities with similar properties.You can create, read, update and destroy items for a resource and these operations are referred to as CRUD operations.</p2>
<br>
<p3>Use of pry for debugging: include pry in the file:
	require 'pry' and then binding.pry is used in the code
</p3>
<br>
<p4>Different environments of development:
Development, Testing, Production</p4>
<br>
<p5>Write specs for routes, model, controller for now</p5>
<br>
<p6>Sequence of functions matters in rails</p6> <br>
<p7>link_to usage: link_to is basically a built-in helper in rails which is used in html files to link to other pages in view.
Usage: link_to('whatever you want to display in the link',{:controller => 'corresponding controller name',:action => 'corresponding action name'})
</p7>
<a href ="http://stackoverflow.com/questions/6882207/how-link-to-mechanism-works-in-ruby-on-rails">Reference for link_to</a>
<br>
<p8>In development mode (which is what you're working in by default), Rails reloads your application with every browser request, so there's no need to stop and restart the web server when a change is made.Active Record supplies a great deal of functionality to your Rails models for free, including basic database CRUD (Create, Read, Update, Destroy) operations, data validation, as well as sophisticated search support and the ability to relate multiple models to one another.</p8>

<p9>HTTP requests are made on the model</p9>
<p10>Use of rails c can be done to deal with model.You do not define functionalities inside the test rather you just check the tests by creating objects and testing the functionalities.</p10>