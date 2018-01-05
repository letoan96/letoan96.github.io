---
layout: post
title:  "Git commands"
date:   2018-01-05 13:37:20 +0700
categories: Git
---
This post is about Git commands
<h3>git add .</h3> Add all files from current directory into index
<h3>git status</h3> Show status in the workspace and index
<h3>git commit -m "commit message"</h3> Commit all files in the index into local responsitory
{% highlight ruby %}
git -m "first commit"
{% endhighlight %}
<h3>git clone [responsitory link] </h3> Clone a repository into a newly created local directory 
{% highlight ruby %}
git clone https://github.com/letoan96/letoan96.github.io.git
{% endhighlight %}
<h3>git push</h3> Push local reponsitory to remote reponsitory
{% highlight ruby %}
git push
{% endhighlight %}
<h3>git remote add [remote-name] [url]</h3> Set a new remote
{% highlight ruby %}
git remote add origin https://github.com/letoan96/letoan96.github.io.git
{% endhighlight %}
<h3>git pull [remote] [branch]</h3> incorporate changes from a remote repository into the current branch
{% highlight ruby %}
git pull origin master
{% endhighlight %}


![image tooltip here](/Git_command_cheatography.png)
![image tooltip here](/Git_command_cheatography_2.png)



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
