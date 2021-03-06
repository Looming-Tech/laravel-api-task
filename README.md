# REST API to serve/edit calendar events

The purpose of this component is to enable web based clients to manage calendar events (aka meetings).

A meeting consists of: 
- owner
- start time
- end time
- name
- meeting room

Two meetings can't be placed in the same room at the same time.

The API should allow for:
- list all meetings an user (owner) has for a particular day
- list all meetings an user (owner) has ever had
- create new meeting

The API specification is for the candidate to decide but it should follow the REST architectural style. Please provide basic documentation of it so we can test. Please provide steps to run or deploy it on the internet.
The implementation should be done with PHP and the Laravel framework.

For simplicity you could assume there is only one meeting owner (user).

Bonus points:
- add basic authentication
- use Swagger for specification
- add update and delete meeting methods
