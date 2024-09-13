---
title: "Welcom"
layout: post
---

Se probó distintos procesamientos de la variable "all_words"

Se trabajó con 26 oraciones

|       Técnica       |   Número palabras   |
|---------------------|---------------------|
| Tokenización        |         129         | 
| Stemming NLTK       |         61          |
| Lematizacion NLTK   |         58          |
| Lematizacion Stanza |         57          |

## Code

Source code can be included by fencing the code with three backticks. Syntax highlighting works automatically when specifying the language after the backticks.

This would be rendered as:

```python
function foo () {
    return "bar";
}
```

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
all_words = [stem(w) for w in all_words_orig if w not in ignore_words]
all_words = sorted(set(all_words))
tags = sorted(set(tags))
{% endhighlight %}


