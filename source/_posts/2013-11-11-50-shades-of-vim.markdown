---
layout: post
title: "50 shades of vim"
date: 2013-11-11 22:03
comments: true
categories: vim, linux
---
As part of my ongoing "tool sharpening" I've been trying to figure out once and for all how terminal vim colorschemes work, and why they seem to always look different on different computers and terminals.

I switched briefly over to GVim, simply as the colorschemes seemed to "do what they said on the tin" and resemble what I'd see on the website promoting them. After some research, I realise terminal vim is less well behaved as it is limited to 256 colours. Not only that, but some terminals only support 16 colours, and applications also interagate environment variables such as $TERM to decide what colours they will use.

Also, terminals have there own colour pallettes; and therefore there own opinion what light green and dark green look like, which vim colorschemes simply build on top of. So the wrong terminal scheme can ruin the best of vim schemes. It's terribly confusing...

So I started with the [Base16 project](https://github.com/chriskempson/base16), a set of color pallettes to configure the terminal, shell and vim so that they all live in harmony. Picking the railscasts theme, I ran the install scripts for my Gnome terminal, setting the default terminal profile to be the newly generated base-16-railscasts-dark theme. Then I pulled down a copy of the base16-shell project, and added the recommended lines to ~/.zshrc to ensure each shell used the same base-16-railscasts-dark shell theme. Finally, a couple of lines into my ~/.vimrc file added the colorschemes (using vundle, in my case) and then set my default colorscheme to base16-railscasts

There were a couple more steps required. 
