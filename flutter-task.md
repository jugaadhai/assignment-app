# Flutter Task Details
1. Create a flutter app named `flutter-jugaadhai-task-yourname` (ex: `flutter-jugaadhai-tak-jitangupta`)
2. On Home Screen display the list of articles
    1. Use article-list api to fetch list of articles 
    2. Create an article-summary-card to display the list of articles If you need any design inspiration, you can visit jugaadhai.in and see
    3. On click of article-summary-card, user should redirect to article details screen
3. Create an article-detail screen to display the article details
    1. Read the article id from parameter and use article-detail api to fetch the article details from server
    2. Display the data
4. Add two options in bottom navigation bar as articles and feedback
    1. Clicking on articles button user should redirect to articles screen
    2. Clicking on feedback button user should redirect to feedback screen
5. Feedback screen design
    1. Feedback page will contain below fields
        1. Name as input field
        2. Feedback as text area
        3. Will you refer JugaadHai to a friend as radio button (yes, no)
        4. A button to save the data
    2. Use save-feedback api to post the form data
  
### Pro Tips
1. To make http requests use https://pub.dev/packages/http
2. To display HTML content in flutter use https://pub.dev/packages/flutter_html

API Details can be found on below path
https://github.com/jugaadhai/assignment-app#readme
