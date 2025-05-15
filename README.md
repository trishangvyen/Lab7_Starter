# Lab 7

Trisha Nguyen

## Check Your Understanding

1. I would fit my automated tests in my Recipe project development pipeline (1) within a Github action that runs whenever code is pushed because it's automated so you won't forget to do it and it ensures that everyone's code within the team is tested the same way.

2. No, E2E is for testing a whole application. For checking a single function, you should use unit tests.

3. The difference between navigation and snapshot mode is that navigation mode analyzes the page right after it loads, analyzing its performance, while snapshot mode analyzes the page in its current state, analyzing accessibility issues.

4. Three things we could do to improve the CSE 110 shop site based on the Lighthouse result are:
   1. Add a meta description: In both navigation and snapshot mode, I received the warning that "Document does not have a meta description." Having a meta description can be helpful in search results so they can briefly summarize the page.
   2. Add a [lang] attribute to the <html> element: In both navigation and snapshot mode, I received the warning that "<html> element does not have a [lang] attribute" which can cause accessibility issues if users have a default language that is not English.
   3. Properly size images: In navigation mode, I received the warning that images are not sized properly, meaning the actual size of the image is much larger than how it is render. Sizing the images properly can preserve data and shorten load times.
