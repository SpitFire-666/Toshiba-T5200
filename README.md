![image](https://user-images.githubusercontent.com/38451588/129733966-22ee7865-65f6-43b2-9c47-891b78e0b54f.png)


# Power Supply
P/N: 5200-0010 


![image](https://user-images.githubusercontent.com/38451588/129731104-cbda1bd7-740c-4aaa-bf04-e68c6f322636.png)

![image](https://user-images.githubusercontent.com/38451588/129731131-282254ee-aae3-4a3a-9ddc-ed9c00d45409.png)

### Components

PC001, PC002: 0N3105



# BIOS

### BIOS entry


### BIOS chip

![image](https://user-images.githubusercontent.com/38451588/129731323-b3285d0e-eee0-4757-96bb-07222fd3d0ee.png)


# Memory (RAM)

### Slots

6x 40 PIN SIMM 

1x 30 PIN SIMM (Parity), optional 

![image](https://user-images.githubusercontent.com/38451588/130006005-8cf8ff80-3ef5-4474-afec-e8a421e00806.png)

 
### Modules


| Make | Part No | Capacity | Chips | Notes |
|-|-|-|-|-|
| OKI | | 1MB? | 9B9Z, M5I4256A-80J. M5IC256-80, 043033 | "TLM-5200-1M" marking on rear |
| Toshiba | ||||
| Toshiba | ||||


RAM types appear to be the same as the Toshiba T8500 desktop PC and Acer 735C.  

The T5200 has 2MB of memory soldered on board and an expansion SIMM board with 6 and a half SIMM slots but uses proprietary 40 pin SIMMs. 

 Here are details on a mod to add 8MB of RAM using a standard 72 pin 8MB Parity SIMM. (Requires at least 2MB of proprietary SIMMs already fitted) 

 Use this info at your own risk, don't blame me if you damage your T5200! 


https://www.vogons.org/viewtopic.php?f=46&t=57998&start=20 


https://www.vogons.org/download/file.php?id=45121&mode=view 


IanB, I have Yet Another Question for you: 
Is there any way around the 14mb RAM limit? 
In the original PC/XT/AT, you could add an ISA RAM card to expand the memory. Could such a card be plugged into the T5200 with the memory mapped beyond the 14mb limit, providing a theoretically 32 or even 64mb of total RAM? 

 You might be able to use a 16 bit ISA memory expansion board for memory below 16MB but that might not work and would be very slow even if it did. 

 

Each pair of SIMM slots has a single label on the component side so there are 6 slots but only 3 labels (IS17, IS16 & IS15 - ignoring the short 30 pin slot). The middle pair is IS16 and one slot I have referenced as "A" and the other as "B" although they are not labelled 


Web links: 

https://www.iclocator.com/rfq.html/-5405EDC5-0471-4E05-9AC9-37B072077022?pagename=rfq&e=33oueXFqWRA 

 

https://old.pinouts.ru/Memory/simm_40pin_pinout.shtml 


# CPU

# Co-Processor

# Hard Disk (HDD)

# Floppy Disk (FDD)

# Display

### Specs
Orange Gas Plasma Display (T5200, T5200/100, T5200/200) Display Area: 9.1"W x 6.8"H; 11.5"  

diagonal Resolution: 640 x 480 

Gray scales: 16 Contrast: 100 : 1 

34 pin plug 

- You dont really need a video driver for your Paradise PVGA1 (?) because these Toshiba models do have - although indeed having one of the first Paradise SVGA compatible chipsets - only 256kb of video RAM, iirc. which means youre limited to a max of 640x480x16 at max, if I am not mistaken. I have tried installing various drivers for the exact same chipset on my T3200SX without success before realizing that it only has 256kb video RAM. 

 
Just noticed: T3200 or T3200SX? T3200 has EGA graphics card and suitable EGA plasma screen (4 levels of intensity) - same as T5100, except in larger form factor. T3200SX on the other hand has VGA screen (16 levels of intensity) that can be swapped with T5200. 

T5200 and T3200SX do have the same displays, VGA 640x480, 16 shades of intensity. T3200 and T5100 have EGA screens of similar size, but different parameters: 640 by 400 pixels and 4 shades of intensity - that's why CGA games look really well on these machines. 

### Issues 
there is a single line vertical artifact on screen.  

Quite often in these screens this may be a "cold solder" ( https://en.wikipedia.org/wiki/Soldering#Electronics ). You can try to check these "fat" solders on top of the screen - every now and then one of them can be repaired. 
 

# Combination Lock

# Fans / Cooling

3x 4cm x 2cm 12v dumb fans 

# ISA slots
 - One 16-bit
 - One 8-bit

# Rear Expansion Slot

Connector made by KEL and 3m makes compatible connectors as well. Part numbers: KEL 8801-060-170L-F or 3M P50-060S-RR1-EA 

 https://www.reddit.com/r/retrobattlestations/comments/j06u3i/i_finally_finished_my_cf_card_adapter_for_toshiba/ 

 
# Links

http://www.le-grenier-informatique.fr/pages/les-telechargements/utilitaires.html
 
