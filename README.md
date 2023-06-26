# Wheel Support (FiveM Plugin)
This client-side plugin for FiveM will allow you to utilize any steering wheel controller as well as
custom settings for a specific vehicle type. 

## 📗Installation
1. Rightclick:  FiveM
2. Click: Open file path
3. Go into the `FiveM ApplicationData`
![image](https://user-images.githubusercontent.com/60815764/153277781-cddad2fe-1c06-4628-a6b1-9b9534087934.png)
4. Create a `plugins` folder, maybe you already have the folder
5. Put the `ManualTransmission` and the `Gears.asi` inside the `/plugins` folder.
- _Steps to be taken by developers:_
6. Open the `server.cfg`
7. Navigate to:
```
# This allows players to use scripthook-based plugins such as the legacy Lambda Menu.
# Set this to 1 to allow scripthook. Do note that this does _not_ guarantee players won't be able to use external plugins.
sv_scriptHookAllowed 0
````
8. Change
```sv_scriptHookAllowed 0``` to ```sv_scriptHookAllowed 1```
**⚠️Please be mindful with setting this variable. It is always recommended to use an anti-cheat mod for FiveM server hosting. **

### ⚙️Setitngs
All settings can be found in the `ManualTransmission`.

## ⭐CREDITS
```
Nano11Bravo            Development
Impulse99 Community    Testing
ZeroFour               Reupload
```
