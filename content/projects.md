---
title: "Projects"
date: 2018-05-11T18:51:14-07:00
weight: 20
draft: false
---

### Some of the projects I've done lately..

#### Arduino Incubator [<span class="icon fa-github"></span>](https://github.com/tgray-projects/incubator)
Uses a temperature sensor and a relay to turn on/off a lightbulb to control the temperature in a homemade duck egg incubator.  Intitially it had connections for an exhaust fan and an air circulation fan, but they proved to be unneeded.
{{< figure class="image main" src="/images/duck.jpg" >}}

#### Makerspace Front Door [<span class="icon fa-github"></span>](https://github.com/prmakerspace/prms-door)
Built a RFID-based door system for the local Makerspace.  A python script reads the member number off of the RFID card and compares it to a local database of active members.  A successful match opens the front door by turning a servo attached to the deadbolt.  The database is updated nightly from our membership site via a cron job and the site's API.

#### Oil Switch [<span class="icon fa-github"></span>](https://github.com/tgray-projects/oil-switch)
Simple arduino sketch to turn a physical oil line valve off when the current to the system fan is turned off by the thermostat.  Current is detected via an analog non-invasive current sensor and, when the current is on, the system turns a servo that will be attached to an oil furnace feed valve.  Because the final installation was done by another (non-technical) party, the system had to be flexible as to mounting points and flexibility, so standard 1/8" stereo jacks were used for all connections (so off the shelf extensions could be used, if needed).  Additionally, because this controls the heat for a greenhouse, and heat loss would cause catastrophic damage during the Canadian winter, fully redundant parts were delivered in case of failure.

#### Puppet [<span class="icon fa-github"></span>](https://github.com/tgray-projects/puppetmasters "Backend.") [<span class="icon fa-github"></span>](https://github.com/tgray-projects/BC-Tech-Summit-B.F.G.R.P "User interface.")
Designed and led a team to build a control system to allow the audience to control the largest humanoid marionette in North America from their mobile devices, shown at the BC Technology Summit in March 2017.  The project used a captive portal built on a router using DDWRT to serve a control system running on a Raspberry Pi.  Requests were routed to a backend Pi which interfaced with the motor controllers that moved the puppets limbs.

{{< figure class="image main" src="/images/puppet.jpg" >}}