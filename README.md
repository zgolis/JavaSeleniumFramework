JavaSeleniumFramework

This is a generic test framework based on a Contact Us page.
Steps / Expected Results:
Test Case 1: ContactUs_Required

    Navigate to 'Contact Us' page E. Page loads with required items displayed and required and no invalid feedback text is displayed.

    Click the submit button. E. Invalid feedback text is displayed for all but Address 2.

    Verify each invalid feedback text is present with text that matches. E. Invalid feedback text displays correctly.

Test Case 2: ContactUs_Validate

    Navigate to 'Contact Us' page. E. Page loads with a header, 6 input fields, 2 selects and 1 button to submit displayed.

    Validate both selects contain all their options. E. Country select has 2 options and State has three options and each are displayed correctly.

Test Case 3: ContactUs_Verify

    Navigate to 'Contact Us' page. E. Page loads.

    Fill out all available fields. E. Each field displays the correctly inputted information.

    Click the submit button. E. New page loads with specific success text.

    Click the 'Back' link. E. Previous page loads.
