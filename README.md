# Boop

An app to manage book groups

- Should have social login
- We can get inspiration on [Meetup](meetup.com) or on [confy.app](confy.app)
- Should be able to create and select through multiple books

**Reading book group**

- Groups should have a name, a description, a calendar, and a book list
- Should be able to select multiple books and vote on the one we're going to read until next meeting.
- Admin's can set the next meeting date, when a meeting is booked, every group participant should be notified (email? push notification? whatsapp message? Don't know yet)
- As group participant, I can write notes about what I wish to talk/discuss on the meeting, and I can configure the permission to show/hide it from all the other participants.
- As group participant I want to add the meeting event to my agenda (google agenda, apple calendar)
- As a group admin, I should be able to share a invite link to the reading group (on social media)
- As user I can enter groups through links or through the app interface.
- As admin I wish to share invite links to my reading group on social media
- As a group participant, I may not participate a meeting (because I didn't want to read this specific book, or because I'm in a lack of time) so I wish to select which meetings I'm going, and the ones I'm not
- As mediator, I want to be able to select a limit point on the book to discuss.
- As mediator, I wish to reschedule the meeting and notify every user that has accepted to go to this particular meeting.

**User**

- A user should have a name, a e-mail or phone and may have a picture, a prefered theme list, a calendar to match groups.
- As user I wish to find a reading book group based on location (online being a valid location), theme or on the time range I select.
- As user I wish to create a reading book group

# MVP - Boop

- User crud
- Group crud
- Select a mediator to the group
- Add meetings to the booking group
- Everytime you add a meeting you have to add the book specification
- Google agenda integration
- E-mail notification

book specification

- Name
- Author
- Theme
- Sinopsis
- Year?
- Publisher?
