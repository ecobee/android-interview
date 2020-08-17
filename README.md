Android take home question
===

We're looking to see how you would write code in our real application. Feel free to use the internets however you like, this includes using any libraries you like.
What we are looking for is someone who writes code with good separation of concerns and high test coverage. Despite this application being small we want to see how
you would write scalable code as if this was a large project.
 
Requirements:
- Hardcode username and password into static strings
- Build login page which has two EditTexts and a button
- First EditText shows hint username
- Second EditText shows hint password, input mode shouldn't show characters(ie. *******)
- Button says Login
- Clicking button will read text from both EditTexts and compare with the hardcoded values in a background task
- When validation fails display a dialog with title "Login Failed" and an ok button
- Pressing ok clears the password
- When validation succeeds open a new screen with a button to load random cat images from http://thecatapi.com/, this part is up to you how you want it to look, behave
- Time is limited and the expectation isn't that you will complete everything, just that what is done is of high quality.
