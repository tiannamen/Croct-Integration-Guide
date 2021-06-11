<p align="center">
    <a href="https://croct.com">
      <img src="https://cdn.croct.io/brand/logo/repo-icon-green.svg" alt="Croct" height="80"/>
  </a>
</p>
<h1 align="center">CROCT</h1>

# Croct Integration Guide

This guide introduces Croct's technology, and explains how to integrate it into your applications.

## Table of Contents

- [Introduction](#introduction)

- [Target Customers and Benefits](#target-customers-and-benefits)

- [Identifying Different Customers with the Personalization Engine](#identifying-different-customers-with-the-personalization-engine)

- [Integrating Croct into your applications](#integrating-croct-into-your-applications)

- [Next Steps](#next-steps)

## Introduction

Croct is a [SaaS](https://www.salesforce.com/br/saas/) platform that provides technology for 
real-time personalization, through unified and managed customer data. Once it is implemented, 
Croct's API starts collecting data from users and creates a customized experience to each one 
of them, by sending timely and relevant messages. Creating more targeted messages increases the near-term 
customer lifetime value.

The personalization is mainly focused on the following approaches:

- Boost conversion;
- User experience improvement;
- Engagement increase.

## Target Customers and Benefits

Marketers, product managers and software engineers can benefit from using Croct's API. 
The platform allows feature adjustments to meet each customer's unique needs, which increases the revenue. 
This technology also benefits the developers, by allowing them to focus on building great products instead 
of spending time and money on an expensive personalization infrastructure. 
By working with Croct's API, companies can take full advantage of first-party customer data to create 
a positive customer experience, and increase their Return on Investment.

## Identifying Different Customers with the Personalization Engine

There are many ways to identify customers, by adjusting the personalization engine, such as:

- Weather: Adapt your offer as people's needs change according to climate and weather.

- Location: Use your customer's whereabouts to define what should be offered.

- Profile: Different people have different interests. Adapt the content according to your customer's profile.

- Behavioral: Establish and use patterns to determine what content should be shown.

- Session: Are your customers leaving your website without interacting with the page? Identify what is wrong and provide more assertive offers.

- Marketing: It is important to keep your communication consistent along the entire purchase flow.


## Integrating Croct into your applications

Thinking about the developers experience, and the revenue increase, Croct designed an English-based 
language called Contextual Query Language (CQL). Its goal is to abstract away, from marketing, product, 
and development teams, the complexities behind delivering personalized experiences online. Therefore, 
even non-developers can work with this new intuitive, straightforward programming language.

For example, `page's title` is a valid CQL expression that tells you the title of the page the user is 
currently viewing. Similarly, `user's name` will tell you the name of the user who is using your app.

Currently, Croct provides a Software Development Kit (SDK) for JavaScript that can be installed 
by using the NPM package manager. For more information, and installation details, refer to 
[Quick Start Guide](https://github.com/croct-tech/plug-js/blob/master/docs/quick-start.md).

The technology provided by Croct works for both web 
(Vanilla JavaScript, React, Vue, NextJs, etc) and app (iOS and Android), and can be implemented 
by following the steps below:

1. Identify the information that the personalization engine will use;

2. Define the audience, and whether it will be an experiment or not, what will be personalized, 
and which metrics will help you measure the outcome of the personalization; 

3. Finally, implement the personalization and, eventually, the tracking to measure the results.


## Next Steps

That's it! You have now the basics of how to integrate Croct's technology into your apps.

If you want to learn more about Croct, check out the other sections in the [documentation](https://github.com/croct-tech/plug-js/blob/master/README.md#documentation). 












