# Software Engineering Final Project!!
## Instaham
An Instagram clone created by our group using Swift and Firebase
- Group Members:
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
### Timeline: October 9th - October 27th
- The first sprint we had to begin the design process.
- As a group we had decided to recreate Instagram, as it is an app we all were familiar with.
- The stories we created were basic and general, but we eventually broke them down into smaller bits.
- The biggest challenge here was doing things that were new to us.
- For example we needed to learn how Firebase worked to even begin using it.
- On the contrary, creating the concept for our model was no challenge as we had done this many times before in previous classes.
## Sprint 2
### Timeline: October 30th - November 10th
- The second sprint was the most progressive for our group by far.
- We were able to implement a lot of things we had set up in the previous sprint, namely the Firebase.
- Once we were able to get the database part of Firebase up and running, we had a lot more to work with.
- We had figured out which format we would want to use for our database that would be most fitting for our app.
- This sprint was when we started playing around with github and we had to learn how to use it.
## Sprint 3
### Timeline: November 13th - November 24th
- There were tons of difficulties during this sprint due to Thanksgiving break.
- Communication definitely broke down due to traveling and various other school assignments took priority over project work at the time.
- We had to leave two stories/epics in the product backlog, brainstorming the controller and developing the view.
- We did complete the design for our view, seen above in the View section.
## Sprint 4
### Timeline: November 27th - December 11th
- Upon return from Thanksgiving break we had a lot that needed to get done.
- We had finally began implementing our view in xcode and our project started to really take shape.
## Conclusion
- Looking back, we had picked way too large of a project for the amount of people we had in our group.
- Deciding to use a new language for most of our group was a bold decision and ended up complicating things substantially.
- Although we may not have completed every goal we had on the software and development side of things, we had definitely learned a ton about the scrum process.
- It became much easier as a group to follow the process as time went on and we gained more experience together.
