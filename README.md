# Event Object

In this example, when users click on a list item, the date that the event happened on is written next to that item, along with the type of event that triggered it. To achieve this, two properties of the event object will be used: timeStamp states when the event occurred; the type states the kind of event that triggered it. To prevent the list from becoming cluttered with multiple date entries, whenever a list item is clicked, any span elements will be removed from the list.

# Components that make the app run

* Any span elements that already exist inside the li elements are removed.
* A new Date object is created, and its time is set to the time at which the event was clicked.
