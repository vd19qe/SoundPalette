**Date: Tuesday March 31**

**Time: 5:00pm - 7:30pm**

**Location: Microsoft Teams**

## Agenda 
- [x] Catch up with everyone's progress
- [x] Discuss goals for the next week
- [x] Address any current bugs/issues

## Attendance
- [x] Parth Chauhan
- [x] Victoria Danh
- [x] Prab Khokhar
- [x] Kaija Sproxton
- [x] William White
- [x] James Windjack
- [ ] Brendan Park
- [ ] Naser Ezzati-Jivan

## Sprint 6 Responsbilities
| Sprint # | Name               | Responsbility                                       |
|----------| ------------------ | ----------------------------------------------------|
| Sprint 5 | Parth              | Software Testing and Planning                       |
| Sprint 5 | Victoria           | Group Chat and Editing/Previewing a Post            |
| Sprint 5 | Kaija              | Improve overall UI                                  |
| Sprint 5 | Prab               | Improve overall UI                                  |
| Sprint 5 | Will               | Algorithm for Posts and Notifications               |
| Sprint 5 | James              | Tagging a User in Post, Notifications, Exploring S3 |

## General Notes
- A few minor connections issues were addressed and corrected
- Discussed bugs that have been found and attempted to fix them as a group
- Walked through some of the changes made
- Briefly discussed the last Sprint meeting and final presentation

## Bugs to Fix
- **ProfileViewFragment**
  1. Crashes when you select the "Profile" or "Search" options from bottom navigation bar
  2. Crashes when you select "MESSAGE" button for a user who you do you already have a message with (failed x2 then passed x1 without any code change, could be a stack or pathway issue?)

- **CommentAdapter**
  1. When user clicks on the profile picture in a comment, it should go to the user's ProfileViewFragment but instead crashes
    - Note: The same code is used in PostAdapter and ChatMessageAdapter and seem to be working correctly

- **MessageFragment**
  1. Crashes when you select the "Profile" or "Search" options from bottom navigation bar

- **ChatroomFragment**
  1. Crashes when you select the "Profile" or "Search" options from bottom navigation bar

## Goals for Sprint 6 Review
- Profile pictures from S3
- Group chat
- Previewing a post capabilities (when creating)
- Editing a post capabilities (caption, and tags)

## To Do
- Ability for a user to stay logged in
- Ability to tag another user in a post
