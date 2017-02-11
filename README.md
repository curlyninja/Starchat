# Starchat
Web based chat application.

Goal: Web based secure messaging system.

## Key goals:
* Ability to create account
  - Ask email and password. Maybe username.
  - Confirmation email.
* Ability to invite friends 
  - Send contact request (Through email)
  - Ability to friend and un-friend.
* See list of contacts.
* Ability to sent text messages to friends
  - Click on contact name, see last sent messages
* Store last messages
* Ability to view text messages from friends
* Real names aren't asked, emails are private. 

## Stretch goals:
* Attach images to text messages.
* Group based chat.
* Emojis, profile picture.
* Message timeouts.
* Clearing of message logs.

## Architecture:
* HTTP --> Python --> DataBase

## Entities:
* User
   - User Id
   - Username
   - Email
   - Create-time
   - Last login
* Friend Relation
   - User ID
   - Friend-user-ID
   - Create-time
* Message
   - From user ID
   - To user ID
   - Message text
   - Create-time
   - Sent/Delivered
   - Read/Notread
* Contact request
   - User ID (1)
   - Email
   - Message
   - Create time
* CREATE ER


