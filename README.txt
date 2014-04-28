RMPBS-Google_Calendar
=====================
Created by Sarah Dudley, Mercy Interactive, Inc.
2/2014

1. Description
2. Usage
3. Requirements


DESCRIPTION
===========
RMPBS-Google_Calendar integrates with Google Calendar to display a navigable calendar with highlighted dates and a list of upcoming events. The snippet defaults to displaying upcoming events for the month and, for the first load, will forward to the next month if no events are on the calendar for the rest of the month. Clicking on a highlighted date will display the event data for that date. Scrolling through the months on the calendar will display events for the given month. Designed for use as a right rail snippet, but could be modified easily.

USAGE
=====
Include all necessary scripts (in Requirements) in the head of the page. Copy and paste RMPBS-Google_Calendar.html into a smart snippet making sure that all variables are created properly - there should be four. Insert snippet at the desired location and populate all required variables (calendar_id, API_key)

REQUIREMENTS
============
Jquery 1.9+
JQueryUI 1.10
Google Calendar API key (obtain through Google's Developer Console: https://console.developers.google.com/ )

Additionally a jQuery UI skin can be added to easily adjust the look of the calendar. Create a custom skin here: http://jqueryui.com/themeroller/