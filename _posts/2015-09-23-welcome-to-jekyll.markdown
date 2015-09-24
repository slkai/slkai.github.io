---
layout: post
title:  "Welcome to Jekyll!"
date:   2015-09-23 15:33:13
categories: jekyll update
---


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

{% highlight objective-c linenos %}
@interface YCFPurchaseNoteView () <DTAttributedTextContentViewDelegate, DTLazyImageViewDelegate, DTWebVideoViewDelegate>
{
    UIView *_packageContentBGView;

    NSMutableArray *_imageViewArray; // lazyImageView 的数组

    float _contentHeight;

    float _isExpanded;

    CGFloat _orginalHeight;

    DTAttributedTextView *_htmlTextView;

    UIButton *_arrowImgView;
}

@end

{% endhighlight %}