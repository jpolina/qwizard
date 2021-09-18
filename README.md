# Voiceflow Study Helper

This voiceflow project takes in the questions and answers that you want to study, and then quizzes you on them. You can chat with your project via the terminal.

## Documentation

For additional information about the Voiceflow API, visit the [documentation](https://www.voiceflow.com/api/dialog-manager).

## Setup

1. If you do not have node, install _Node.js_ and _npm_ from [nodejs.org](https://nodejs.org/), or follow an equivalent guide.
2. In this folder, run `npm install`.
3. Replace `'process.env.API_KEY'` in `index.js` with your API Key.
   You can find them under the integrations tab:

   <img src="https://user-images.githubusercontent.com/5643574/129422436-04d964d3-85a0-402d-ae5e-d6e84723da5e.png" width=800 />

4. run `npm start` to start your chat!

## Example

What it might look like in action:

```
$ npm start

> What is your name?: Jonathan
...
Welcome back to the study guide. To begin, say the first question you want to study.
> Say something: In what year did World War II end?
...
Enter the answer to this question.
> Say something: 1945
...
To add another question, enter the question. Otherwise, if you are ready to start the test, say 'Start'.
> Say something: What is 4+3?
...
Enter the answer to this question.
> Say something: 7
...
To add another question, enter the question. Otherwise, if you are ready to start the test, say 'Start'.
> Say something: What is the color of grass?
...
Enter the answer to this question.
> Say something: green
...
To add another question, enter the question. Otherwise, if you are ready to start the test, say 'Start'.
> Say something: start
...
Your first question is:
What is the color of grass? 
> Say something: red
...
Wrong. The answer is: green. 1 out of 3 completed.
Here's your next question
What is 4+3? 
> Say something: 7
...
Correct!
2 out of 3 completed
Here's your next question
In what year did World War II end? 
> Say something: 1945
...
Correct!
3 out of 3 completed
We've now come to the end of the exam. 
For your final score, you answered 2 out of 3 questions correctly. If you want to run through the exam again, just say "try again". 
> Say something: exit
...
The end! Start me again with `npm start`
```
