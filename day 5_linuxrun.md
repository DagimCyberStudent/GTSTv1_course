                 ADVANCED LINUX USER!💻
          some advanced user commands 
     . to change password of user
           . sudo passwd username
     . to change user id 
           . sudo usermode -u new_id
     . to delete user
           . sudo userdel -r username
     . to change user on terminal
                  sudoers file
     * the sudoers file is afile linux and unix administrators use to allocate system rights to system users
     *  The user you created doesn’t have power to use sudo as the original one. 
     * this is b/c it is not added in the sudoers file
     * to access the file
        . sudo visudo
                   cont..
        # You can add the User you need to have access to the sudoers ﬁle, so he can use the sudo command
                        Linux file permission 
      ● every file on linux have their own
           ○ Owner
           ○ Permissions                 
      ● There is 5 main parts on the listing
      ○ Permission
      ○ Owners 
      ○ Date
      ○ Size 
      ○ ﬁlename 
            ownership
     ● ownership is the owner of the file
     ● this have 2 kind 
         . user        . group
     ● to change the owner of file you can use the command 
           . chown user:group filename 
          permission
     ● There are 3 types of permissions ○ Read ( r ) ○ Write ( w ) ○ Execute ( x )
     ● The folders and ﬁles are differ with the ‘d’ and ‘-’ on the beginning of the permission. 
         cont..
      ● There still the permission have three parts.
       ○ user -group-other 
      ● User ( u ) => power of user deﬁned on the the ownership 
      ● Group (g )=>  power of group deﬁned on the the ownership
      ● Other ( o ) =>  power of other users.
      ● All ( a ) => power of all which can be found in the 3 above owners 
      ● Command to change permission of ﬁle 
      ○ chmod <option> ﬁlename
           CHMOD command
       ● This command helps to change ﬁle permission. 
       ● Those ﬁle permissions are read,write & execute. 
       ● Each of the permission have a number representations.
        ○ Read -> 4 -  r
        ○ Write -> 2 - w ○ Execute  -> 1 - x 
       ● Syntax
        ○ chmod <parameter> ﬁlename             
        cont..
      ● The parameter can be in numbers and symbols 
   A) Parameters in symbol 
    ○ chmod a+x ﬁlename   ->  adding execute permission for all  ( chmod +x ﬁlename) 
    ○ chmod u+x ﬁlename -> adding execute permission for user 
    ○ chmod g+x ﬁlename -> adding execute permission for group 
    ○ chmod o+x ﬁlename -> adding execute permission for other 
    ○ chmod -x ﬁlename -> removing execute permission for all 
    ○ chmod a+rwx , u-rw , g-x , o-xw ﬁlename -> gives rwx for all and removes something from all
   B) Parameters in Number
 ● chmod 621 ﬁlename -> 6 for user, 2 for group, 1 for other  ( 6 = 4+2 ),  6 =r w ● chmod 777 ﬁlename -> 7 for users, 7 for group , 7 for others (7 =4+2+1),  7 = rwx
                               special file permissions
       - There are another 3 special permissions, you may encounter on your pentest Journey.
        - They are 
        - SUID bits(s)   - set user ID bit    - add 4 infront of our numeric value  ->    4000 
        - SGID bits(S) - set group ID bit - add 2 infront of our numeric value ->  2777 
        - Sticky bits(t) - set other ID bit - add 1 in front of our numeric value -> 1602 
        - They are permissions like the execute(x), but they will set the execute permission to the user who settled them. 
        - Example: if mr.A add suid bit to a program that program will be executed with permission of mr.A 
           - Meaning if admin add suid bit on some program. Then any user if they got that program they can run it as root with any sudo password
                   package installation on linux
    ● on linux to install softwares you use package managers
       - ex:apt,pacman,pkg
    ● we will use debian package manager
    ● on debian the package manager i called 'apt'also there is called 'dpkg'
    ● package manager are afree-software user interface that work with an online server to handle the installation and removal of software on debian and debian-based linux distributions.
                     the repository
        ● this is the site/server kali use to upload the packages             
                      advanced package tool/apt/
     ● Apt is a free-software user interface that work with an online server to handle the installation and removal of software on Debian, and Debian-based Linux distributions.used for online and offline purpose. 
     ● The old ‘apt’ used as ‘apt-get’ 
                ● Syntax 
     ○ sudo apt update
      ○ sudo apt search <softwarename> 
      ○ sudo apt install <softwarename> 
      ○ sudo apt remove <softwarename> 
      ○ sudo apt upgrade 
      ○ sudo apt purge 
      <softwarename>
                package dependencies
      ● A software can be built based on another program called ‘modules’
      ● SO, a program to work properly, the dependencies have to be installed successfully. 
      ● Those package managers install the software+dependencies.
                                 dekp/debian package manager/
       ● Dpkg is an ofﬂine package managing program. 
       ● Packages on debian have an extension “.deb” 
       ● Syntax 
          ○ sudo dpkg -i <packagename> 
          ○ sudo dpkg -r <packagename>
          ○ sudo dpkg -P <packagename                          






















