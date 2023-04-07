# Robinhood tax document to pandas

This script helps me file state taxes since there are 17 pages of dividend details and I no longer want to manually calculate the totals within each state.

Specifically, since...

- the tax software wants to know how much dividends and sales gains/losses I earned while residing in each state,
- Robinhood doesn't offer a nice, clean CSV for dividends

I wrote this script (alongside ChatGPT) to:
- crop PDF where the tables are
- converts the cropped image to text
- serializes captured rows as pandas DataFrame
- sum up dividends prior to and after move date

![image](https://user-images.githubusercontent.com/15331990/230653267-84962ab5-6d8c-49b0-a612-adbef8c0430d.png)

Use at your own risk if you decide to use this for your own taxes.
