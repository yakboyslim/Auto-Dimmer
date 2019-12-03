# Auto-Dimmer
Auto set dimmer levels to match outdoor conditions. Parent and child app both required.

Multiple child apps could be made to create different illuminance versus level curves for different dimmers, or for different modes.

Interpolates between dimmer settings for dark, dusk, overcast, and sunny conditions to find a level to set. Always sets dimmers to this level when they are first turned on. Will set dimmers to new values as the illuminance changes if the option is selected. If dimmer level is manually set the app will not update as illuminance changes, however it will set the level the  next time the dimmer is turned off and back on.
