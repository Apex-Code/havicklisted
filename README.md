# README
*******HAVICKLISTED*******
 
 This app is a part of the #14in14.  A challenge to build 14 Ruby on Rails apps in 14 days.  After the challenge, there will be a #14in14revamped in which all apps will gain added functionality, and those that are worthy will be deployed.  This Readme will be updated as the app progresses.
 
 *******Users*******
  
 [X] Will have a password
 
 [X] Will have an email
 
 [X] Will have a session unique to them
 
 *******Forum*******
 
 [X]  Users will be able to edit posts
 
 [X]  Users can comment other posts
 
 [X]  Users can edit and delete comments
 
 [X]  Users CANNOT edit or delete someone else's comment
 
 [X]  Users CANNOT edit or delete someone else's forum post
 
 *************************

 Challenges that were faced were: *********************

 If a user deleted a post with comments, a 500 error occurred.  To solve this I implemented a @message.comments.clear inside the messages controller destroy method.  (Success!)

 Remembering to authenticate user before most actions, except index and show.

*******************Ideas for #14in14revamped*************

[]  Add number of views rating for posts

[]  Style change

[]  Let number of views determine Message order

[]  Not to give up.  Ever.