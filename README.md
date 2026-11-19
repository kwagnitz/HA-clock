<h1>HA-clock</h1>
<b>Code for a HA clock dashboard.</b>

This is code for a Home Assistant dashboard displaying a clock with extra info on it.<br>
It is intended for use in the bedroom, displayed on a tablet.
(I have it on a 10" tablet on a wardrobe at the end of the bed.)

The layout is in HTML for flexibility.
The display dims at low light level, as provided by a weatherstation.  It could be done by time of day.

The following items need to be added from HA Marketplace:
* Kiosk Mode - gets rid of extraneous items like headers.
* Blackout theme - makes the background truly black, not grey.
* HTML Template card - displays HTML & CSS, with Jinja2 templating.

The easiest way to add a clock dashboard to your HA, is to
* create a dashboard
* open it, click on <em>Edit dashboard</em>, then <em>Raw configuration editor</em>
* paste the code into the editor window, ovewriting what was there
* save it.

I added user 'Clock', for displaying the clock dashboard.  For that user, the header is hidden.<br>
(Note: That dashboard can not then be edited by user 'Clock'.)

If you don't have the weatherstation I have, change the items to suit what you do have, or add other stuff.
