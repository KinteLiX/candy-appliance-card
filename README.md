# candy-appliance-card
A picture elements card for the unofficial Home Assistant Candy component, currently it only supports washing machines.
![alt text](https://i.imgur.com/V0iSZmj.png)
![alt text](https://i.imgur.com/37a9yIx.png)

# Installation
1. Have the [Candy integration](https://github.com/ofalvai/home-assistant-candy) installed from HACS.
2. Copy the files from config/www/candy-icons to your HA install.
3. Add the code from configuration.yaml to your HA install and restart HA.
4. Create a new picture elements card and insert the code for your appliance.

You might need to change some of the values in the picture elements card and you might have to add more icons to config/www/candy-icons if your appliance has additional programs for instance.

# Troubleshooting
If your image(s) don't seem to update, try adding "?=v1" after the image extension to force an update.
