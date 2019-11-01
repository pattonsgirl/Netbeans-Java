# Installation of Java + Netbeans
This guide is for Programming Classes at Wright State University.  This guide will install the software setup currently installed in CSE labs.  Once newer versions have been tested, this guide will be updated.

JDK version: 8

Netbeans version: 8.2

Use [Apache Netbeans 11](https://netbeans.apache.org/download/) at your own risk.  Our labs use Netbeans 8.2, not 11

For all Operating Systems (Windows, Mac, Linux), download the installer from here:
- https://www.oracle.com/technetwork/java/javase/downloads/jdk-netbeans-jsp-3413139-esa.html

This installer is a lovely bundle that includes: Netbeans 8.2 AND JDK 8 (and the JRE)

## For Windows
- [Download the installer for Windows](http://download.oracle.com/otn-pub/java/jdk-nb/8u111-8.2/jdk-8u111-nb-8_2-windows-x64.exe).  Note: this is the 64 bit installer.  
- Find the installer (usually your Downloads folder)
- Double-click the installer file to run the installer
- At the Welcome page of the installation wizard, click Next
- At the JDK Installation page, specify which directory to install the JDK into and click Next
  - Make note of where this is just in case you need to set environmental varibles
  - Default is Program Files or Program Files x86
- At the NetBeans IDE Installation page, do the following:
  - Specify the directory for the NetBeans IDE installation
  - Accept the default JDK installation to use with the IDE
  - Click Next
- Review the Summary page to ensure the software installation locations are correct
- Click Install to begin the installation
- At the Setup Complete page, provide anonymous usage data if desired, and click Finish

### Environment Variables
If you opened Netbeans and things look normal, you're good to go, ignore this section.  If Netbeans won't open or it's acting "wrong", you get to experience setting environment variables.

## For Mac / Apple
- [Download the installer for Mac](http://download.oracle.com/otn-pub/java/jdk-nb/8u111-8.2/jdk-8u111-nb-8_2-macosx-x64.dmg)
- After the download completes, run the installer. The installer file has the .dmg extension
- On the panel that opens double-click the package icon. The package has the .mpkg extension. The installation wizard starts
- At the Introduction page of the installation wizard, click Continue
- At the Installation Type page, select the appropriate option below:
  - To perform a standard installation of the Software Bundle, click Install
  - To specify another installation location, click Change Install Location
  - (Optional, required if you clicked Change Install Location) At the Destination Select page, specify the disk for Software Bundle installation and click Continue
  - (Optional, required if you clicked Change Install Location) At the Installation Type page, click Install
- Enter the administrator's name and password for your system and click Install Software to begin the installation.
- The Installation page displays the progress of the installation.
- When the installation is complete, click Close at the Summary page.

For NetBeans 8.2, jdk 12 is not compatible, so you need to install jdk 8
To set an environment variable, follow this guide:
https://medium.com/@himanshuagarwal1395/setting-up-environment-variables-in-macos-sierra-f5978369b255

You will still need to edit the netbeans.conf file, as can be found in this guide:
https://www.cs.wcupa.edu/rkline/index/netbeans-mac.html

### Environment Variables
If you opened Netbeans and things look normal, you're good to go, ignore this section.  If Netbeans won't open or it's acting "wrong", you get to experience setting environment variables.

## For Linux
OMG. You use Linux?  I use Linux!  This is gonna be great.
- [Download the installer for Linux](http://download.oracle.com/otn-pub/java/jdk-nb/8u111-8.2/jdk-8u111-nb-8_2-linux-x64.sh)
- Navigate to the directory into which you downloaded the installer file and type:
  - chmod +x <installer-file-name> to change the installer file's permissions so it can be executed.
- Installing the Software
- Type the following command from the directory where you placed the installation file:
  - `./<installer-file-name>`
- At the Welcome page of the installation wizard, click Next.
- At the JDK Installation page, specify the directory where to install the JDK and click Next.
- At the NetBeans IDE Installation page, do the following:
  - Specify the directory for the NetBeans IDE installation.
- Accept the default JDK installation to use with the IDE or specify another JDK location.
  - Click Next.
- Review the Summary page to ensure the software installation locations are correct.
- Click Install to begin the installation.
- At the Setup Complete page, provide anonymous usage data if desired, and click Finish.
- When the installation is complete, you can view the log file, which resides in the following directory: `~/.nbi/log`
Note: If you choose to install this bundle into a system-wide location such as /usr/local, you must first login as root to gain the necessary permissions.

### Environment Variables
If you opened Netbeans and things look normal, you're good to go, ignore this section.  If Netbeans won't open or it's acting "wrong", you get to experience setting environment variables.

