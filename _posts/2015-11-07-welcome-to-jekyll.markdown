---
layout: post
title:  "Welcome to Jekyll!"
date:   2015-11-07 04:58:46
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help



•What do you think of pre-compiling your CSS?
◦Compare to regular CSS
◦Which techniques did you use?
◦Pros and cons?
•What do you think of static site generators?
◦What type of projects are they suitable for?
•What is Open Graph and how do you make use of it?
•How did you implements comments to blog posts

####Precompiled CSS
Precompiled CSS save a lot of work, and enable the developer to keep the web-pages consistent.
The compiled CSS has several advantages, several CSS files can be compiled into one file, improving performance and 
avoid repetition of the same code. It abstracts the CSS into files that can be managed well in a project, 
without having to bother about performance issues such as merge conflicts, thus increase through-put. The pre-compiled 
CSS has higher tool-chain overhead then regular CSS.
It is dependent on the tool-chain, thus it become more dependent on version handling of these tools and the "feature"
 they offer can be seen as both a blessing and a course. Blessing because they have the potential to automate things 
 and offer extra functionality, at a low cost. Curse, because the user/developer get dependent of a certain tool-chain 
 that could be costly to maintain and may after some time become out-dated. The biggest risk is to become locked-down 
 with a old or in worst case several versions of code generators, caused by over-usage/dependencies of "features" and 
 costumer demands. A common model for debit of costumers, is the amount of work/hour. Small changes and to keep old 
 tools/versions and environments, is seen a beneficial in the short-term, even thaw the long-term cost may be sever, 
 both in terms of work-hour, but also in the more invisible cost of lost competence-development/security and integration 
 their environment. I thing pre-compiler CSS have clear advantages, as long as the code is continuously maintained 
 and the compilation is up-to-date, to use a boiler-plate is a clear advantage.
 The version handling must be on both the code AND the environment that generate the code!
 Compiled code can be "nice-to-have" as a reference, if the build-process derails, for some reason.


####Static site generators
Static site generators, are just as the name indicates, suitable for static/semi-static information, such as web-sits 
containing, buisness-location, restaurant-menues, company-adress/telephone-number, publication of electronic books, results and scores.
In short, everything that represent a result of some sort of activity that does not change/or change rarely.
Rarely meaing something like once-per-day, allowing the site to be regenerated, in controlled manor on a predictable time.
Advantages with static site generators, are their safety,stability and simplicity to update. which makes them an 
attractive alternative. This make them less attractive to buisness-sites, that nower-days, need to keep tack-of rapid 
price-changes and "just-in-time" supply-chains. I like static-site generators, because of their, short "start-up" time, 
and they suffice, when there is a  need to get some-ting of the ground fast.

•What is robots.txt and how have you configure it for your site?
•What is humans.txt and how have you configure it for your site?

####robots.txt 

####humans.txt
<http://humanstxt.org/>
####"This" blog post
I implemented this blogg, with the usage of DISQUS. It is very nice, but unfortunately, one need to have 
access/connection to a web-server, with the rights to run java-script. Also to configure and add features, are quite 
technically demanding for most people, that may not be so into programming.
<https://disqus.com>

####Open Graph

 Open graph, is an interesting technique, but a major hurdle, is that FACEBOOK is so dominating, when it comes to 
 developing/influencing the future.That there will be companies and standards, that "glue" the web together, is certain,
 but which standard and who that will develop it is unclear. The connection with a certain service provider is definitively 
 a problem, and as long as one part will be dominating, the cost and lack of influence, will drive forward alternative 
 that will compete or be used in parallel, thus one can predict a turbulent future with relatively high maintenance-costs,
 for those who wishes to keep "up-to-date".
 
<https://www.quora.com/Why-doesnt-Wikipedia-use-Twitter-Card-or-Open-Graph-markup-in-their-articles>
