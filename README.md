# Take-Home-Assignment
We, at One Door, are a very practical team and this extends to the way that we work with you to find out if this team is a great fit for both of us. We want you to come away with a solid understanding of the work that our engineers do on a daily basis and what it is like to work on our team.

So instead of subjecting you to a live-coding interview or whiteboard session with someone looking over your shoulder, we provide a take-home assignment that is meant to be completed in approximately four to eight hours of dedicated developer time. Do not feel the need to over-engineer your solution; however, we do value quality over quantity and be prepared to explain and extrapolate your design and implementation decisions.

## Guidelines
- Think of this assignment as an open source project. Create a repo on Github, use git for version control, and provide tests for your solution as if this assignment were to be deployed to production.
- Include a README.md for documenting the rationale behind your technical decisions, provide any trade-offs you measured for, and anything you would like to do differently given you were provided more time on the assignment.

## The Challenge
You've been tasked to work on our Merchandising Categories system. Merchandising Categories are similar to the product categories you would see in any e-commerce store, except they're used for categorizing products in a physical store. One of our clients has hundreds of categories and has requested for information about them.

An example category structure might be "Pets > Pet Food > Dog Food > Organic > Bulk Dry Food", where "Bulk Dry Food" is the 5th-level category. However, in the attached JSON file, sub-categories are only differentiated by a letter+number ('A1', 'C5') combination.

Using the language of your choice, build a REST API that utilizes CRUD fundamentals. Implement two HTTP endpoints that fetch the following payloads based on the attached `categories.json` file:
1. Retrieve the `name` and `products` attributes for a specified category/sub-category and its immediate children
2. For any given category or sub-category, retrieve the count for the total number of children and their descendants
