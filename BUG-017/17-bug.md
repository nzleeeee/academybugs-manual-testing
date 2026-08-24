# Bug Report

## Bug ID
BUG-017

## Title
Order History section hangs on an infinite loading loop in user Dashboard

## Environment
- OS: Windows / macOS
- Browser: Chrome / Firefox / Edge
- Website: https://academybugs.com

## Preconditions
User is logged in on the AcademyBugs website.

## Steps to Reproduce
1. Open the browser and navigate to `https://academybugs.com`
2. Click on the **Find Bugs** link in the navigation bar
3. Click on any product to open its details page
4. Sign in (or sign up) via the form at the bottom of the right side menu
5. Click on **Order History** at the bottom of the right side menu

## Expected Result
The Order History section should load and display the user's past order details.

## Actual Result
The Order History section displays a loading animation indefinitely and fails to render order data.

## Severity
High

## Priority
High

## Attachment
![Bug #17 Screenshot](./17-bug.png)
![Bug #17 GIF](./17-bug-gif.gif)