# Contributing to IT events

First off, thanks for taking the time to contribute!

If you want to add an event to the list, please submit a pull request. Note that list is for IT events and mostly for software development events and conferences. User group events can be added, if they are online or have a big audience. International or English events are preferred. Pull requests that don't match the topic will be rejected.

## Pull request conventions

Write the event name in the title. Modify [README.md](README.md) or [past.md](past.md) files to add the event. Please keep in mind that events need to be ordered by date and time, in ascending order for upcoming and in descending order for past events. Make sure to convert the event start time into the UTC timezone. Each line in event details needs to end with two spaces `(  )`, to be compiled to line break.

The event name is the link to the event. User group meetups have `UG:` prefix, workshops have `Workshop:` prefix, conferences have no prefix.  

### README.md event entry format

    ## [Event name](https://event-link.com/)

    :date: May 12 2020, 7:00 AM UTC  
    🇪🇺 language flag only if different from English. If event is on English, remove this line.
    :globe_with_meridians: Online - or use country flag in case of offline event  
    :free: Free or  
    :credit_card: $25
    :loudspeaker: a call for speakers link  
    :speech_balloon: Describe the event here with a sentence or two.

### past.md event entry format

This document is intended for the entry of past events that do have links to materials and event recordings.

    ## [Event name](https://event-link.com/)

    :date: May 12 2020  
    🇪🇺 language flag only if different from English. If event is on English, remove this line.
    :speech_balloon: Describe the event here with a sentence or two.
    :arrow_forward: Link to event recordings.  
