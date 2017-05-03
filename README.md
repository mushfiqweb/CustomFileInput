# CustomFileInput
There are quite a few techniques for “customizing” the <input type=”file” /> element. I tried most of them, but none was good enough.

As as result, I tried googling for an unseen solution. Once it seemed that there was nothing new, my eyes were caught by a comment on StackOverflow. It had just a few upvotes and was lost somewhere in the middle of the page, but most importantly it contained a magic word – <label>! As you may know, pressing a label basically triggers the focus event for the bound input. Interesting thing is that, if it is a file input, it works out as a click event, resulting in opening a file browser. This is great for crafting a semantic solution.

Checkout the Article on www.mrShishir.ME/style-and-customize-file-input-tag-in-your-own-way-with-example

