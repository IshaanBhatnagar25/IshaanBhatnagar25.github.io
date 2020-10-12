---
layout: post
title: List-index-out-of-range
snippet: Why the hell the index is out of Range
comments: true
---

Hey there! 
<p>From today onwards, I will log my daily progress in the blog. I recently read an amazing blog of a friend of mine that had a <strong>daily progess section</strong>. The motive behind:</p>

>If I'll put it in public, I'll do it, may be not now, but certainly I will. 

<p>What are your views on this, let me know in the comments section!</p>

<p>
First of all the daily progress/goals section:
<ol>
<li>Setup the <strong>About</strong> section of the portfolio</li>
<li>Update the readme section of my <a href="https://github.com/IshaanBhatnagar25">Github Profile</a></li>
<li>Design a workflow in github to fetch my top 5 blogs and show them on the ReadMe section.</li>
<li>Saperate Bolgs on the implementation of topics mentioned above. 😆</li>
</ol>
</p>

<p>Okay! Well now coming to the title, <code>IndexError: list index out of range</code>.So how often you encouter this 😆. Or how often you end up spending hours on something like this.</p>

<p>I'm pretty sure, many time would be the answer.</p>

<p>Actually, I faced an issue today where I was running a loop like this:</p>

```python
for i in range(0,len(my_list)):
    stuff_done_here
```

<p><br>And in the loop, I was deleting certain entries from the original list <code>my_list</code>. So during the iterations, the length of the list actually got reduced and hence, I was getting this: <br><code>IndexError: list index out of range</code><br> Though it seems to be a straight-forward issue, yet it took me about an hour error to find the root-cause.😆</p>

### The FIX:<br>

```python
for index,item in enumerate(my_list):
    stuff_done_here
```

<p><br><code>Enumerate()</code> method adds a counter to an iterable and returns it in a form of enumerate object. This enumerate object can then be used directly in for loops or be converted into a list of tuples using <code>list()</code> method.</p>

<p>Find out more on this <a href="https://www.geeksforgeeks.org/enumerate-in-python/">here</a></p>

<p>Lets catch up in the next post.</p>
<p>Till then O/</p>