# Code Nation Fellowship 2 Unit 2 Project - Jeopardy

Students will implement a Jeopardy game.

Below is the recommended order in which to complete the project.

## Day 1 - Rendering

### render_categories.js

[x]1. Note the `categories` array at the top of the file. These are the category headers.
[x]2. Follow the instructions in the file and write code where it reads `// Add code here`

3. The output should be:

![render_categories.js](https://i.imgur.com/l6J9OCh.png)

### render_questions.js

[x]1. Note the `numCategories` and `questionValues` variables at the top of the file.
[x]2. Follow the instructions in the file and write code where it reads `// Add code here`

3. The output should be:

![render_questions](https://i.imgur.com/rpPcTHD.png)

## Day 2 - Helper functions

### click_handlers.js

1. Students and volunteers should take a minute to read the instructions.

   1. There is a lot of code in this file and students are asked to carefully append it.

2. Follow the instructions and write code where it reads `// Add code here`

3. If done correctly, the following should be true:

   1. Each question block is clickable
   2. On-click renders a popup like so:

   ![onclick](https://i.imgur.com/lUb4wOp.png)

   3. Clicking "Show Answer" will show the answer like so:

   ![answer](https://i.imgur.com/bhvRj4s.png)

   4. Clicking "Close" will hide the modal and remove the question from the board like so:

   ![closed](https://i.imgur.com/IBIyhrJ.png)

## Day 3 - Scoring

### scoring.js

1. Follow the instructions in the file and write code where it reads `// Add code here`

2. If done correctly, the following should be true:

   1. On launching, there is a new "Current Score: 0" div at the bottom of the board like so:

   ![current_score](https://i.imgur.com/MJltSPC.png)

   2. After clicking on a question, then clicking "Show Answer", the player is presented with an option to select "Correct" or "Wrong".

   ![correct_or_wrong](https://i.imgur.com/7YPhGSv.png)

   3. If the player chooses "Correct", the score is updated to reflect the added amount.

   ![correct](https://i.imgur.com/AEAw7tL.png)

   4. Ensure that choosing "Wrong" subtracts the amount instead.

## Extra Credit

1. Attempt the bonuses.
2. Improve the styling.
