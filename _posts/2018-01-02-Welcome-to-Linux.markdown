---
layout: post
title:  "Linux commands"
date:   2018-01-02 16:37:20 +0700
categories: Linux
---
This post is about Linux commands

<h3>ls</h3> List all files in current folder
<h3>ls  [options]  [folder]</h3> List all files in [folder] with some [options]
{% highlight ruby %}
ls -laht /usr/local ## List all files in '/usr/local'with more details
{% endhighlight %}
<h3>cd [path]</h3> Change current working directory to [path]
{% highlight ruby %}
~/Music$ cd iTunes/ ## go to folder iTunes start from Music folder 
cd /usr/local/lib/ ## go to lib folder start from very first folder of Linux
{% endhighlight %}
<h3>cd </h3> Back to root folder of current folder
{% highlight ruby %}
~/Music/iTunes$ cd ## Back to user's folder
{% endhighlight %}
<h3>rm [file]</h3> Detele [file]
{% highlight ruby %}
rm file.txt ## delete file.txt
{% endhighlight %}
<h3>rm [file] [folder's path]</h3> Move [file] to [folder]
{% highlight ruby %}
mv text.txt remove ## move file text.txt to folder remove
{% endhighlight %}
<h3>rm [filename1] [filename2]</h3> Change name of [filename1] to [filename2]
{% highlight ruby %}
mv text.txt text2.txt ## Change name text.txt to text2.txt
{% endhighlight %}
<h3>chmod [options] [file] </h3> Change file's permission
![chmod](/chmod.png)
{% highlight ruby %}
chmod 755 text.txt  
{% endhighlight %}
<h3>df </h3> Show disk usage
<h3>chown [option] [user]:[group] [file/folder] </h3> Change file owner and group
{% highlight ruby %}
chown -R root:admin Ruby
## set owner user root, group admin for folder Ruby and all it's children files   
{% endhighlight %}


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
