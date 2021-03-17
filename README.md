<p align="center">
    <a href="https://croct.com">
      <img src="https://cdn.croct.io/brand/logo/repo-icon-green.svg" alt="Croct" height="80"/>
  </a>
</p>
<h1 align="center">CROCT</h1>

# Croct Integration Guide

This guide aims to introduce Croct's technology, and explain how it can be integrated into your applications.

## Table of Contents

- [Introduction](#introduction)

- [Target Customers and Benefits](#target-customers-and-benefits)

- [Development Details](#development-details)

- [How to Implement It](#how-to-implement-it)

- [Ways to Identify Your Customers](#ways-to-identify-your-customers)

- [Next Steps](#next-steps)

## Introduction

Croct is a [SaaS](https://www.salesforce.com/br/saas/) platform that provides technology for real-time personalization, through unified and managed customer data. Once it's implemented, Croct's API starts to collect data 
from users and creates a customized experience for each one of them by sending timely and relevant messages. This way, the near-term customer lifetime value can be increased by creating more targeted messages.

The personalization is mainly focused on the following approaches:

- Boost conversion.
- User experience improvement.
- Engagement increase.

## Target Customers and Benefits

It is aimed for marketers, product managers, and software engineers. The platform allows features adjustment to meet each customer's unique needs, which increases the revenue. 
The platform is also expertly designed for developers, allowing them to focus on building great products instead of spending time and money on expensive personalization infrastructure. 
By working with Croct, companies can take full advantage of first-party customer data to create a positive customer experience, and increase their Return on Investment.

## Development Details

Thinking about the developers experience, and the revenue increase, an English-based language called Contextual Query Language (CQL) was designed to abstract away from marketing, product, and development teams the complexities 
behind delivering personalized experiences online. Therefore, even non-developers can work with this new straightforward programming language.

For example, `page's title` is a valid CQL expression that tells you the title of the page the user is currently viewing. Similarly, `user's name` will tell you the name of the user using your app.

Currently, Croct provides a Software Development Kit (SDK) for JavaScript that can be installed by using the NPM package manager. For more information, and installation details, refer to 
[Quick Start Guide](https://github.com/croct-tech/plug-js/blob/master/docs/quick-start.md).

## How to implement it

The technology provided by Croct works for both web (Vanilla JavaScript, React, Vue, NextJs, etc) and app (iOS and Android), and can be implemented as follows:

1. Identify the information that will be used by the personalization engine.

2. Define the audience, and whether it will be an experiment or not, what will be personalized, and which metrics will help to measure the outcome of the personalization. 

3. Finally implement the personalization, and, eventually, the tracking to measure the results.

## Ways to Identify Your Customers

Customers can be identified by multiple ways, that is, the personalization engine can be adjusted to identify components such as:

- Weather: Your offer can be adapted as people's needs change according to climate and weather.

- Location: Use your customer's whereabouts to define what should be offered.

- Profile: Different people have different interests. Adapt the content according to your customer's profile.

- Behavioral: Establish and use patterns to determine what content should be shown.

- Session: Are your customers leaving your website without interacting with the page?

- Marketing: It's important to keep your communication consistent along the entire purchase flow.

## Next Steps

That's it! You have now the basics of how to integrate Croct's technology into your apps.

If you want to learn more about Croct, check out the other sections in the [documentation](https://github.com/croct-tech/plug-js/blob/master/README.md#documentation). 












