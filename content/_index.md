+++
title = "Home"
date = 2020-10-06
+++

# The Better Web Alliance
Is a voluntary collection of websites and web developers aiming to make the world wide web a better place by putting users first. This is an experiment very much in the early stages and any feedback and collaboration is most welcome. Eventually it is hoped that this website can provide useful resources for developers hoping to make the web a better place, such as links to tutorials and how to articles, and list of websites that have pledged to follow our principles.

## We have a small collection of guiding principles:
1. Respect the privacy of your users.
2. Minimise your impact on infrastructure and the environment.
3. Make your content accessible for all.

## Why is this needed?
The nature of the web is changing. Total page weight is rapidly increasing. Images and videos are replacing text. Tracking scripts and analytics seem to be becoming increasingly common. Major data breaches exposing personal information of users are a regular occurrence. More and more sites seem to be hiding information behind pay walls.

Some of the best content on the web, it is true, is created by people who can make a living out of it. However, if you look at a random selection of popular websites many of them seem to share some unfortunate features in common:

- Large page weight contributing to slow load speeds and expensive downloads for those on metered connections.
- Poor accessibility: many sites omit aria attributes and use non standard ‘hacks’ to achieve layout.
- Heavy reliance on tracking scripts that monitor the activities of visitors and record their personal information without their consent.

This is bad for users, often bad for the site itself as slow loading and browser incompatibilities in scripts drive visitors away, and bad for the environment as these pages generally produce a lot of carbon per view.

## What can you do to help?
### 1. Respect the privacy of your users.
#### The problem
Invasive tracking scripts like google analytics and facebook pixel collect huge amounts of unnecessary personal data on your visitors, violating their privacy and heavily slowing down page load speeds. Most browsers are now blocking these to one extent or another and when they are embedded too deeply into your dependency stack can break other functionality on the page when they fail to load<sup id="a1">[1](#f1)</sup>. Tracking scripts frequently share data with other websites and the deep personal profiling that this allows is driving the rise in targeted political advertising and misinformation across the web<sup id="a2">[2](#f2)</sup>.

#### Steps to take
Ask yourself do you really need to collect all of this information on your users? Is the tiny percentage increase in sales that knowing your customers' favourite colour provides greater than the loss in sales from visitors leaving your website in frustration? If you were to swap shoes with them for a moment, would you be happy with the amount of data you are collecting on yourself? 

### 2. Minimise your impact on infrastructure and the environment.
#### The problem
The internet as a whole may currently consume as much as 10% of the world's electricity<sup id="a3">[3](#f3)</sup>. This produces a huge amount of carbon emissions that contributes to climate change and environmental destruction. Visitors to websites are also increasingly likely to abandon them the longer they take to load<sup id="a4">[4](#f4)</sup>. Large websites are almost always slow websites, bad for users and bad for the planet.

#### Steps to take
Fortunately, small improvements in website size and performance can quickly add up due to the sheer size of the web. Optimizing and reducing the number of images, avoiding using frameworks wholesale, and cutting down on the amount of javascript you use can all help with making your website lighter and faster.

### 3. Make your content accessible for all.
#### The problem
Not everyone who visits a website can see or possesses fine motor control. Many sites that look visually appealing can be totally impenetrable to those using screen readers and the machines that index the web. Newsletter popups and lengthy multi-page forms may be attractive for marketing, but can be extremely frustrating for those who lack the ability to use a mouse or have cognitive impairments.

#### Steps to take
Standard HTML elements have many accessibility features already implemented; always use the appropriate ones to represent your content, don't be tempted to reinvent the wheel. Make sure your choice of colours has sufficient contrast for those who are colour blind or partially sighted. Use alt text on images and ARIA attributes where necessary. Don't assume that all of your users have access to as powerful devices and fast internet connections as you do.

## References
<ol class="footnotes">
    <li id="f1">
        <a href="https://github.com/magento/magento2/issues/21326">https://github.com/magento/magento2/issues/21326</a> - accessed <time datetime="2020-10-06">2020-10-06</time>
    </li>
    <li id="f2">
        <a href="https://www.wired.com/story/cambridge-analytica-facebook-privacy-awakening/">https://www.wired.com/story/cambridge-analytica-facebook-privacy-awakening/</a> - accessed <time datetime="2020-10-06">2020-10-06</time>
    </li>
    <li id="f3">
        <a href="https://internethealthreport.org/2018/the-internet-uses-more-electricity-than/">https://internethealthreport.org/2018/the-internet-uses-more-electricity-than/</a> - accessed <time datetime="2020-10-06">2020-10-06</time>
    </li>
    <li id="f4">
        <a href="https://econsultancy.com/slow-loading-websites-cost-retailers-1-73bn-in-lost-sales-each-year/">https://econsultancy.com/slow-loading-websites-cost-retailers-1-73bn-in-lost-sales-each-year/</a> - accessed <time datetime="2020-10-06">2020-10-06</time>
    </li>
</ol>