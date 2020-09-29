---
title: "The FarmBot Web App"
slug: "the-farmbot-web-app"
excerpt: "Step-by-step instructions for setting up the FarmBot Web App"
---

* toc
{:toc}

The [Farmbot Web App](https://github.com/FarmBot/farmbot-web-app) is a cloud based web service that performs the following functions:

 * Storage of device info and calibration settings
 * Real time manual control of a FarmBot from a web browser via Meshblu
 * Creation of sequences of events
 * Scheduling of recurring sequences of events (irrigation, seeding, etc...)
 * Coming soon: creation of regimens (plant-age-based scheduling of sequences of events)
 * Coming soon: drag and drop interface for farm/garden design
 * Coming soon: crop and sensor data storage and management

You can host the web application yourself on your own servers, or use the [My FarmBot](http://my.farmbot.cc) service. Below, we talk about how to do both.

# Create an account on my.farmbot.cc

1. Go to [my.farmbot.cc](http://my.farmbot.cc)
2. Click 'Register'
3. Enter a username, email, and password. Click 'Register'
4. Check your email and follow the link to confirm your account (coming soon)
5. Once you are logged into the application, you will be prompted to enter in device credentials. You can do this from the 'Devices' page.
6. Enter the name, UUID, and security token for your FarmBot and click 'Add FarmBot'. You can get the UUID and security token from the terminal screen when farmbot.rb first starts up.
7. You may need to refresh the web application for the settings to take effect

{%
include callout.html
type="success"
title="You're all setup!"
content="Now you can begin creating sequences and scheduling them to run whenever you want. Just press the synchronize button to update your FarmBot!"
%}



# Provisioning the FarmBot Web App (advanced)



{%
include callout.html
type="warning"
title="For advanced users only"
content="This step is intended for expert users and software developers who wish to run the FarmBot Web App on their own servers. Nontechnical users are encouraged to use the [My Farmbot Service](http://my.farmbot.cc)."
%}

Please see the official README for the web app source code here: https://github.com/FarmBot/farmbot-web-app/blob/master/README.md
