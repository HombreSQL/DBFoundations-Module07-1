## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/chrisgpark/DBFoundations-Module07/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Assignment 7 – Functions

### Introduction 

In module 7, we dive deeper into views and functions. We learn about different types of functions, and how they're structured. We also create views and functions in the SQL query portion of the assignment. In this write-up, I'll discuss the use of UDFs, and the difference between Scalar, Inline and Multi-Statement functions.

### Topic: Types of Functions

We use User Defined Functions (UDFs) to create custom functions that are not pre-defined. We distinguish functions into two types: scalar and table functions. A scalar function returns a value, while a table function returns a table of values. As noted in the previous assignment, scalar functions have various uses, with checking for constraints being a major one. In assignment 7, we use a scalar function to create a binary variable to determine whether there has been an inventory count increase. While creating a view is often an indistinguishable alternative to a table function, a table function is far more consistent as we can include clauses that views exclude. Not to mention, a multi-statement function can process data outside the scope of a SELECT clause. We can virtually create a table using a script and then implement it into our function. In previous modules, we learned about subqueries or queries within a query. Inline functions are similar, with a select query in parenthesis. Again, we can use a view, but inline functions allow parameters.

### Conclusion

I was under the impression that the ability to work with SQL views is far more critical than functions. However, after completing this assignment, I realize that being fluent with scalar function can be very beneficial at work. I often create loops using VBA with conditional statements to create binary variables but using a scalar function will be much more efficient.

### Jekyll Themes
