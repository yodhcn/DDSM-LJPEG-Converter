# DDSM-LJPEG-Converter

This repository is created for converting Mammography of Digital Database for Screening Mammography (DDSM) form LJPEG to more ordinary format.



## Initial Requirements

- Windows

- Cygwin

  

## Install Cygwin on Windows

**There are 4 steps you need to pay attention to.**

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1qBbLclWD3KVjSZFs763qkpXap.png" alt="Sample" width="402" height="311">
	<p align="left">
		<em> ATTENTION 1: Choose to install for “Just Me”.</em>
	</p>
</p>

**Search components with the search box.**

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1anLRclKw3KVjSZFO761rDVXaM.png" alt="Sample" width="768" height="408">
	<p align="left">
		<em> ATTENTION 2: Choose to install ImageMagick.</em>
	</p>
</p>

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1BvYNcoGF3KVjSZFv762_nXXaN.png" alt="Sample" width="768" height="408">
	<p align="left">
		<em> ATTENTION 3: Choose to install ruby.</em>
	</p>
</p>

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1OjfPcmSD3KVjSZFK76210VXaW.png" alt="Sample" width="768" height="408">
	<p align="left">
		<em> ATTENTION 4: Choose to install rubygems.</em>
	</p>
</p>



## Usage

**1\.** Initialize your home directory.

 Start a Cygwin session by double-clicking the **Cygwin icon** on your desktop.

 Initially, your session will start in your “**home**” directory, denoted by “~” in Cygwin.

 (This corresponds to the Windows directory "**C:\cygwin64\home\<Your User Name>** "

 where <Your User Name> is your Windows username.)

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1knkPca5s3KVjSZFN763D3FXam.png" alt="Sample" width="546" height="317">
	<p align="left">
	</p>
</p>

**2\.** Copy the **DDSM-LJPEG-Converter** folder into your Cygwin home directory.

 (i.e., **C:\cygwin64\home\<Your User Name>\DDSM-LJPEG-Converter**)

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1itgOcaSs3KVjSZPi763siVXaz.png" alt="Sample" width="559" height="362">
	<p align="left">
	</p>
</p>

**3\.** Copy your LJPEG pictures folder into the **DDSM-LJPEG-Converter** directory.

 The LJPEG pictures folder can be a Nested Folder, but there are 2 points you need to pay attention to.

- ATTENTION 1: Don't modify **.LJPEG** filenames and **.ics** filenames.
- ATTENTION 2: Ensure that **.LJPEG** files are in the same directory as their corresponding **.ics** file.

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1G8M5Xvxj_uVjSZFq761boFXas.png" alt="Sample" width="559" height="362">
	<p align="left">
	</p>
</p>

**4\.** Change directory to the DDSM-LJPEG-Converter directory.

 Change directory to the newly created **DDSM-LJPEG-Converter** directory 

 by typing the following command into the terminal and then pressing return:

```
cd DDSM-LJPEG-Converter
```

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1SGwPclCw3KVjSZFu763AOpXa2.png" alt="Sample" width="546" height="317">
	<p align="left">
	</p>
</p>

**5\.** Run the ruby script.

```
./LJPEG-to-png
```

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1hksIcliE3KVjSZFM762QhVXa3.png" alt="Sample" width="546" height="317">
	<p align="left">
	</p>
</p>

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1LawKcmSD3KVjSZFK76210VXaW.png" alt="Sample" width="559" height="361">
	<p align="left">

<p align="left">
	<div align=left><img src="https://ae01.alicdn.com/kf/HTB1WhQJcliE3KVjSZFM762QhVXag.png" alt="Sample" width="559" height="361">
	<p align="left">
	</p>
</p>
