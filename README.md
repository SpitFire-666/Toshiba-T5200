# TOSHIBA T5200 

## Info, mods, pics, tips etc

![image](https://user-images.githubusercontent.com/38451588/185399025-eac09d79-5327-4b18-9074-843dcfde0991.png)


# Models

| Model | Type | Comment |
|-|-|-|
|PA8054U | T5200C or T5200/200 (200MB HDD) model | |
|PA8052U | Plasma, 100MB | |
| PA8052EA | Plasma, 100MB | No search results on google for this but it definitely exists (I have one!)| 
|PA8050U | Plasma, 40MB | |
| PA8050E | Plasma, ?? | | 


 ## T5200 vs T5200C - differences

- Both machines are identical except for the display assembly (and LCD/PDP converter). The displays *should* be swappable (but has anyone ever tried??)

| T5200 | T5200C | Part | Comment | 
|--|--|--|--|
| |![image](https://user-images.githubusercontent.com/38451588/181877108-0104f558-dc73-42d0-9287-ee75f2173bf8.png) | Display | Color LCD has 2 dials instead of one | 
| |![image](https://user-images.githubusercontent.com/38451588/181877133-93c7b40a-34be-439e-bfcb-f7e96a32a70b.png) | Display | T5200C display is more matte than the plasma |
| ![image](https://user-images.githubusercontent.com/38451588/183250781-ca9b7102-303c-4637-8970-930b2092a015.png) | ![image](https://user-images.githubusercontent.com/38451588/181877833-a95827aa-a50f-4874-9c5b-3b6e909c87cd.png) | Display/lid | Lid is fatter on the T5200C |
| | | LCD display is smaller than the plasma (10.4" vs 11.5") |

# 📖 Maintenance Manual

http://www.minuszerodegrees.net/manuals/Toshiba/Other/Toshiba%20T5200%20-%20Maintenance%20Manual.pdf

# 🔌 Power Supply
P/N: 5200-0010 

![image](https://user-images.githubusercontent.com/38451588/129731104-cbda1bd7-740c-4aaa-bf04-e68c6f322636.png)

![image](https://user-images.githubusercontent.com/38451588/129731131-282254ee-aae3-4a3a-9ddc-ed9c00d45409.png)

### Components

PC001, PC002: 0N3105


# BIOS

### Accessing the BIOS

- Hold down Esc while powering on the system to force an error, then hit F1
- Alternatively, launch TEST3.EXE from MS-DOS

## BIOS Variants

- Note the "05" up top right, and the ability to choose plasma font set on the other variant!

![image](https://user-images.githubusercontent.com/38451588/185271619-3f36e793-05b0-4c88-9b9b-1366cb0da993.png)

![image](https://user-images.githubusercontent.com/38451588/185385205-52e3ffdf-55d4-4bd5-9bd3-9847bbb68ee7.png)

![image](https://user-images.githubusercontent.com/38451588/185744681-1524ec4d-1187-4b85-a13e-b440e8a9f7df.png)


### BIOS chip

- Chip could be from AMD or Texas Instruments

![image](https://user-images.githubusercontent.com/38451588/129731323-b3285d0e-eee0-4757-96bb-07222fd3d0ee.png)


### 🔋 CMOS Battery

- I replaced mine with a 3V CR2032 battery (with battery holder) and diode (if you're worried about the machine trying to "charge" the battery).

![image](https://user-images.githubusercontent.com/38451588/161382229-b83a9a8d-d6e0-43c4-9f30-7ca61384752a.png)



# Memory (RAM)

- 1MB of RAM is soldered on the RAM board - the system will run just fine with no SIMMs installed
- 6x 40-pin SIMM slots (proprietary and impossible to find 😥) and 1x 30-pin parity slot (optional)
- Apparently a maximum of 16MB is supported (but I've only seen up to 14MB)
- SIMMs appear to be the same type as used in the Toshiba T8500 desktop PC and Acer 735C
- You can skip the RAM check/count on boot by hitting SPACE 


### Memory board

![image](https://user-images.githubusercontent.com/38451588/185402032-e8fe3137-5acd-4901-8e2b-b715a50acbb9.png)


![image](https://user-images.githubusercontent.com/38451588/130006005-8cf8ff80-3ef5-4474-afec-e8a421e00806.png)

 
### SIMM variants

Front and back of 4 different modules:

![image](https://user-images.githubusercontent.com/38451588/141056903-9fdc0ed4-73e3-4f66-aff3-88474bef04b4.png)
![image](https://user-images.githubusercontent.com/38451588/141056919-16e454e6-6690-42c8-8613-7935e063f799.png)

Others I've seen online:

![image](https://user-images.githubusercontent.com/38451588/185403433-7197f463-343b-4376-bf4c-a01e34e71e9d.png)


![image](https://user-images.githubusercontent.com/38451588/185402205-056ac3da-8973-4e6d-b86f-312dd36a154c.png)


![image](https://user-images.githubusercontent.com/38451588/131814713-3a018a9b-c1a4-4653-b876-926c3b7e0334.png)


## RAM Mod

 Here are details on a mod to add 8MB of RAM using a standard 72 pin 8MB Parity SIMM. (Requires at least 2MB of proprietary SIMMs already fitted) 

 Use this info at your own risk, don't blame me if you damage your T5200! 


https://www.vogons.org/viewtopic.php?f=46&t=57998&start=20 

https://www.vogons.org/download/file.php?id=45121&mode=view 

You might be able to use a 16 bit ISA memory expansion board for memory below 16MB but that might not work and would be very slow even if it did. 

Each pair of SIMM slots has a single label on the component side so there are 6 slots but only 3 labels (IS17, IS16 & IS15 - ignoring the short 30 pin slot). The middle pair is IS16 and one slot I have referenced as "A" and the other as "B" although they are not labelled 


Web links: 

https://www.iclocator.com/rfq.html/-5405EDC5-0471-4E05-9AC9-37B072077022?pagename=rfq&e=33oueXFqWRA 
 

https://old.pinouts.ru/Memory/simm_40pin_pinout.shtml 

https://forum.vcfed.org/index.php?threads/creating-a-bmp-image-thats-viewable-in-windows-3-1.66758/


# Motherboard/Mainboard

![image](https://user-images.githubusercontent.com/38451588/141057266-ca2b497e-8d77-43d9-920a-48ec93dd3af8.png)


# CPU

- 132-pin PGA Intel i386 DX @ 20MHz

![image](https://user-images.githubusercontent.com/38451588/185403793-f91672fe-9466-47cb-8adf-be334536970a.png)


## CPU Upgrades

You can fit a 33Mhz or 40Mhz upgrade CPU in the T5200, it will just run at 20Mhz unless the CPU has built in clock doubling. The hardware mods improve the performance of some of the upgrade CPUs but aren't essential and the CPUs will work if you plug them in without any mods albeit with reduced performance. 


| Brand | Model | Comment | SysInfo benchmark score (higher is better) |
|-|-|-|-|
| Intel | i386 DX @20MHz | Stock CPU | 21.2  | 
| Texas Instruments | TXI486DLC/E-33GA |
| Texas Instruments | TX486DLC-40BGA| 
| Texas Instruments | TX486DLC-40GA | (Note, installs sideways) |  23.9 |
| Texas Instruments | TI486DLC/E40BGA | |
| Cyrix | Cx486DRx2 20/40GPL |
| Texas Instruments | SXL2-50 | | 32.1 (stock, 54.3 using custom BIOS that allows it to run at 40MHz https://www.vogons.org/viewtopic.php?f=46&t=57998#p643529 |
| Cyrix | Cx486DLC | |



![image](https://user-images.githubusercontent.com/38451588/183288996-dbf6525b-7abb-47fb-8191-681df5cbc53f.png)

 
# Math Co-Processor

- Optional i387

![image](https://user-images.githubusercontent.com/38451588/185405977-28094708-244f-4633-bd59-abbc8a3af4e5.png)


# Hard Disk Drive (HDD)

- BIOS only supports 3 types of Conner drives, available in 40MB, 100MB and 200MB (rarer) capacities

- Replacement drive must match one of the 3 approved conner HDDs - it must match the CHS setting in the BIOS and its model number must start with CP (Conner Peripherals).
 

| Pic | Make | Model | Capacity | Seek time (ms)|
|-|-|-|-|-|
|![image](https://user-images.githubusercontent.com/38451588/151661736-462e5589-0b63-4672-a2bb-90371464784b.png) | Conner | CP-344/CP-3044 | 40MB ||
| ![image](https://user-images.githubusercontent.com/38451588/138080146-abbab5ef-eec3-4edc-b8d1-839683fb0211.png) | Conner | CP-3104 | 100MB ||
| ![image](https://user-images.githubusercontent.com/38451588/183248769-1afba90b-a025-490d-8ca9-b6845b05c673.png) | Conner | CP-3204F | 200MB || 



## HDD upgrades/mods

### XT-IDE option

- An ISA card with IDE connector/SD card slot/CF card slot

![image](https://user-images.githubusercontent.com/38451588/160276380-2011e3bd-5cda-4115-9b6d-9a595bb18bc0.png)

https://conventionalmemories.com/wiki_cm/CF_adapter_for_Toshiba_portables

https://conventionalmemories.com/wiki_cm/3inONEder_for_Toshiba_portables

https://texelec.com/product/lo-tech-xt-cf-lite-rev-2/

- Set the IO_ADDR to 300H
- Prepare a CF card (install MS-DOS in VirtualBox, convert the VDI to .IMG, use Win32DiskImager to write to the CF card

Options:
- fire up the T5200 and go in to the BIOS setup and see what hard drive options you have - write them down - and buy a matching Conner CP series IDE drive.
- write the AT version of XTIDE to a boot ROM and configure it in a network card, set the T5200 to no hard drive, and install any generic IDE hard drive.
- find another Conner IDE drive and ask someone on here to hack the ROM, then burn the new ROM and replace the one on your motherboard (or maybe get away with drive overlay software)

 Drive Overlay software is a program that sits in the boot sector and reconfigures the drive before DOS starts.
 

# 💾 Floppy Disk Drive (FDD)

- 26-pin (non-standard) FDD connector, which carries data + power
- These drives are prone to failure, and rarely work anymore
- ℹRecommend the floppy drive mod below which involves hacking a ribbon cable to allow a standard 34-pin floppy (or Gotek USB floppy emulator) to work

| Pic | Make | Model | Note |
| - | -|-|-|
| ![image](https://user-images.githubusercontent.com/38451588/161383043-07148ab2-8b76-42a8-8b69-4e238dd3f42e.png) | Toshiba | ND-356S-A | | 
| | Citizen | 0SDA-32C | |


## Floppy mod

How-to: https://www.vogons.org/viewtopic.php?p=642629#p642629

Gotek USB floppy emulator (pictured):

![image](https://user-images.githubusercontent.com/38451588/161382983-5f1f4f1e-ca1a-4908-b109-7556b260759d.png)

- Adapters like this may also work:

https://floppyemulator.com/products/34-26-pin-flat-cable-adaptor/

![image](https://user-images.githubusercontent.com/38451588/150640288-59cf68aa-cac1-4da7-9a77-56a8377ee057.png)


# Display

## 🟧 Orange Gas Plasma Display (T5200, T5200/100, T5200/200) 


- Display Area: 9.1"W x 6.8"H; 11.5"  

- Model: Panasonic MD480T640PG3

- diagonal Resolution: 640 x 480 

- Gray scales: 16 Contrast: 100 : 1 

- 34 pin plug 

- T5200 and T3200SX have the same displays, VGA 640x480, 16 shades of intensity. 

### VGA / Video Card / HRGS

- Board: FH3HR4 / FH3HR3

![image](https://user-images.githubusercontent.com/38451588/138082616-0a46b4bf-1432-4946-92b2-cd6db4440687.png)

- Capacitors C2 and C4 are 16v 47uF and do not appear to be related to the plasma display
- C2 does not appear to be related to the plasma display (maybe it's for the VGA port?)
- R127 and R134 (SMD resistors on rear) do not appear to be related to the plasma display

- "You dont really need a video driver for your Paradise PVGA1 (?) because these Toshiba models do have - although indeed having one of the first Paradise SVGA compatible chipsets - only 256kb of video RAM, iirc. which means youre limited to a max of 640x480x16 at max, if I am not mistaken."


## I/O card

- System will NOT POST without this card present

- Display will NOT power on without this card present

- System will emit 4 short beeps and 2 long beeps if card is not installed

![image](https://user-images.githubusercontent.com/38451588/138082561-74206daf-6a7a-4af4-8532-e851730fa627.png)


# 🔐 Combination Lock

# Fans / Cooling

- 3x 4cm x 2cm 12v dumb fans

# ISA slots
 - One 16-bit (top)
 - One 8-bit (bottom)

# Rear Expansion Slot

- Connection is ISA but in a non-standard layout
- Often unpopulated, but modems were the most common expansion. I've also seen parallel ports.
- The interface connector for the mainboard is made by KEL and 3m makes compatible connectors as well. Part numbers: KEL 8801-060-170L-F or 3M P50-060S-RR1-EA 

| Image | Expansion card | Comment |
|-|-|-|
 | ![image](https://user-images.githubusercontent.com/38451588/159207603-7dcc1a33-68be-425c-9f1a-b8186de08296.png) | Modem | MultiTech MT224TL   2400/1200/300-BPS, INTERNAL CARD MODEM FOR TOSHIBA T3100, T3100/20 & T5100 COMPUTERS |
| ![image](https://user-images.githubusercontent.com/38451588/183251788-dd848e97-bbee-481f-85a4-bac94d44a8db.png) | Toshiba Expansion box connector | |
| ![image](https://user-images.githubusercontent.com/38451588/166194285-94945955-994a-4e25-9a60-614c29131673.png) | Expansion box card ? | |
| ![image](https://user-images.githubusercontent.com/38451588/183807329-98d5fe1e-9f39-43be-a451-fe66d80401e9.png) | ConventionalMemories' 3inOneder card | An XT-IDE card that replaces the HDD with a CF card, includes a soundcard and gameport (https://old.reddit.com/r/retrobattlestations/comments/n8ilxg/all_the_features_my_toshiba_was_missing_on_one/) |
| ![image](https://user-images.githubusercontent.com/38451588/185272409-c709a88d-09d0-45aa-aa4e-4a1100b25992.png) | LAN card | | 
| ![image](https://user-images.githubusercontent.com/38451588/185744770-1d88f1a8-ad14-4935-803e-19d718c33864.png) | CF XT-IDE card | by ConventionalMemories |
| ![image](https://user-images.githubusercontent.com/38451588/224875165-c8197a92-cf1d-4948-aea0-54d3bb9902b1.png) | Modem | Holmes Microsystems Inc |
| ![image](https://github.com/SpitFire-666/Toshiba-T5200/assets/38451588/3858ac23-4540-4666-9d55-6a50023b4282) | Arctic Systems SynPhonix speech synthesizer | |


Modem

![image](https://user-images.githubusercontent.com/38451588/185271896-0c77e701-f674-4bf0-a2d9-1c472af21384.png)


### Issues 
there is a single line vertical artifact on screen.  

Quite often in these screens this may be a "cold solder" ( https://en.wikipedia.org/wiki/Soldering#Electronics ). You can try to check these "fat" solders on top of the screen - every now and then one of them can be repaired. 

# Capacitors

## Converter board (plasma)

| Number | Voltage | Capacitance |
|-|-|-|
|C00|? |? |
|C202| ? | ? |
|?| 250V| ?|
| ? |25v | 100uF |

## Converter board (Colour LCD - T5200C)

| Number | Voltage | Capacitance |
|-|-|-|
| C2| 25v | 22uF |
|C17 | 10v | 1000uF|
|C1 | 35v | 330uF |
| C14| 35v | 330uF |
|C6 | 25v| 820uF|


## Plasma display board

| Number | Voltage | Capacitance |
|-|-|-|
| C2 | 250v |3.3uF |
|C6|?|?|
|C7|?|?|
|C9| 16v| 47uF|
|C10|?|?|
| C15| 16v | 47uF | 
| C32 | 16v | 47uF |
| C36 | 250v |3.3uF |
|C37| 250v | 1uF |
| C38 | 250v | 1uF |


## VGA (HGRS) card FH3HR4
| Number | Voltage | Capacitance |
|-|-|-|
|C2|||
|C4|||

## Motherboard

| Number | Voltage | Capacitance |
|-|-|-|
|C1|||
|C2|||
|C11|||
|C299|||
|C12|||

## Power Supply


# Software

|-|-|-|
|name | details | other |
| LXPic | | lxpic /c /g8 /y |



# Media appearances

- Toshiba ad, 1990, Australia:

https://www.youtube.com/watch?v=PPWLVBK-W3Y

- An ad featuring the T5200 amongst a lot of women's legs 

https://www.youtube.com/watch?v=3rmI2FAk5Ic


# FAQs

## What's the max resolution (external monitor)?

## How does the A/B/PRT switch work?

## How to change combination lock code?

1. 

## Why are many games/MS-DOS "letterboxed", leaving the top and bottom of the screen unused?

## Can you use another video card?

Yes, you can plug in any ISA video card (not sure if this disables the plasma/onboard VGA card though?)

## Can I upgrade the video RAM?

Maybe? I believe the internal display's video RAM is on the mainboard. You might be able to replace the RAM chips for external display on the HGRS board.

## Can it run DOOM?

Yes. But very slowly 🐌. Upgrading the CPU will help, and I recomment FastDOOM - a port of DOOM that's optimised to be as fast as possible on old machines: https://github.com/viti95/FastDoom/

Note: DOOM 2 has a hard RAM requirement (8MB I think)


# 🖼️ Photos

- I've taken a bunch of nice, big photos of the guts of this machine here:

https://photos.app.goo.gl/ahrCAmGZybXRYxjD6

# 🔗 Links

http://www.le-grenier-informatique.fr/pages/les-telechargements/utilitaires.html
 
https://xtideuniversalbios.org/

https://forum.vcfed.org/index.php?threads/toshiba-t5200-100-with-cp30174e.52335/#post-641502


# 🪛 DISASSEMBLY

## 🔩 SCREWS

- Screen - bottom/hinge: 2x 10mm
- Screen - top (under rubber pads) 2x 8mm
- Plasma frame: 4x 10mm

Accessing RAM/CPU/FPU/BIOS/PC Speaker

- Remove 4x 8mm screws from base, along front of machine
- Wiggle keyboard to release it
- Remove 2x 10mm screws to remove the keyboard plate
