# Magento 1.x CE GDPR Compliance

## Overview
GDPR compliance is a worry for many businesses based in the EU. This free extension supports Cookie Compliance and Customer Data Anonymisation. The GDPR Complicance module for Magento 1 adds some key features to aid your support in meeting the requirements set out in the new General Data Protection Regulation (GDPR) legislation which comes into effect throughout the EU on 25 May 2018. Key requirements under the new legislation include the removal of customer data on request.

Magento Core code does not currently facilitate this therefore all sites without this extension (or similar) will not be adhering to legal requirements, given Magento can store customer cart data (quotes) and customer order data for failed orders. Both these should not be retained by Magento under new laws. The 'Express Consent' law also requires that you refrain from setting ALL non-essential cookies (including 3rd party cookies and beacons) from operating UNTIL express consent has been granted. This extension supports both these requirements.

 

## Features
* **Cookie Notification Popup**: requesting ‘express consent’ from your website visitors upon entering your website.
* **Delete Customer & Anonymise Data from Admin or Front-end**: Although legally a business is permitted to retain customer information if the customer has purchased from you, Magento does have functionality to record sales data (sales and quotes) even if the order has not technically resulted in a completed sale. This extension allows you to fully anonymise customer data from Customer, Sales, Quotes tables so that you can feel assured that you have met your GDPR obligations

 
 ## Installation
 * **Compatible with Magento CE**:  1.8, 1.8.1, 1.9, 1.9.1, 1.9.2, 1.9.3
 
 ### Using modman
 ```
 modman clone https://github.com/landofcoder/Magento1_GDPR
 ```
 
 ### Manual installation
 * [Download the extension from Github](https://github.com/landofcoder/Magento-1.x-CE-GDPR-Compliance/archive/master.zip)
 * Drag and drop into your web directory

## Acknowledgments

This extension requires a basic understanding of Google Tag Manager.
