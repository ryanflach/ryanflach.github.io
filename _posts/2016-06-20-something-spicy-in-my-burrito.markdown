---
layout: post
title:  "Something Spicy in my Burrito"
date:   2016-06-20 09:08:26 -0700
categories: thoughts
---
Hello there. If you're reading this, you're either Andrew Carmer, a curious classmate, or terribly lost.

I'm comfortably sitting on my parents' couch in San Diego as I write this. I didn't grow up here, but it's a nicer place to call home than State College, Pennsylvania, was. My intermission week in San Diego has largely been spent at my computer, but I did go to the beach this morning with my brother and his family. Although crowded, body surfing and walking the beach down to the pier was a much needed break from computers. I'll try and visit with some friends while here as well.

Jekyll (the interface with which this blog was built) allows the use of [Liquid](https://github.com/Shopify/liquid/wiki) templating to include code snippets. I'm writing this entirely so I don't forget what that is and what it does. It can do many things, but one of them is to display Ruby code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

I stole that code from the example post. It's not the most exciting method, but _that's not the point_.

Well, I feel as though I've probably typed more than enough for this demonstration, so I will leave you with a YouTube video of me playing drums in the Philippines that I've embedded using the tips found [in this blog post](http://www.adamwadeharris.com/how-to-easily-embed-youtube-videos-in-jekyll-sites-without-a-plugin/).

{% include youtubePlayer.html id="aVmCZwhS3xA" %}

Finally, to test an issue that others were having, here's my Turing headshot:
![Picture of the author]({{ site.url }}/_assets/ryan-flach.jpg)
