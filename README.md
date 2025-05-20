# Lab 7

## Check Your Understanding

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
- Within a Github action that runs whenever code is pushed 
- Manually run them locally before pushing code
- Run them all after all development is completed

*Within  GitHub action that runs whenever code is pushed so that it can be used to check the quality of the code incrementally during development.*

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

*No, because end-to-end testing emulates user input from start to finish. This testing evaluates many parts of some code and interactions between them. Testing if a function returns correct output is best done with unit tests to minimize the variables in play.*

3) What is the difference between navigation and snapshot mode?

*Lighthouse analyzes the overall performance of the site right after page load in navigation mode. In snapshot mode, it analyzes the site in whatever current state the site is in, which may be after some user interaction has occurred since page load.*

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

*Three improvements we can have are:*
- Adding a `<meta name="viewport">` tag with `width` or `initial-scale` to optimize for mobile screen sizes
- Serve images appropriately-sized to the display to save cellular data and improve load time
- Include a `[lang]` attribute in the `html` element tag to improve screen reader experiences

