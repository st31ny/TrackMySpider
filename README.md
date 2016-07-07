# TrackMySpider
Log abitrary events with key strokes

## Function
TrackMySpider allows users to make a time protocol of key strokes which can be used as proxy for anything. Simply hit a previously defined key in order to record the current time and the event code and description associated with this event.

To run TrackMySpider all you need is a modern web browser -- no internet needed. When you are ready to start the session, just hit "Start" at the bottom of the page. Now, all events in the top navigation bar(s) are active. There are two different kind of events:

1. Simple Events: by hitting the associated key you generate a single entry in the event log with end and begin time being equal to the current time.
2. Latch Events: by htting the associated key for the first time, an entry in the event log is created with the begin time being equal to the current time. The end time is left open until you hit the same event key again. The time when the latter happens is recorded then. Afterwards, the event is in its initial state again. The can be arbitrarily many different latch events be active at the same time.

When you are done with the entire event log, hit save to open a window with a CSV export of the event table to copy in insert into your favourit spreadsheet software.

By the way, all fields in the event log can be edited on the fly. When an input field gets the focus, all event keys are disabled, so you can type without triggering any events. When you are done, just click anywhere or hit "Return" to have the input field lose its focus and trigger events again.

## Change events

To change event keys, codes and descriptions, just edit the "index.html" file. Right in the beginning you'll find a commented JavaScript table with all you need to add, remove or edit event keys.
