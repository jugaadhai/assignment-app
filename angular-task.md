# Angular Task Details
1. Create an angular app named `ng-jugaahai-task-yourname` (ex: `ng-jugaadhai-tak-jitangupta`)
2. On default page display list of articles
    1. Use article-list api to fetch list of articles 
    2. Create an article-summary-card to display the list of articles If you need any design inspiration, you can visit jugaadhai.in and see
    3. On click of article-summary-card, user should redirect to article details page
3. Create an article-detail component to display the article details
    1. Read the article id from active Route and use article-detail api to fetch the article details from server
    2. Display the data
4. Add a feedback button on article list page, once clicked, redirect user to feedback page
    1. Feedback page will contain below fields
        1. Name as input field
        2. Feedback as text area
        3. Will you refer JugaadHai to a friend as radio button (yes, no)
        4. A button to save the data
    2. Use save-feedback api to post the form data

## Pro Tips
1. Use ReactiveFormModule for form design
2. Use HttpClientModule while making Http requests
3. Use RouterModule for adding routes

API Details can be found on below repository
https://github.com/jugaadhai/assignment-app#readme
