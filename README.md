# Software Engineering Final Project!!
## Instaham
An Instagram clone created by our group using Swift and Firebase
Group Members:
## Concept
- Our idea was to recreate Instagram to practice app development.
- We wanted to utilize the Model View Controller design principle.

## Model
- The database management system we chose to use was Firebase, an expansive noSQL DB made by Google.
- Our model was to be represented in a database using Entity Relationships.
- This can be seen [here](https://github.com/MosesHimself/Software-Eng-Final-Proj/blob/master/ERD.png) in our ERD we had created.
- Essentially, each user would have an array of posts that each have an array of comments.
- Moving forward from there, we had began implementing this database inside Firebase, as can be seen [here](https://github.com/MosesHimself/Software-Eng-Final-Proj/blob/master/sampleDBformat.png)
- Connecting this database to our IOS project was quite the challenge at first.
- This was because Firebase works with IOS using CocoaPods and I (HG), have had no experience using those.
- Fortunately, I had found out that CocoaPods works using Ruby and is a Gem, which I have had some experience with.
- Using that knowledge I was able to create the pod file and add the Firebase to our project!


## View
- The view is definitely the most simple part of the application in terms of work and thought needed
- The original Instagram app layout would make the most sense to use.
- We decided to have three different scenes that a user would be able to see.
- Our diagrams we created can be seen [here](https://github.com/MosesHimself/Software-Eng-Final-Proj/blob/master/ViewDesign.png)
- The main scene would be a user's "Timeline", where all of the new posts of the users they follow would be displayed
- This would go in chronological order from when the posts had been created
- The post scene has duplicated features so we combined the Timeline and Post scenes, making the Timeline a list of Posts.
- The Profile scene would not differ much from the Instagram app, as it seems there is not much to improve on.

## Controller
- With our group having very little experience with Swift, we decided to develop this part last.
- Unfortunately due to time constraints we had not gotten to complete this part of the design for our app.

# Scrum/Kanban Process
- [Here is a link to our environment](https://docs.google.com/spreadsheets/d/1bvLWHnr4DOBnJgx6yxXo4vlfA3YVRor0wbPGG8gUI-k/edit?usp=sharing)
- Unfortunately we had not for-seen the trial ending for our SmartSheet 30 days after we had started it.
- [Here](https://github.com/MosesHimself/Software-Eng-Final-Proj/blob/master/SmartSheetEmail.png) is the email they had sent me.
- Since we could not export the data as they had claimed, we had to transfer our Kanban board over to a Google Spreadsheet last minute.
## Daily Scrum Meetings
- Tuesdays and Thursday we met before class and just talked about what we did the day prior, what we will do that day, and any troubles
- Wednesday and Friday we met during the day, had a similar scrum meeting as specified above, and additionally had an hour or so of group work

## Sprint 1
- The first sprint we had to begin the design process.
- As a group we had decided to recreate Instagram, as it is an app we all were familiar with.
- The stories we created were basic and general, but we eventually broke them down into smaller bits.
- The biggest challenge here was doing things that were new to us.
- For example we needed to learn how Firebase worked to even begin using it.
- On the contrary, creating the concept for our model was no challenge as we had done this many times before in previous classes.
## Sprint 2

## Sprint 3

## Sprint 4
