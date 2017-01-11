---
layout: default
title: Room Meetings
menu: Room Meetings
permalink: roomMeetings
---


# Room Meetings

Periodically SOCVR will have room-wide meetings where we discuss room policies and behavior. 

Anyone can propose new topics to be discussed by creating an issue in the GitHub repository [here](https://github.com/SO-Close-Vote-Reviewers/SO-Close-Vote-Reviewers.github.io/issues). The issues will be labeled with `room-meeting-suggested-topic`. 

When there are enough topics the RO team will announce a new date for an roommeeting. The topics that will be on the agenda get labelled with the actual roommeetig like `room-meeting-2017-01`. The regulars are then invited to vote and comment on the topics so anyone can prepare for the meeting.

The meeting will be held in the room [SOCVR Room Meetings](https://chat.stackoverflow.com/rooms/108179/socvr-room-meetings). Do notice that this room will be unlocked 30 minutes before the start of the meeting. You don't need (and urge you to not try it either) to request access.

During the meeting one of the RO's will chair the meeting. After we reached a conclusion on a topic, the resolution is documented and after the meeting published.

Here you'll find  the resolutions and transcript of previous meetings:

{% for post in site.posts %}
  {% if post.categories contains "meetings" %}
[**{{ post.title }}**]({{ post.url }} )   
  {% endif %}
{% endfor %} 

