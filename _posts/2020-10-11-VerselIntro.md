---
layout: post
title: Hey there! Vercel!
snippet: Hoisting Dynamically Scalable Static Site
comments: false
---

Hi there!

<p>So I was updating the README section of my Github profile and I found <a href="https://github.com/anuraghazra/github-readme-stats">this</a> amazing repository to add my <strong>Github Stats</strong>. Thanks to <a href="https://github.com/anuraghazra/github-readme-stats">anuraghazra</a> for this great repository.</p>

### But! But! But!
<p>After I implemented the logic to showcase the stats, it just froze. The README section was show only a link to the <a href="https://github.com/anuraghazra/github-readme-stats">repository</a>.</p>

> Here comes the saviour in the picture! Vercel!

---

## Vercel:

> Vercel is a cloud platform for static sites and Serverless Functions that fits perfectly with your workflow. It enables developers to host Jamstack websites and web services that deploy instantly, scale automatically, and requires no supervision, all with no configuration.

<br>
Here is the [documentation](https://vercel.com/docs)

---

<p>So I had to deploy my forked repository on Vercel to create a specific Versel instance for my application. </p>

### Deployment on Vercel:
<p>
Deployment on Vercel is a straight-forward process. Below are quick points to Deploy on Vercel:
<ol>
<li>Create a Vercel Account by logging through Github</li>
<li>Select your repository to deploy</li>
<li>Update the configs as per your requiremments.</li>
<li>Thats it! Hit Deploy! You are good to go.</li>
</ol>
</p>

> Personal Access Token: You might need to create a Personal Access Token from your Github Profile to authenticate Github from Vercel at the go. To create a PAT, Goto Settings -> Developers Setting -> Personal Access Token -> Generate PAT. Then the generated PAT can be added as an Environmental Variable in the Vercal App.

<p>
Below are the snapshots from the doploment of my instance:<br>
<code>Starting the deployment</code>
<img src='{{ site.baseurl }}/assets/2020-10-11_VercelDeployment.png' alt="Lynis_report"/>
<code>Voila</code>
<img src='{{ site.baseurl }}/assets/2020-10-11_Vercel_Deployed.png' alt="Lynis_report"/>
</p>

---

### Finally:
Here is how the Stats appear on the Github Profile:
<img src='{{ site.baseurl }}/assets/2020-10-11_Stats.png' alt="Lynis_report"/>

> Yeah! Improving these stats is a goal of mine.

Lets catch-up in the next post.

Till then O/