# Lab 4 - *Flashcard app*

Submitted by: **Michael West**

**Flashcard app** Building a flashcard app to grasp SwiftUI fundamentals.
       Date: 10/7/24 |
      University: Florida Atlantic University |

Time spent: **5-6** hours spent in total


## Required Features

The following **required** functionality is completed:

- [ x ] View a flashcard and toggle between the card's question and answer text
- [ x ] Understand the effects of swiping left or right by updating the cards color as the user swipes
- [ x ] Swipe left and right to progress though the deck
- [ x ] Reset the deck with all the cards or only cards they've categorized as needing more practice
- [ x ] Create new flashcards and add them to the deck
 

## Video Walkthrough

  <div>
    <a href="https://www.loom.com/share/812d6e8271974857b59324dfaab7847c">
    </a>
    <a href="https://www.loom.com/share/812d6e8271974857b59324dfaab7847c">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/812d6e8271974857b59324dfaab7847c-cf5605e6fbd42fd8-full-play.gif">
    </a>
  </div>

# Describe any challenges encountered while building the app.
The issues I had with this lab were around step 5 when I added a State property and updated the value of an offset modifier added to the CardView. The preview wasn't working and the project was unable to run due to code crashing. I quickly found out that it was an issue with the struct and type errors with the #preview code line at the bottom of the code.
