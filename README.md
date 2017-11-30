# OneUp Database Project

### What is OneUp?

OneUp is a web application that aims to create a space where young skateboard talent can surface up democratically, powered by those who know and love skating. The app is centered around a database of user-uploaded skate videos that are curated by upvotes and downvotes from other users. Skaters are constantly aiming to get sponsored while building their personal brand, and Oneup can make this process more efficient. Besides serving the committed skater, anyone who simply enjoys watching skate videos will have a place to watch the top clips and have a say in which video/skater should be noticed.

OneUp Web Application (in development): https://github.com/abdulazizasiri/OneUp

### Database Project Goal

The purpose of this database project is to display how we store user-added information about the user and the videos they upload.

To implement this database, we intend to use MongoDB for querying skate clips and user information, creating schemas specific to our needs, updating data, and deleting data.

### Data Dictionary

#### User Collection

  - User ID
      - A unique ID to reference a user. This will be stored as an integer.
  - Username
      - The username of the user. This will be stored as a string.
  - Name
      - The name of the user. This will be stored as a string.
  - Email
      - The user’s email address. This will be stored as a string.
  - Password
      - The user’s password. This will be stored as a string.
  - Bio
      - The user’s bio that includes information such as current sponsors, achievements, accolades or anything the user would like to share. This will be stored as a string.
  - Social Media Links
      - A list of the user’s social media accounts. This will be stored as a string.

#### Video Clip Collection

  - Clip ID
      - A unique ID that references a clip. This will be stored as an integer
  - Clip
      - The video clip file.
  - Title
      - The title of the video clip. This will be stored as a string.
  - Description
      - A description of the video clip. This will be stored as a string.
  - Uploader 
      - The user that uploaded the clip. This will be stored as a string.
  - Upvotes 
      - The number of upvotes that the clip has received. This will be stored as an integer.


### Demonstration

1) Creating an Account- Storing Information

2) Signing In- Querying Information

3) Settings- Updating Information

4) Uploading Video- Storing Video Link and Information

5) Signing In with different users


