# Ubuntu-File-System-Structure

Let’s explore what each folder in the Linux file system is for.

* `/` ---> This sign is known as “root”. It is the beginning of file system structure. Everything in Linux begins from the root.

*`/bin` ---> Important command binaries which need to be available in single-user mode. Typically, binary files can be for the Linux terminal commands such as cd, pwd, ls and so on (Don’t worry about these terminal commands, I will explain them in later videos).

/boot --- This folder contains all the needed files to boot the system.

/cdrom --- Temporary place for your CD/DVD drive from your computer on your system.

/dev --- Contains Linux device files. Or we can simply say that it is a location where your physical devices are mounted such as hard drives, optical drives, USB drives, and etc.

/etc --- This folder contains configuration files. 

/home --- This folder will contain all your personal files. The folders like desktop, documents downloads are all stored in the home directory. However, note that there can be more than one user. In this case, each user has their own desktop, documents or downloads folder. For example, /home/user1/desktop and /home/user2/desktop.

/lib --- Thin folder contains libraries which are important for binaries in /bin and /sbin.

/media --- This external directory contains devices such as USB drives that can be mounted. Imagine that you insert a CD into your linux system. What will happen? Well, a new directory will be automatically created inside the /media directory so that you can easily access the contents of the CD inside this new directory.

/mnt --- Generally, this directory contains temporary mounted file systems.

/opt --- This directory is a location for optionally installed programs.

/prog --- This directory contains special files that represent system and process information. 

/root --- This directory is the home directory of the root user. Please note that it is different from “ / ” which is the system root directory.

/run ---This directory contains information or files about the current running system.

/sbin --- This directory is similar to /bin, however, it contains the certain commands that can only be run by the root user or superuser.
/snap ---This directory contains files and folders from installed snap packages that appear on your system.

/srv --- Contains data for services provided by the system.

/sys --- This directory holds information about the system.

/tmp --- This directory contains temporary files. You don’t need to delete them manually like in Windows because they are automatically deleted by Linux.

/usr --- This directory contains files and utilities that are shared between users.

/var --- Directory for the variable data. For example, system logs usually are kept here. 

