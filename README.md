# Take-Home-Assignment

We, at One Door, are a very practical team and this extends to the way that we work with you to find out if this team is a great fit for you. We want you to come away with a solid understanding of the work that our engineers do on a daily basis and what it is like to work on our team.

So instead of subjecting you to a live-coding interview or whiteboard session with someone looking over your shoulder, we provide a take-home assignment that is meant to be completed in approximately four hours of dedicated developer time. Do not feel the need to over-engineer your solution; however, we do value quality over quantity and be prepared to explain and extrapolate upon your design and implementation decisions.

## Guidelines

- Our preference in programming language is prioritized as follows: Ruby, Python, JavaScript, Java
  - however, you should write your solution in the language you feel is your strongest
- The format of your submission may be either a **zip** file or Github repo/gist.
- Include tests for your solution as if this assignment were to be deployed to production.
- Include a README.md for documenting the rationale behind your technical decisions, provide any trade-offs you measured for, and anything you would like to do differently given you were provided more time on the assignment.

## The Challenge

You've been tasked to work on our Merchandising Categories system. Merchandising Categories are similar to the product categories you would see in any e-commerce store, except they're used for categorizing products in a physical store. One of our clients has hundreds of categories and has requested information about them.

An example category structure might be "Pets > Pet Food > Dog Food > Organic > Bulk Dry Food", where "Bulk Dry Food" is the 5th-level category. The data in the attached JSON file is for testing purposes and differentiates subcategories using a letter+number (‘A1’, ‘C5’) combination to denote the level and count of items at that level.

Build a REST API that utilizes CRUD fundamentals. Provided the attached `categories.json` file, implement two HTTP endpoints that fetch the following payloads:

1. Retrieve the `name` and `products` attributes for a) specified category or subcategory and b) its immediate children.
2. For any given category or subcategory, retrieve the count for the total number of children and their descendants.

_Note: if you are unclear about the language, phrasing, or context of these requirements, please state your assumptions and proceed accordingly_
