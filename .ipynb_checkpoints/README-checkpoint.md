# Discounted Cash Flow Valuation on J.P Morgan
---

<img src="Images/logo.jpg" />

## Background

I have a HireVue interview for the JP Morgan Wealth Management Analyst position to finish by tomorrow night. So, I wanted to value JP Morgan before that. I usually calculate Discounted Cash Flow (DCF) using Excel, but I recently found an [article](https://towardsdatascience.com/discounted-cash-flow-with-python-f5103921942e) that shows how to do a DCF model using python. I can use that to learn more about JP Morgan while getting hands-on with DCF using python.

Last time, I did a [valuation of Roku, Inc](https://github.com/danalain/Market_Financial_Analysis_Roku#Investment-Strategies) on Excel. However, Roku is different because it went public in 2017, and the streaming industry is just starting to boom. So, it has a lot of assumptions. I wonder an automated DCF model in python might work for JP Morgan. So, let's have at it! Shall we?

---
## File

1. [Discounted Cash Flow Model]("Codes/DCF.ipynb")

## Note

I realized what a terrible idea that was. At least I got more practice on how to use python loops. Even though the code is okay, the financial data I was getting is a few billion off from SEC filing's data provided on SEC.gov. You can see how that can mess with the valuation, right? 

I included the code so that anyone interested can learn and improve upon it. Don't forget to apply for an API key from [this website](https://financialmodelingprep.com/developer). You can try using the code for other companies from a different industry.

The banking industry is different because cash is their resource and the product. Banks move money around a lot through loans, deposits, and investments. Projecting Free Cash Flow using the standard model, which includes subtracting CAPEX from the Operating Cash Flow, is very limited. So, we need to look at revenue, book values, margins, and growth rate. The annual report for 2020 will also be coming out soon. 

By March 2021, we can get a more detailed look at the current valuation of JPM. There are also great resources for the valuation of JPM like [this video](https://www.youtube.com/watch?v=7OIZLsVLvsg).

---
## Written by 

__Dana K Lain__, Profile: [LinkedIn](https://linkedin.com/in/dana-kyine-lain)