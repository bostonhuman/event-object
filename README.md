# Event Object

In this example, when users click on a list item, the date that the event happened on is written next to that item, along with the type of event that triggered it. To achieve this, two properties of the event object will be used: timeStamp states when the event occurred; the type states the kind of event that triggered it. To prevent the list from becoming cluttered with multiple date entries, whenever a list item is clicked, any span elements will be removed from the list.

# Components that make the app run

* Any span elements that already exist inside the li elements are removed.
* A new Date object is created, and its time is set to the time at which the event was clicked.
* The time the event was clicked is then converted into a date that can be read.
* The date that the list item was clicked is written into the list item along with the type of event that was used. Note that the timeStamp property does not display in Firefox.

## How to run the app?
* In your terminal:
```
git clone https://github.com/bostonhuman/event-object
```
* Open `event-object.html` to run the app.
