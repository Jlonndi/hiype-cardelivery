# FiveM car delivery script

FiveM resource for servers with QbCore Framework.

Start a mission for a car delivery, steal the car, drive it to the destination, profit.<br>
Pretty simple so far, further updates coming soon.

**Development still in progress**

## Features

- Payout based on vehicle condition (Engine, Body)
- Cooldown between each taken job
- Vehicles spawn either parked or driving around (Soon)
- Very basic rank system, nothing changes yet
- **Planned some time**: Rank system with better cars spawning the more xp you get.

## Requirements

- [QbCore framework](https://github.com/qbcore-framework)
- Could be more soon...

## Setup

1. Download or clone this repository inside your resources folder
2. Remove the "-main" part from folder name
3. Add a line to your server.cfg file -> **ensure hiype-cardelivery**
4. Add a line inside [qb] -> qb-core -> server -> player.lua
   <br>**PlayerData.metadata['cardeliveryxp'] = PlayerData.metadata['cardeliveryxp'] or 0**
   <br>An example image can be found at the bottom of this section
5. If your server is running, remember to either restart your server or do **/refresh** and also **/start hiype-cardelivery**

![Enter this line](https://i.imgur.com/hae5hLd.png)

## Instructions

To start the job, go to the location seen on the map below.

![Map](https://i.imgur.com/4xeQvGS.png)

Once there, go next to the NPC and press E key on your keyboard to start the job. An objective will automatically show up.

![Job start location](https://i.imgur.com/b4coTdR.png)

Follow the objective, use any lockpick to open the car and hotwire if necessary.<br>
Drive to the destination. Beware, if the car is destroyed, job will **fail**!<br>
Once you arrive at the destination, stop the car inside the objective blip on mini map. Job will finish and you will get paid depending on distance driven and condition of the car.

## Support

If you wish to support me in any way, you can do so through this link -> [Streamelements donos](https://streamelements.com/therealhiype/tip)<br>
This link will redirect you to a Streamelements donation page which shows the donation on my twitch stream if I'm live<br>
P.S Im rarely live and this was just easier to do
