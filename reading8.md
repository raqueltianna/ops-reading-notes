# Reading 8

1. What is an ISO File?
   - It is a single file that can be duplicate a CD. The file by itself is no good it's the contents inside of it.
2. How do you write an ISO file to a CD, DVD, or removable media (like a thumb drive)?
   - Most operating systems come with built in disc burning capabilities. After you enter a Blank CD/DVD you can just burned the ISO file onto it. For a USB drive you would need a program like the one we used, Rufus, to download the Ubuntu, then download it onto the USB.
3. How do create an ISO file?
   - You have to have a disc in and then either using the built in software or a downloaded software and create an iso file by having a cd/dvd disk and then selecting create an iso image from that. After asking chatgpt about some commands you can put into the terminal to create an iso file you can instaall the tools you need by putting
         sudo apt-get install genisoimage
   - and then to create the iso file you put
         genisoimage -o my_image.iso -R -J /path/to/files (with whatever directory you want it to go to).
4. How do you mount an ISO file?
    - You can open the file with a disc emulator and then choosing a specific drive letter that the file should represent. On newer OS like Windows 10, you can just right click on an ISO file and click mount.

### Things I want to know more about
  - Are ISO files only able to be used in software like Virtual Box?
  - What is the difference between other disk image formats like IMG?
  - Since you can have a whole OS and setting and configurations saved on an iso file or ova file, can you put a password on the file so that if someone else had access to your computer they can't just download the file? 
