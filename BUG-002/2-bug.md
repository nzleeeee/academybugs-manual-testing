# Bug Report

## Bug ID
BUG-002

## Title
Cart grand total calculation includes an extra $100 overcharge

## Environment
- OS: Windows / macOS
- Browser: Chrome / Firefox / Edge
- Website: https://academybugs.com

## Preconditions
User is on the AcademyBugs homepage.

## Steps to Reproduce
1. Open the browser and navigate to `https://academybugs.com`
2. Click on the **Find Bugs** link in the navigation bar
3. Add one or more products to the cart
4. Click **View Cart** on top of the page (or click **Continue to Shipping** on the checkout page)

## Expected Result
The grand total should be exactly equal to the sum of all item prices in the cart plus any applicable taxes or shipping fees.

## Actual Result
The grand total calculation adds an extra $100 to the total sum of the items in the cart.

## Severity
Critical

## Priority
High

## Attachment
![Bug #2 Screenshot](./2-bug.png)
![Bug #2 GIF](./2-bug-gif.gif)
