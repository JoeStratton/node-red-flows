# Node Red Home Assistant Flows
<b>Required:</b><br> 
- <a href="https://flows.nodered.org/node/node-red-contrib-home-assistant-websocket">Home Assistant Websocket Plugin</a>

<b>Automations:</b><br>
<b>Presence Notifier</b><br>
- Uses the Pushover API and Amazon Alexa to notify different areas of the housee/phones who is home and leaving

<b>Night Lights</b><br>
- Turns on ktichen lights when the sun is down and the back patio sliding door is opened, but only if the tv is off
- Turn on and off lights in home theater when movies start and stop at night
- Turn on and off night lights around the house based upon the position of the sun, not time

<b>Battery Notifier</b><br>
- Notifies homeowner when smart locks/smart hardware is low on battery via pushover api and alexa voice

<b>Party Mode</b><br>
- Limits the volume of certain speakers around the house if someone is trying to sleep

<b>Media</b><br>
- Controls Theater Music/Movies/Lights via series of Nvidia Shield API calls, Telnet commands to a projector, Music Cast API calls (Yamaha)
- Controls Living Room Music/Movies/Lights in multiple zones and runs active checks to confirm settings

<b>Startup</b><br>
- Detects when home assistant is online and sets the theme for all users on the backend on startup

<b>Doors and Lights</b><br>
- Check various doors and notify household if they are left open
- If Pantry door is opened, turn on light, close after 2 min of no door activity
- Notify household if outdoor fan is left on for more than 2 hours
- Power Chandelier from 1-100 brightness when someone opens front door
- Close Garage after left open for 45 minutes and notify users via Pushover/Alexa notification
