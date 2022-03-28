
# Graphics Reduction Pack for FiveM
Package created to improve FiveM performance on my computer, check settings in project readme


## Features
- Temas dark e light
- Preview em tempo real
- Modo tela cheia
- Multiplataforma


## Roadmap
**v0.1 - Alpha**
```diff
    + Decreased range of police sirens reflex in 20%;
```
**v0.2 - Alpha**
```diff
    + Removed the distance from the reflection of police sirens;
    + Removed 40% of light emission from stationary objects;
```
**v0.3 - Alpha**
```diff
    + Removed specular light from the sun and moon;
    + Reduced the distance the shadow of objects will be rendered by 40%;
    + Reduced shadow opacity by 85% (in GTAV's normal setting)
```
**v0.4 - Alpha**
```diff
    + Completely removed smoke from tires during burnout;
    + Decreased 90% blood splatter multiplier during combat;
    + Removed bullet marks on walls (if you want to keep it, delete the files "decals_cs.dat" and "decals.dat"
```
**v0.5 - Beta**
```diff
    + Light emission by objects fixed at 75%;
    + Decreased range of police sirens reflex by 70%;
    + Removed more 45% of light emission from stationary objects;
    + Reduced in 10% exhaust smoke from the vehicle when stationary (if you want to return to the original, delete the files "vehicles.meta");
    + Removed unnecessary lens flare effects (if you want to return to the original, delete the files "lensflare_f.xml", "lensflare_m.xml" and "lensflare_t.xml");
```
## Screenshots
![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## Installation
### **Basic Installation**
- Extract the pack files to a folder on your desktop;
- Completely clear your FiveM cache (script attached);
- Make a complete backup of your FiveM's `citizen` folder in the `%LocalAppData%\FiveM\FiveM.app\` folder;
- Make a backup of the `fivem.cfg` file in the `%AppData%\FRoaming\CitizenFX\` folder;
- Make a backup of the `gta5_settings.xml` file in the `%AppData%\FRoaming\CitizenFX\` folder;
- Open the `gta5_settings.xml` file and write down in a notepad the value of line #72 - `VideoCardDescription`;
- Open the `%AppData%\FRoaming\CitizenFX\` folder and replace the `gta5_settings.xml` file with the modified one;
- Edit the `gta5_settings.xml` file with the information saved in step #45;
- Open the `%AppData%\FRoaming\CitizenFX\` folder and replace the `fivem.cfg` file with the modified one;
- Completely delete the original `citizen` folder from your FiveM and move the present one in the package;
- Move the `a_CATUSSE_Package_VisualOptimisation_NG.rpf` file to the `%LocalAppData%\FiveM\FiveM.app\mods\` folder

### **Complementary Installation**
***Note: The following modifications are personal, and may have different performance on each computer, it is recommended that you back up your computer before running the files.***

- **Disable Power Throttling**: Creates a new power plan "forcing" your computer to run FiveM with maximum processing power;
- **Increase CPU Performance**: Activates game mode and sets games to run at maximum priority on your computer, overriding other programs;
- **Increase System Resposiveness**: Disables Moderate Network Speed ​​input so you can stop losing some packets (reduces PL) during gameplay;
- **KeyBoard Optimization**: Enables the Keyboard Class Driver in Windows 10, a kernel device driver capable of reducing the keyboard response time by a few milliseconds (if the computer uses > PS/2 inputs);
- **Mouse Optimization**: Enables the Mouse Class Driver in Windows 10, a kernel device driver capable of reducing mouse response time by a few milliseconds (if the computer uses PS/2 inputs);
## Credits to Creators
Todas as modificações presentes nesse pacote foram retirados da internet (principalmente de sites estrangeiros) e editados por mim durante longas semanas; caso decida compartilhar em outro site, dê os créditos e informe o link original deste repositório.

```diff
+ Rockstar Games, Inc: Do I need to say anything?
+ LMF' Tah FiveM: Package Visual Optimisation
+ Nevek: Editor de Registro do Windows
```
## Suport
Any problem with crash or loss of FPS, contact me by Ticket on the channel's [Discord](https://discord.gg/qCF9AbFDq5).

## Licence
[MIT](https://github.com/ricardo-codes/Graphics-Reduction-Pack-for-FiveM/blob/183aa1e35f59bc11f9df9c434236a02c26d77e81/LICENSE)

