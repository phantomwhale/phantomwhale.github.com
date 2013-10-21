---
layout: post
title: "Simple Server Setup with anSible"
date: 2013-10-21 16:49
comments: true
categories: Ansible
---
So the first topic I intend to write a few posts on is on [Ansible](http://www.ansibleworks.com/docs/ "Ansible"), a system configuration and provisioning tool.

I first was introduced to Ansible at Railscamp 13 (Melbourne, Jun 2013) as a lightweight server provisioning tool. Before then, I had presumed Chef and Puppet were the only players in this space worth watching, but for our small, single-server based deployment stack, using such tools always felt quite heavy.

Up until this point we have mainly stuck with shell scripts and a little manual hackery we documented on a wiki. Of course, documentation is a lie waiting for happen, to paraphrase the [Ruby Rogues](http://rubyrogues.com/079-rr-documenting-code/).

So upcoming I'm hoping to post on how we're using Ansible to create our new server, how I've also been using it on my local machines to get a repeatable development environment installed and there is also a presentation I am working on to introduce the topic to a wider audience.

I'll end this post with a link to an e-book by [Matt Jaynes](http://mattjaynes.com/) that I found quite helpful when trying to understand how Ansible fits into the server provisioning "space" in general. It's called [Taste Test](http://devopsu.com/books/taste-test-puppet-chef-salt-stack-ansible.html) and covers using Puppet, Chef, Salt and, of course, Ansible to configure a simple server setup.
