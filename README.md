# MudScheduler
Trying to make a Team Scheduler App from MuBlazor Components

Dates across the top, and grouped data down the left side (support rtl maybe too)

Maybe include to reverse it so the dates are on the left/right and the group data is along the top.

Useful for looking a multiple people's entries at the same time.

Something like this
![image](https://github.com/Gareth064/MudScheduler/assets/22307223/2a32d1b6-12ba-4769-bf7b-a1445167bac3)

In the example (screenshot) above probably isn't something you'd achieve in a MudScheduler Component, unless you guys think otherwise.
This is its structure and behaviour.

**Structure**

- **Sidebar** with "People"
- **Top bar** with dates
- **Centre section** with events

**Behaviour**

- The top bar, with Dates, and the Centre section have a virtualize infinite horizontal scroll, loading in the next\previous months' worth of data (from server) as it comes into view.
- The centre section is one big, massive drop zone where you can not only move events between days on the person they are associated, but also drag them onto another person.
- Events can be dragged from the edges to expand/shrink which updates their duration

Video of the type of scrolling/navigation that would be great to figure out how to do.

https://user-images.githubusercontent.com/22307223/196027100-ddb04da4-114b-4877-a6f6-bd0b10037ac9.mp4
