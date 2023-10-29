              Further On Linux
       linux file hierarchy
   ● linux/unix have aspecial file system than windows
         system files
    ● system file are file used by the system software(os)
    -> windows: system file appear under the local disk c:
    -> linux: system file appear under the root directory(/)
                           file structure in detail 
            1. /(root)
              . every single file and directory start from the root directory 
              . the only root user has the right to write under this directory
              .  /root is the root user’s home directory, which is not the same as /            
            2. bin- binary executables  
               .  Essential command binaries that need to be available in single-user mode; for all users i) e.g) cat, ls, cp,pwd 
            3. /boot- boot loader file 
                .  Kernel initrd, vmlinux, grub ﬁles are located under /boot ○ Example: initrd.img-2.6.32-24-generic, vmlinuz-2.6.32-24-generic
            4. /dev- essential device files 
                . These include terminal devices, usb, or any device attached to the system.
                  Example: /dev/tty1, /dev/usbmon0
            5. /etc- etcetera
                .  Contains conﬁguration ﬁles required by all programs. ○ This also contains startup and shutdown shell scripts used to start/stop individual programs.
                  Example: /etc/resolv.conf, /etc/logrotate.conf.            
            6. /home-home directory
                . Home directories for all users to store their personal ﬁles. ○ example: /home/nathan, /home/rexde    
            7. /lib- libraries essential for the binaries in /bin & /sbin
                 .  Library ﬁlenames are either ld* or lib*.so.*
                   Example: ld-2.11.1.so, libncurses.so.5.7            
            8. /media-mount point for removable media such as cd-rom
                . Temporary mount directory for removable devices. 
                 Examples, /media/cdrom for CD-ROM; /media/ﬂoppy for ﬂoppy drives; /media/cd recorder for CD write
            9. /mnt- temporarily mounted file
                 . Temporary mount directory where sysadmins can mount ﬁlesystems.
            10. /opt-optional application software packages
                . Contains add-on applications from individual vendors. 
                 Add-on applications should be installed under either /opt/ or /opt/ sub-directory.             
            11. /sbin- essential system binaries
                  . Just like /bin, /sbin also contains binary executables.   The linux commands located under this directory are used typically by system administrator, for system maintenance purpose.
            12. /tmp- temporary file
                . Directory that contains temporary ﬁles created by system and users.  Files under this directory are deleted when system is rebooted 
            13. /usr-user utilites
               . Contains binaries, libraries, documentation, and source-code for second level programs
               . /usr/bin contains binary ﬁles for user programs. If you can’t ﬁnd a user binary under /bin, look under /usr/bin. For example: at, awk, cc, less, scp
                        text editors
           - programs that used for text processing
           - linux command line text editors
                 ○ VIM          ○ Nano
                 ○ Emacs
           - linux graphical text editor
                ○ sublime   ○ vscode
                ○ gedit
           VIM
      ● Before vi the primary editor used on Unix was the line editor
          ○ User was able to see/edit only one line of the text at a time      
       ● The vim editor is:
        ○ a very powerful
        ○ but at the same time it is cryptic
        ○ It is hard to learn, specially for windows users
      ● It have mainly to modes
       ○ Command mode -> where you can do commands ○ Input mode -> where you can write     
                opening vim
        - vim is by default on command mode when you open it       
        - to get on insect mode you have to type 'i'
                  command mode
           to get back to command mode you type 'esc' 
        cont..
     ● Inside Command mode you can
      ○ Save
      ○ Save & quit
      ○ Force Quit & Save 
      ○ Undo
      ○ Execute bash commands 
             save
          type: w+enter           
            quit
         type: q+enter   
        save & quit
       type: wq!+enter 
           force=!
           undo 
        type: undo+enter   or:u  
        execute commands
     type: %!yourcommand     this is no space between them
        NANO   
    # the gnu nano text editor is a user-friendly, free and open -source text editor that usually comes pre-installed in modern linux system 
          * starting nano 
          * saving exiting & undo_redo
    - ctrl+s=save           
    - alt+u=undo
    - alt+E=redo                         this ^ is equal to 'ctrl'                                        
    - ctrl+x=exit
    - paste,copy& paste all over the linux is
    - ctrl+shift+c=copy                           
    - ctrl+shift+x=cut
    - ctrl+shift+v=paste
                   you can append text from other file with ctrl+R and spacify the path
                       linux user management
        ● On Computer system, person who uses the computer is called “user”
         ● Every Users have Group.
         ● Users have their own ﬁle & applications. ● To know our name on linux -> “ whoami “ ● Those users have power/privilege.
         ● On linux  there's 2 kinds users.
             ○ Root  id = 0 
             ○ Normal User id start with 1-999
       The root user have the power to do          everything on linux , 
              but if users want to have a root access they add sudo in front of the command .
              sudo YourCommand
            ● SUDO = Superuser do  ,  used to pass permission denied        
                          creating user
    ● On linux, to create users you can use the following commands
        ○ Useradd -> simple
        ○ Adduser   -> Detailed 
    ● Useradd command
        ○ sudo useradd username
    ● Adduser command
        ○ sudo adduser username
          The User ﬁles are stored inside /etc/passwd
          The User password are stored inside /etc/shadow
          When you create a user it creates a group with that name.                    
                        checking/etc/passwd
        -> this happened what shell i do?
                         to access root user
             # command 
                 -> sudo su
                                            
















































                   













