## Agenda week 8

Date: 2 April
Time: 13:45
Location: Drebbelweg
Chair: Kaan
Minute Taker: Emiel
Attendees:  6 + TA

### Updates from last week / announcements (~7 minutes)
- Opening by chair (1 min)
- Project Pitch(1 min)
- Missing Requirements Implemented
  (WebSocket, Long Polling, Admin, Settings, Language, Shortcuts)(5min)


### Talking Points (~24min)
- Check on everyone about any development problems last week.(4 min)
- Discuss about the merge request "Second part of Admin Functionality" by Leo(3 min) 
- Testing still needs a work. Difficulties for testing each page and interactions between them.(5 min)
- Missing Requirements both Basic and Other(7 min)
- We should be able to edit the title of an event(1min)
- Tag functionality needs to be implemented.(1 min)
- Adding Statistic Page.(1 min)
- Styling the client side of app (Not getting into too deep but at least screen size can adapt to different devices)(2 min)

### Finishing up (~5min)
- Goals for the upcoming week (3 min)
- Minute taker reads notes (2 min)
- Any questions, discussion with TA

Total time: 36 minutes

### Notes
- Confirmed that the late uploading of the presentation wasn't a problem.
- Confirmed that web socket communication doesn't need to be used for sending client data to the server.
- Discussed how participants should be added to an event by the owner of the event, decided that we should keep adding participants manually so that "ghost" participants can be created.
- Decided that we don't need to restrict editing participants to the owner of the event.
- Talked about the css styling and whether the application should be responsive, decided that we need to keep a uniform styling throughout the entire application and that we won't be doing full responsive design.
- Agreed on that everyone should test their own javafx controllers
- Talked about how we're going to implement indirect output tests.
- Talked about the HCI assignment, and how we're going to pass the multi-modality part of it.
- Discussed what should happen when a user wants to delete a participant that has debt entities related to them, decided that the server should not allow this.
- Discussd what features still need to be implemented before the end of next week. These include:
  - Change the last activity field of an event when a user changes some data.
  - Implementing the expense tags
  - Implement the expense statistics
  - Fix bugs including joining event with invite code not working, and debts not being created.