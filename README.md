# candy-appliance-card
A picture elements card for the unofficial Home Assistant Candy component, currently it only supports washing machines (smart pro series).

![alt text](https://i.imgur.com/hifGOf7.png)
![alt text](https://i.imgur.com/OLgzHlc.png)
![alt text](https://i.imgur.com/dtup1iz.png)

# Installation
1. Have the [Candy integration](https://github.com/ofalvai/home-assistant-candy) installed from HACS.
2. Copy the files from `config/www` to your HA install (create it if it doesn't exist).
3. In Lovelace, click the three dots in the top right, then select `Edit Dashboard`. Then click the three dots again and select `Manage Resources`. Click `Add Resource` in the bottom right and enter `/local/7segment.css` and set the type to `Stylesheet`.
4. Add the code from `configuration.yaml` to your HA install and restart HA.
5. Create a new picture elements card and insert the code for your appliance.

You might need to change some of the values in the picture elements card and you might have to add more icons to `config/www/candy-icons` if your appliance has additional programs for instance.

# Troubleshooting
If your image(s) don't seem to update after you replaced or changed them, try adding `?=v1` in the picture elements card after the file extension to force an update.
