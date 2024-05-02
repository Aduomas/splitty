## Agenda week 3

Date: 27 Feb \
Time: 13:45 \
Location: Drebbelweg \
Chair: Adomas \
Minute Taker: Leo \
Attendees:  6 + TA

### Updates from last week / announcements (~16 minutes)
- Opening by chair (1 min)
- Code Of Conduct review (5 min)
- Weekly review of achievements related to assignment. Individual assesment of each others work (10 min)

### Talking Points (~25min)
- Merge requests (5 min)
- - Merge Request Owners
- - Approving/Closing
- Considerations about what endpoints, services will we need on server-side (5 min)
- - Looking at template implementations (3min)
- Discussion on  mock up examples and/or additional pages (5 min)
- Creating relevant issues in gitlab for discussed topics (5 min)
- Checkstyle configuration agreement (2 min)
### Finishing up (~5min)
 - Goals for the upcoming week (3 min)
 - Minute taker reads notes (2 min)
 - Any questions, discussion with TA

Total time: 45 minutes
**Notes**
- Code of conduct seems to be complete, we will meet on Thursday to discuss it and submit.
- All of the merge requests regarding the schema were sucessfuly closed. We are on track
- If somebody opens their merge request, exactly this person should merge it. избежать miscommunication
- After submitting Code of Conduct, this week we create issues for each of the basic requirements and implementing the server side of all the basic controllers
- All of us agree on the checkstyle
- We decide to write javadoc only when it's necessary
- Controller, Service, Repository
- We need to have at least one test for each endpoint
- We'll probably use Mockito for it
- We test all of the exceptions and then we test that it was added
- For a good grade we focus on doing 80% test coverage for functional classes(entities, controllers, jpa classes). In general it's better to test as much as possible.
- We must not do bad tests (such as overlapping tests or something similar)
- It's better to do boundary testings then just focusing on test coverage

Tasks for this week:
- creating an event (Adomas)
- joining an event (Adomas)
- change title event (Leo)
- delete event (Leo)
- get event by id (Adomas)
- remove (participant) from event (Leo)
- expire the inviteCode (generate new) (Nikola)
- creating expense (requires title, payer, participants, amount) (Nikola)
- getting expense (Nikola)
- deleting expense (Kaan)
- changing expense details (title, amount, participants) (Kaan)
- get total participant debt (Emiel)
- get all debts in event (Emiel)
- create new transfer (requires from, to, amount, message) (Jordan)
- mark transfer as approved (only transfer receiver should be allow to mark it as approved) (Jordan)
- update bank account, name, email (Adomas)