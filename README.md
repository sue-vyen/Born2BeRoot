# Born2BeRoot
groot groot not groot

"Yes, I like knives";

IF not done on your laptop and done on campus mac, you prob need to store them in your 'goinfre' file;
**groot:** _a person given to excess in the consumption of food and drink. A greedy or ravenous eater; a glutton._
- cr: interglot.com
su -

- The goinfre file is kinda like a cloud that can store lots of files with large GB, your mac by now should have 1GB to 3GB which isn't enough.

  **STORAGE**
- Virtualbox Disk Image (VDI): Oracle VM VirtualBox uses its own container format for guest hard disks.
- Virtual Hard Disk (VHD): disk image file formats that have similar functionalities to a physical hard drive and are designed primarily for use with Hyper-V virtual machines.
- Virtual Machine Disk (VMDK): a disk image file format for storing the entire contents of a computer's hard drive.
\\
- Dynamically allocated memory: use space on the physical hard disk as more things are added and will not shrink if space is freed
- Fixed size: faster to use but slower for sys to create.

  **PARTITION**
- a logical division of a hard disk that is treated as a separate unit by operating systems (OSes) and file systems.
- more logical than functional
- splitting the drive up into specific segmented parts
- LOGICAL VOLUME MANAGEMENT (LVM)
  - a portion of physical volume, a hierarchy of structures is used to manage disk storage
  - every phy vol belongs to a volume grp OR used directly for virtual storage
  - every volumer group has a virtual box
    - virtual box sizes can vary and shirnk and expand depending on usage and purposes
 - overview: BOX <- LVM <- VG <- LV

 **SUDO POLICIES + PASSWORD**
 <img width="919" alt="Screenshot 2023-06-27 at 15 39 47" src="https://github.com/sue-vyen/Born2BeRoot/assets/130726863/9881f274-ccfc-4184-90da-a25a4b546623">

<img width="854" alt="Screenshot 2023-06-30 at 16 50 07" src="https://github.com/sue-vyen/Born2BeRoot/assets/130726863/e422e95d-fd56-4a65-a32b-20e568169c3a">

GID = group ID;
UFW = uncomplicated firewall
 - adds extra layer of protection
 - protect comp / your network by controlling the incoming + outgoing internet traffic
   - decides which connections are allowed + blocked
SSH = secure shell
- needed to generate to connect a host
- code for your comp
- securely connect encrypted to another computer over an untrusted network
- ensures communications + data remain private + protected
Cron = background process manager specified process will be executed at the time specified in the time


**pewpew**
sudogroot: swifer'MIAW'cinnamonroll2689
groot2: pewpewDUA2806*
grootencyrpt: Meimeiissuperduperfluffy3456!

to enter root:
command -> su
name
password

to add grp:
command -> sudo addgroup (groupname)
 - to check if grp is added:
   command -> getent group (groupname)
to add user to grp:
command -> sudo adduser (user) (groupname)

IF GONNA REDO AND THE SAME .vdi IS ALREADY CONNECTED TO A PORT
rm ./.ssh/known-hosts


**SHASUM** -> command that allows you to identify the integrity of a file using the SHA-1 hash check sum of a file
08a891d863a9984209cb292df95fcbd57b03cfc7  Born2beroot.vdi
