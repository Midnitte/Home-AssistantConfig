# Home-AssistantConfig
Configuration for my Home Assistant.

I currently have a Raspberry Pi B3+, Smartthings Hub (along with several lights and buttons), chromecasts, and Google Homes.

My goal is to automate things that get in the way, but also allow things to be physically controlled when needed.

WIP.


## Automations
Here are some examples of the automations I use which print notifications for me in Discord.

![AMA Alerts](ReadmeImages/amaalert.png?raw=true)

This automation prints out the name of the next AMA from the AMA subreddit, as well as the time and description. It is also currently a WIP because it only prints one AMA (so if there are multiple in a day, or multiple at a time, only one is printed).

![NWS Alerts](ReadmeImages/NWSalert.png?raw=true)

This automation prints out any alerts for my zone from the National Weather Service. This relies upon the ![Weather Alerts](https://github.com/custom-components/weatheralerts) custom component.

![Pollen Alert](ReadmeImages/pollenalert.png?raw=true)

This automation gives an alert in the morning whenever the pollen count via IQVIA is a 6 or above.

![Rain Alert](ReadmeImages/rainalert.png?raw=true)

This just gives an alert whenever the current forecast changes to rain, with a limit on how frequently it triggers.

![Temp Alert](ReadmeImages/tempalert.png?raw=true)

This triggers an alert when the temperature in the bedroom is above or below certain temperatures at 8pm (to give us time to adjust the temperature before going to bed).

![Travel Time](ReadmeImages/traveltimealert.png?raw=true)
![Chris Time](ReadmeImages/christimealert.png?raw=true)

These automations give a notification about travel time, either in minutes, or estimated time of arrival. I also @ mention the person it's most relevant too.
