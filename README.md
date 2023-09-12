# Filametrix Mod
# Important
As the Stealthburner has been revised the "motor plate" doesn't fit anymore. I've uploaded the motor plate you need to use for filametrix.

This is a mod of the Voron Stealthburner which adds a filament cutting possibility!

![Image](https://user-images.githubusercontent.com/83211473/235375660-0192f0ec-643e-4637-aa77-7b43cf537856.png)
![image](https://github.com/sorted01/Filametrix/assets/83211473/0ce0be5b-109b-4fe7-905f-fe22846c1f3a)

## Update
### Main Body
#### Main Body with Filamentsensor Option has been added.
- SB_CW2_Main_Body_Cutting_with_2xD2F_ECAS
- SB_CW2_Main_Body_Cutting_with_D2F_ECAS
- SB_CS2_Main_Body_EBB_ECAS_D2F "CW2 main body for the ERCF w/ ECAs, bearing switch, and SB2209 Canbus mods" Thanks to [juliusjj25](https://github.com/juliusjj25)

#### Support for LGX Lite
https://www.printables.com/de/model/576122-lgx-lite-stealthburner-filament-cutter

tommorox234 has created the main body for the LGX Lite. Feel free to get in contact with him via printables.
Thank you :)

### Printhead
#### Update for Bambu Hotend has been added.
#### Known Issue: It seems that the parts are separated. As i did not design them I cannot update them. Sorry!
- SB_Bambu_cutting_Printhead_back
- SB_Bambu_cutting_Printhead_front or SB_Bambu_cutting_Printhead_front_2
- Bambu_Adapter

Thanks to "Jakub Kadlec" from Facebook :) 

#### Update for Voron Revo Hotend 
- SB_RevoVoron_back
- SB_RevoVoron_front

by Russell Gower - NOTE currently untested!!

#### Update for Rapido Hotend

- see folder

say thank you to [juliusjj25](https://github.com/juliusjj25)  :) 


## Motivation
I was looking at the ERCF MMU for several month now. What always kept me from starting the project were the discussions about issues and problems with  filament tip forming. Suddenly a new company showed us how they do it quite reliable. They just cut the filament. Further motivated and inspired by the design of @pure100kim who has built the [ERCF_Filament_Cutting_MOD](https://github.com/pure100kim/ERCF_Filament_Cutting_MOD) I started to build my own version of it.

## See how it works


Proof of concept 1: https://youtube.com/shorts/HOMG8cVk_U4

Proof of concept 2: https://youtu.be/tTcrxttyths

Filametrix in action: https://www.youtube.com/watch?v=tfMZWQRqtvY

## Good to know

Please be aware:

**!! THIS IS A WORK IN PROGRESS !!**

- This is my very first repository on GitHub. Please be paitend with me :D - Any hints are welcome!
- We will need to use one of the ADXL mounting threads
- Depending on the setup and position of the cutting point we will most probably not lose any build volume
- For the main body i remixed the ECAS version from [Alexanderor](https://www.printables.com/de/model/433797-clockwork-2-ecas-fitting-for-ercf)

## What you need
### Print list
#### Toolhead
- 1x SB (hotend name) cutting Printhead back
- 1x SB (hotend name) cutting Printhead front
- 1x SB Main body Cutting with ECAS (or with sensor)
- 1x SB motor plate (as Stealthburner has seen a small update the newest plate does not fit anymore. So please use the one from this git)
- 1x SB latch ECAS
- 1x Cutting arm
- 1x Knife holder

#### Cutting point on gantry
- 1x depressor mount
- 1x depressor

### Parts list - considering you already have a Stealthburner with Dragon Hotend

#### Toolhead: 
- Loctite
- 1x M3 nut (DIN934; ideally a countersunk tool to modify the nut for proper filament insertion)
- 2x M3 washer (0.5mm)
- 1x M3x18 SHCS (it repleaces the top left M3x25 SHCS from the SB-Cover mount) 
- 2x Voron heat inserts
- 1x M3x18 FHCS (counter sunk screw)
- 1x M3x8 SHCS
- 1x M2.5x16 SHCS (15-18mm works)
- Spring of ballpoint pen (L=15mm; D<=4,5mm) (I've ordered some for testing, to have a "defined" spring)
- Type 4 metal hobby blades (we will cut it to length) [Link](https://de.aliexpress.com/item/1005005117830095.html?spm=a2g0o.order_detail.order_detail_item.9.47c26368QwSbBr&gatewayAdapt=glo2deu) Amazon link, these need glue to be held in but work fine (USA) [Link](https://www.amazon.com/dp/B07QP8L1QG)
- ![Image](https://user-images.githubusercontent.com/83211473/235373488-2253e51a-6892-4dc9-9b53-363d28b1faa8.png)

#### Cutting point on gantry
- 1x M3x16 BHCS
- 1x M3 nut
- 1x M3x8 FHCS
- 2x M3 SHCS (Lengths: 6mm - no backers, 10mm - titanium backers, 12mm - MGN9 rails)
- 2x Voron heat inserts

## Assembly
### Cutting arm
#### Cut skalpel to length l=26mm
![image](https://github.com/sorted01/Filametrix/assets/83211473/c17c3605-2184-4c45-986b-4da3b65add38)
##### Result
![image](https://github.com/sorted01/Filametrix/assets/83211473/62f5fb5d-31df-4c98-a9ee-5afadb0f73e9)
#### Insert skalpel into knife holder
Insert the skalpel (which is cut to 26mm) into the knife holder until you see it in the little hole. Use pliers to push it into the knife holder. Some force should be needed as the skalpel should stay in place due to the "pressfit". If that's not the case add some glue.(Depelding on skalpel tolerances)
![image](https://github.com/sorted01/Filametrix/assets/83211473/b46f8143-e8a0-459e-af59-e8ae7ef47191)
#### Put knife holder into cutting arm
The M2.5x15 screw is directly screwed into the plastic of the knife holder. The tip of the screw should be flush with the cutting arm or no more than 0.1-0.3mm above it.
Check the orientation of the hole for the M2.5 screw in the knife holder. It needs to be on the bottom side.

**!! The knife holder must move up and down without friction in the cutting arm but shoult not have a lot play. Maybe some grinding is needed. !!**

![image](https://github.com/sorted01/Filametrix/assets/83211473/bbaa3ada-9219-41d7-b9d6-3e1e33d68f22)
![image](https://github.com/sorted01/Filametrix/assets/83211473/120f79e6-e4fa-4f14-8aaa-b15671ae2da4)




### Add heat inserts

Tip here for the heat set that goes above the cutter I would suggest drilling the threads out with a ~2.5mm drill bit. On the hotend holder side below the cutter make sure you flare out the PTFE tube to help guide the filament.
#### Main body
![image](https://github.com/sorted01/Filametrix/assets/83211473/8324c808-83cd-4b8d-a89a-45ca6b4836d8)
#### SB cutting Printhead back
![image](https://github.com/sorted01/Filametrix/assets/83211473/e7a5901d-e755-4ad7-a55a-b15f54218cdb)
#### Depressor - one on either end, end with ribs should be flush with surface below ribs with no plastic sticking up past surface
![image](https://github.com/juliusjj25/Filametrix/assets/118471600/652e0256-451f-44c3-a2ec-b7ecb967395c)

#### Finished cutting point assembly should look like this
Note: for titanium backers, the backer should be centered between belt clamps and the end of the depressor mount should be flush with the end of the backer. This will work for all backers with 10/20/40mm spacing with the furthest back hole 5-15mm from the end. Height of depressor should be adjusted to press in the depression on the cutting arm and the BHCS can be adjusted in and out for the right positioning and locked in place with the M3 nut.
![261054978-7247e729-06e5-4cba-a8ad-aafa2b9bd7a1](https://github.com/juliusjj25/Filametrix/assets/118471600/d08debd0-4a2d-4288-916e-c076feb9d45b)

I need some time to finalize assembly instructions. If you have questions you'll find me in discord "sorted#8941"

## Code

***The code only works with https://github.com/moggieuk/Happy-Hare** If you haven't updated yet you really should.

Copy mmu_additional.cfg to your printer config directory mmu/base/ and include it in your printer.cfg below all of the mmu includes via [include mmu/base/mmu_additional.cfg]

You will need to adjust the parameters in mmu_addtional as well, like setting up your cutter location, speeds, etc. More information in the cfg file itself.




