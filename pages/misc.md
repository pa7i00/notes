---
layout: default
title: misc
---

This is a page (not post).

{% highlight c %}
#include <stdio.h>

int main(int argc, char *argv[])
{
  if (argc > 1)
    print("Hello, %s.\n", argv[1]);
  else
    print("Hello, world.\n");

  return 0;
}
{% endhighlight %}
