---
sidebar_label: 'Install OS to an Micro SD Card'
sidebar_position: 31
---

# Install OS to an SDCard

## Preparation 

1. Prepare a Micro SD card
2. Prepare an SD card reader
3. Download the official Ubuntu/Debian system image from [Downloads](../downloads/official-images).
4. Insert the SD card into the card reader, then insert the card reader into the USB port of the computer.  
![ROCK5A Install](/img/accessories/sd_install_1.webp)


## Flash OS image to Micro SD card

### Flash OS image to Micro SD card via etcher

1. Download the flash tool etcher from [Downloads](https://www.balena.io/etcher#download-etcher).  
  - ![ROCK5A via Etcher 01](/img/rock5a/rock5a-etcher.webp)

2. Open etcher and prepare to flash OS image to Micro SD card. In the etcher window, click `Flash from file` to select the OS image you just downloaded.
  - ![ROCK5A via Etcher 02](/img/rock5a/rock5a-etcher-1.webp)

3. In the etcher window, click `Select target`.
  - ![ROCK5A via Etcher 03](/img/rock5a/rock5a-etcher-2.webp)

4. In the etcher window, click `Flash!` and wait for flashing image process.
  - ![ROCK5A via Etcher 04](/img/rock5a/rock5a-etcher-3.webp)

5. In the etcher window, it means success when it shows `Flash Complete!`
  - ![ROCK5A via Etcher 05](/img/rock5a/rock5a-etcher-4.webp)
  
**If the flash OS image fails, please manually flash the image once again.**

### Flash OS image to Micro SD card via Win32DiskImager

1. Download the flash tool Win32DiskImager from [downloads](https://win32diskimager.org/). 
  - ![ROCK5A via Win32DiskImager 01](/img/rock5a/rock5a-win32.png)

2. Open Win32DiskImager  
  - ![ROCK5A via Win32DiskImager 02](/img/rock5a/rock5a-win32-1.png)  

3. Click the folder icon button and select the .img file to write image.
  - ![ROCK5A via Win32DiskImager 03](/img/rock5a/rock5a-win32-2.png)   

4. After the above configuration is completed, click the Write button to start writing image. Next, wait for the write image to compete.  
  - ![ROCK5A via Win32DiskImager 04](/img/rock5a/rock5a-win32-3.png) 


