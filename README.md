# coding-events
#purpose
This application tracks events around different locations and offers details about them
#state
The User is able to add events to the application, and attach tags to the events
#future improvements
We need to add a person class in order to have our users to select and save their favorite events

Proposed Architecture 
person class

fields:
name-string
email-string
password-string
list of events-List<Event> : Many to Many relationship
favorite category-EventCategory : Many(many people can have the same favorite category) to One(because a person can only have one favorite)

Methods:
Getters and Setters
Get back favorite events(return all events that have to do with favorite category)
