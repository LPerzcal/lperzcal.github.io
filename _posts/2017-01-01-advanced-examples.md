---
title:  "Analysis of Customer Retention"
mathjax: true
layout: post
categories: media
---

![Swiss Alps](https://user-images.githubusercontent.com/4943215/55412536-edbba180-5567-11e9-9c70-6d33bca3f8ed.jpg)

### <font style="color : darkgrey">Duration: 6 weeks</font> <br>
**Stakeholders:** Data Engineers, Product Manager, Account Managers, Data Analyst, other relevant departents. <br>
✅ SQL  ✅ Databricks  ✅ Tableau  ✅ JIRA  ✅ Microsoft Teams  ✅ Asana

### **Project Overview**:
  The "Analysis of Customer Retention" project is aimed at understanding and improving customer retention rates for a business. 
  As customer retention is a critical factor in sustaining growth and profitability, this project focuses on leveraging data-driven insights 
  to identify trends, patterns, and potential drivers of customer churn. The analysis will be conducted in collaboration with cross-functional teams, 
  including data engineers, product managers and account managers, and will utilize tools like **SQL**, **Databricks**, and **Tableau** as visualization tool.

**1. Data Gathering and Preparation:** 
Define project scope, objectives, and deliverables. Identify stakeholders. Set up communication channels (meetings, emails, collaboration tools). 
Collaborate with data engineers to collect relevant customer data from databases using SQL. Clean, transform, and preprocess the data to ensure accuracy 
and consistency.


**2. Cohort Analysis:** Utilize Databricks to perform cohort analysis, grouping customers based on common characteristics or time periods. Calculate retention rates for each cohort 
to identify trends over time.

**3. Visualization and Dashboard Creation:** Create interactive visualizations and dashboards in Tableau to present retention metrics, cohort performance, and potential churn factors. The visualizations 
will make complex data insights more accessible to stakeholders.

**4. Insight Generation:** Analyze the visualized data to extract meaningful insights about customer retention trends, including identifying periods of high churn and potential influencing 
factors.

**5. Collaboration:** Collaborate with product managers and other stakeholders to align the analysis with business goals. Discuss findings, implications, and potential strategies for 
improving customer retention.

**6. Recommendations:** Based on insights derived from the analysis, develop actionable recommendations to enhance customer retention. These recommendations will guide the formulation 
of strategies to reduce churn rates.

**7. Implementation and Monitoring:** Work with cross-functional teams to implement retention-improvement strategies. Set up monitoring mechanisms to track the impact of these strategies on customer retention.






## MathJax

You can enable MathJax by setting `mathjax: true` on a page or globally in the `_config.yml`. Some examples:

[Euler's formula](https://en.wikipedia.org/wiki/Euler%27s_formula) relates the  complex exponential function to the trigonometric functions.

$$ e^{i\theta}=\cos(\theta)+i\sin(\theta) $$

The [Euler-Lagrange](https://en.wikipedia.org/wiki/Lagrangian_mechanics) differential equation is the fundamental equation of calculus of variations.

$$ \frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac{\partial L}{\partial \dot{q}} \right ) = \frac{\partial L}{\partial q} $$

The [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) describes how the quantum state of a quantum system changes with time.

$$ i\hbar\frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2\mu}\nabla^2 + V(\mathbf{r},t)\right ] \Psi(\mathbf{r},t) $$

## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

<script src="https://gist.github.com/5555251.js?file=gist.md"></script>

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}
