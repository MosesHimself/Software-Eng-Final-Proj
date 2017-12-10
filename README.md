# Software Engineering Final Project!!
## Instaham
An Instagram clone created by our group using Swift and Firebase

## Concept
- Our idea was to recreate Instagram to practice app development.
- We wanted to utilize the Model View Controller design principle.

## Model
- The database management system we chose to use was Firebase, an expansive noSQL DB made by Google.
- Our model was to be a represented in a database using Entity Relationships.
- This can be seen [here](https://github.com/MosesHimself/Software-Eng-Final-Proj/blob/master/ERD.png) in our ERD we had created.
- Moving forward from there, we had began implementing this database inside Firebase, as can be seen [here](https://github.com/MosesHimself/Software-Eng-Final-Proj/blob/master/sampleDBformat.png)
- Connecting this database to our IOS project was quite the challenge at first.
- This was because Firebase works with IOS using CocoaPods and I (HG), have had no experience using those.
- Fortunately, I had found out that CocoaPods works using Ruby and is a Gem, which I have had some experience with.
- Using that knowledge I was able to create the pod file and add the Firebase to our project!
