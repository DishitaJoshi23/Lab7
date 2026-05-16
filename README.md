Name: Dishita Joshi

## Check Your Understanding Questions
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

   1. Within a Github action that runs whenever code is pushed 
   2. Manually run them locally before pushing code
   3. Run them all after all development is completed
 
    Answer: Within a Github action that runs whenever code is pushed. 
    This is because it automatically enforces testing on every push in a clean, consistent environment.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
    Answer: No, because we would use unit test to check a specific function.

3) What is the difference between navigation and snapshot mode?

    Answer: Navigation mode tests the full page load experience based on metrics like Speed index, first contentful paint, etc. While the snapshot mode tests the performance in the current state of the page without reloading it. So, the snapshot mode relies on metrics like explicit width and height of the elements that already on the page. 

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   Answer:
   1) Accessibility: the html element does not have a lang attribute.
   2) Performace: The speed index can be higher (speed index = 1.5).
   3) SEO: Document does not have a meta description.

