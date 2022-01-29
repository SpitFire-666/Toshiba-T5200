# TOSHIBA T5200 

## Info, data, pics, tips etc

![image](https://user-images.githubusercontent.com/38451588/129733966-22ee7865-65f6-43b2-9c47-891b78e0b54f.png)


# Maintenance Manual

http://www.minuszerodegrees.net/manuals/Toshiba/Other/Toshiba%20T5200%20-%20Maintenance%20Manual.pdf

# Power Supply
P/N: 5200-0010 


![image](https://user-images.githubusercontent.com/38451588/129731104-cbda1bd7-740c-4aaa-bf04-e68c6f322636.png)

![image](https://user-images.githubusercontent.com/38451588/129731131-282254ee-aae3-4a3a-9ddc-ed9c00d45409.png)

### Components

PC001, PC002: 0N3105


# BIOS

### BIOS entry


https://xtideuniversalbios.org/


### BIOS chip

![image](https://user-images.githubusercontent.com/38451588/129731323-b3285d0e-eee0-4757-96bb-07222fd3d0ee.png)


# Memory (RAM)

A maximum of 16MB is supported (but I've only seen up to 14MB).

The T5200 has 1MB of memory soldered on board and an expansion SIMM board with 6 and a half SIMM slots which uses proprietary 40 pin SIMMs. 

RAM types appear to be the same as the Toshiba T8500 desktop PC and Acer 735C.

### Memory board

![image](https://user-images.githubusercontent.com/38451588/132091941-90e3593b-97c7-41dc-ae5d-c5e213af373b.png)



### Slots

6x 40 PIN SIMM 

1x 30 PIN SIMM (Parity), optional 

![image](https://user-images.githubusercontent.com/38451588/130006005-8cf8ff80-3ef5-4474-afec-e8a421e00806.png)

 
### SIMMs

Front and back of 4 different modules:

![image](https://user-images.githubusercontent.com/38451588/141056903-9fdc0ed4-73e3-4f66-aff3-88474bef04b4.png)
![image](https://user-images.githubusercontent.com/38451588/141056919-16e454e6-6690-42c8-8613-7935e063f799.png)

https://www.winhistory-forum.net/showthread.php?pid=267370


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

# Motherboard/Mainboard

![image](https://user-images.githubusercontent.com/38451588/141057266-ca2b497e-8d77-43d9-920a-48ec93dd3af8.png)



# CPU

- 132-pin PGA i386

## CPU Upgrades

you can fit a 33Mhz or 40Mhz upgrade CPU in the T5200, it will just run at 20Mhz unless it has built in clock doubling. The hardware mods improve the performance of some of the upgrade CPUs but aren't essential and the CPUs will work if you plug them in without any mods albeit with reduced performance. 

 There are four possible 486 compatible CPUs from Cyrix / Texas instruments that can be used to upgrade the T5200s Intel 386 processor (Texas Instruments made the CPUs for Cyrix and sold them under their own brand as well): 

 Be careful when installing, do not confuse PIN 1!!! 
 


 

# Math Co-Processor

![image](https://user-images.githubusercontent.com/38451588/138083051-54b49b0b-7ac3-44ec-b2b5-11dccef7f51e.png)


# Hard Disk (HDD)

- Available in 100MB and 200MB (rarer) capacities

- Replacement drive must match one of the 3 approved conner HDDs - it must match the CHS setting in the BIOS and its model number must start with CP (Conner Peripherals).
 
 Options:
- fire up the T5200 and go in to the BIOS setup and see what hard drive options you have - write them down - and buy a matching Conner CP series IDE drive.
- write the AT version of XTIDE to a boot ROM and configure it in a network card, set the T5200 to no hard drive, and install any generic IDE hard drive.
- find another Conner IDE drive and ask someone on here to hack the ROM, then burn the new ROM and replace the one on your motherboard (or maybe get away with drive overlay software)

 Drive Overlay software is a program that sits in the boot sector and reconfigures the drive before DOS starts.
 
## Connor CP-344/CP-3044 (40MB)

![image](https://user-images.githubusercontent.com/38451588/151661736-462e5589-0b63-4672-a2bb-90371464784b.png)

  
## Conner CP-3104 (100MB):  

  ![image](https://user-images.githubusercontent.com/38451588/138080146-abbab5ef-eec3-4edc-b8d1-839683fb0211.png)

## Conner CP-3204F (200MB):


## HDD upgrades 

https://texelec.com/product/lo-tech-xt-cf-lite-rev-2/


# Floppy Disk (FDD)

The T5200 uses a 26-pin (non-standard) FDD connector, which carries data + power. 

![image](https://user-images.githubusercontent.com/38451588/150640068-7be6420c-4b95-4bab-849b-d8c132eec5b5.png)


These are prone to failure, and hard to find. It's best to use a mod to use a standard 34-pin interface. Then install a standard floppy or even Gotek USB floppy emulator (pictured):

![image](https://user-images.githubusercontent.com/38451588/150640126-d1ac8c05-fb04-4e47-99a7-6dce654382d7.png)


![image](https://user-images.githubusercontent.com/38451588/150640212-b3f8936d-4f67-4805-b96e-1d5f53ca4a75.png)


Adapters like this may also work:

![image](https://user-images.githubusercontent.com/38451588/150640288-59cf68aa-cac1-4da7-9a77-56a8377ee057.png)



# Display

### Specs
Orange Gas Plasma Display (T5200, T5200/100, T5200/200) Display Area: 9.1"W x 6.8"H; 11.5"  

diagonal Resolution: 640 x 480 

Gray scales: 16 Contrast: 100 : 1 

34 pin plug 

### VGA / Video Card

![image](https://user-images.githubusercontent.com/38451588/138082616-0a46b4bf-1432-4946-92b2-cd6db4440687.png)

- You dont really need a video driver for your Paradise PVGA1 (?) because these Toshiba models do have - although indeed having one of the first Paradise SVGA compatible chipsets - only 256kb of video RAM, iirc. which means youre limited to a max of 640x480x16 at max, if I am not mistaken. I have tried installing various drivers for the exact same chipset on my T3200SX without success before realizing that it only has 256kb video RAM. 

 
Just noticed: T3200 or T3200SX? T3200 has EGA graphics card and suitable EGA plasma screen (4 levels of intensity) - same as T5100, except in larger form factor. T3200SX on the other hand has VGA screen (16 levels of intensity) that can be swapped with T5200. 

T5200 and T3200SX do have the same displays, VGA 640x480, 16 shades of intensity. T3200 and T5100 have EGA screens of similar size, but different parameters: 640 by 400 pixels and 4 shades of intensity - that's why CGA games look really well on these machines. 

### Issues 
there is a single line vertical artifact on screen.  

Quite often in these screens this may be a "cold solder" ( https://en.wikipedia.org/wiki/Soldering#Electronics ). You can try to check these "fat" solders on top of the screen - every now and then one of them can be repaired. 
 

## I/O card

- Note - system will not start without this card present.

![image](https://user-images.githubusercontent.com/38451588/138082561-74206daf-6a7a-4af4-8532-e851730fa627.png)


# Combination Lock

# Fans / Cooling

- 3x 4cm x 2cm 12v dumb fans 

# ISA slots
 - One 16-bit (top)
 - One 8-bit (bottom)

# Rear Expansion Slot

Connector made by KEL and 3m makes compatible connectors as well. Part numbers: KEL 8801-060-170L-F or 3M P50-060S-RR1-EA 

 https://www.reddit.com/r/retrobattlestations/comments/j06u3i/i_finally_finished_my_cf_card_adapter_for_toshiba/ 

 
# Links

http://www.le-grenier-informatique.fr/pages/les-telechargements/utilitaires.html
 
