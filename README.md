# milk-and-chocolate-HA-theme
This Home assistant theme should fit into traditional homes with a lot of wood on the walls.
Most dark themes (ios or google) are on the gray side, which this theme still keeps, but it shifts a little into the dark chocolate side. 

## How to use / install the theme
Due the fact that i'm new to git, i'm very sorry to not be able to offer you a more fancy methode than :
1. create a folder named "themes" in the config folder
2. add this lines to your configuration.yaml

~~~~
frontend:
  themes: !include_dir_merge_named themes
~~~~

3. clone this git with terminal into the themes folder 
~~~~
cd config
cd themes
git clone https://github.com/dschaga/milk-and-chocolate-HA-theme
~~~~ 
This will create a folder "milk-and-chocolate-HA-theme" into the themes folder.

4. restart HA 

5. Go into your user and look into the themes list 


## why it looks like it looks like 
### The dark "chocolate" mode
Basicaly it's a dark theme with a slightly shift into brown and with orange accents. Mostly this "brown shift" comes from the text color and from the base background gradient. 
The Theme was created in winter during the heating season and while there was mostly artifical lighting and or the light of a fireplace. At that time this theme feels just right.



![screen2](https://user-images.githubusercontent.com/176213/178560318-41fc16ad-9733-4201-b87b-44c6d515a833.PNG)
![screen1a](https://user-images.githubusercontent.com/176213/178559537-48f87bdf-026e-4500-86ec-198e2cbddd95.PNG)
![screen3a](https://user-images.githubusercontent.com/176213/178560120-c0c684bf-31e3-4657-9edc-e88eef52cb37.PNG)

### The bright "milk" mode
The bright mode is an experiment with bright gradients, which is quite challenging, because the base color should not go into a gray and if it does this, then the gradient should help "recovering" the brightness of the theme.

![screen2b](https://user-images.githubusercontent.com/176213/178560339-1a110201-4b65-4e67-ad1f-f8b2745845a0.PNG)
![screen1ab](https://user-images.githubusercontent.com/176213/178560202-42cc3e3a-19f7-4e7c-b0dd-c1ac4c006251.PNG)
![screen3ab](https://user-images.githubusercontent.com/176213/178560076-eaa63778-6c09-4c9a-b785-06fdd33af9ae.PNG)
