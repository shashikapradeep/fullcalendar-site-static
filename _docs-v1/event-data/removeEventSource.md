---
title: removeEventSource
type: method
since_version: 1.2
---

Dynamically removes an event source.

<div class='spec' markdown='1'>
.fullCalendar( 'removeEventSource', *source* )
</div>

Events from the source will immediately be removed from the calendar.

Since version 1.5, the `source` parameter has become rather relaxed.
You can provide an event source's Array/URL/Function
**or** you can specify the full [Event Source Object](event-source-object).

Prior to version 1.5, things were more strict.
You must specify a reference to the original Array/URL/Function.
