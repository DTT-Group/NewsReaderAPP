# News Reader App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview
### Description
Tracks what music an individual listens to, and pairs them with others based on that music. Could be potentially used as a dating app, or just meeting new friends with similar music tastes.

### App Evaluation
- **Category:** News
- **Mobile:** This app would be primarily developed for mobile but would perhaps be just as viable on a computer, such as tinder or other similar apps. Functionality wouldn't be limited to mobile devices, however mobile version could potentially have more features.
- **Story:** Analyzes users music choices, and connects them to other users with similar choices. The user can then decide to message this person and befriend them if wanted.
- **Market:** Any individual could choose to use this app, and to keep it a safe environment, people would be organized into subscriptions.
- **Habit:** This app could be used as often or unoften as the user wanted depending on how deep their social life is, and what exactly they're looking for.


## Product Spec
### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User logs in to have access to the news
* User can sign up for a new account
* User can subscribe to news channels
* User can view Videos with audio of the current/past news
* User can get push notifications of when new news is received

**Optional Nice-to-have Stories**

* User can favorite specific news channels and order which ones will pop up first
* Most viewed news channel pops up first
* User can unsubscribe from a channel

### 2. Screen Archetypes



### 3. Navigation

**Tab Navigation** (Tab to Screen)

* News channel Selection
* Profile 
* Account info


**Flow Navigation** (Screen to Screen)

## Wireframes
![Alt Text](https://github.com/DTT-Group/NewsReaderAPP/blob/main/IMG_5717.JPG)

## Schema 
### Models
#### Post

   | Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | objectId      | String   | unique id for the user post (default field) |
   | author        | Pointer to User| image author |
   | image         | File     | image that user posts |
   | caption       | String   | image caption by author |
   | createdAt     | DateTime | date when post is created (default field) |
   
### Networking
#### List of network requests by screen
   - Home Feed Screen
      - (Read/GET) Query all posts where user is author
         ```swift
         let query = PFQuery(className:"Post")
         query.whereKey("author", equalTo: currentUser)
         query.order(byDescending: "createdAt")
         query.findObjectsInBackground { (posts: [PFObject]?, error: Error?) in
            if let error = error { 
               print(error.localizedDescription)
            } else if let posts = posts {
               print("Successfully retrieved \(posts.count) posts.")
           // TODO: Do something with posts...
            }
         }
         ```
   - Create Post Screen
      - (Create/POST) Create a new post object
   - Profile Screen
      - (Read/GET) Query logged in user object
      - (Update/PUT) Update user profile image
      
#### [OPTIONAL:] Existing API Endpoints
##### An API Of The News
- Base URL - [https://newsapi.org](
http://newsapi.org/v2/everything?q=bitcoin&from=2020-10-03&sortBy=publishedAt&apiKey=API_KEY)

   HTTP Verb | Endpoint | Description
   ----------|----------|------------
    `GET`    | /News | get all of the news
    `GET`    | /News/?name=name | return specific character by name

