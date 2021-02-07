---
layout: post
title: Its Time to Evaluate!
snippet: Basic meathods to evaluate the ML Models
comments: false
---

Hi there!

<p>Lets discuss various ways to Evaluate an ML Model.</p>

### Basic Terminology:
<p>
<ul>
<li>True Positive(TP): Predictive Positive is actually Positive.</li>
<li>False Positive(FP): Predictive Positive is actually Negetive</li>
<li>True Negetive(TN): Predective Negetive is actually Negetive</li>
<li>False Negetive(FN): Predictive Negetive is actually Negetive</li>
</ul>
</p>

### Confusion Matrix:
<img src='{{ site.baseurl }}/assets/2021-02-07_ConfusionMatrix.png' alt="ConfusionMatrix"/>

### Accuracy:
<code>Accuracy = (TP + TN)/(TP + TN + FP + FN)</code>

### Precision:
> How much the model is Right when it says it is Right!
<p><code>Precision = (TP)/(TP + TN)</code></p>

### Total Positive Rate/Recall/Senstivity:
> % of Positive Instances out of Total Positive Instances
<p><code> TPR = (TP)/(TP + FN)</code></p>

### Specificity:
> % of Negetive Instances out of Total Negetive Instances
<p><code> TPR = (TN)/(TN + FP)</code></p>

### F1 Score:
> It is the Harmonic Mean of Precision and Recall.
> The higher the F1 Score, the better it is.
<p><img src='{{ site.baseurl }}/assets/2021-02-07_F1Score.png' alt="ConfusionMatrix"/></p>

### PR Curve:
>It is the curve between precision and recall for various threshold values.


Lets catch-up in the next post.

Till then O/