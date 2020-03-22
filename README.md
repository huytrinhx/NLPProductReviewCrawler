# AmazonProductReviewCrawler
## Introduction

This is a simple end-to-end automation scripts in UIPath language - a wrapper around VB.NET. This crawler will take user input url and scrape all the reviews from that product and output to an Excel file.


## Installation and Important Setup

You'll need to install UIPath Studio - Community Version (Free) or Enteprise (Paid) - in order to run the Main.xaml file.

If you know how to sign up for a free trial of UIPath Orchestrator, then create a credential in Orchestrator to store your login credentials for Amazon account, then update the credential name in the corresponding variable inside the User Input Validation state of Main.xaml file. If not, for the sake of simplicity, please log in to your Amazon account using your own credential before running this solution in Internet Explorer. Amazon will remember your login so you can bypass the login step in subsequent runs.

## Few suggestions in future developments

1. This solution is designed to take user input and scrape all the reviews one product at a time. If we have a need to scrape multiple products, we can modify the solution to read a spreadsheet of urls instead of asking for only one url.

2. In a larger scale, even create a list of product urls to start with takes a lot of manual work. Therefore, we can build a solution to create a list of urls of top N (reviewed, best-selling...) products for a department or product categories.

## Bugs and Status
