# Firestorm-Builds
Private Firestorm Builds

#################################################################
#						                                                    #
#                  Build Informations:		                      #
#						                                                    #
#################################################################
#                    *Primary Build PC*                         #
#                                                               #
#                 OS: Windows 10 Pro (x64)                      #
#         Virtualisation: Vmware Workstation 17 Pro             #
#       Virtual Machine OS: Windows 10 Pro (X64)       		      #
#                System Manufacturer: MSI                       #
#     System Model: MSI MPG X570 GAMING EDGE WIFI (MS-7C37)     #
#    CPU: AMD Ryzen 7 5800X 8-Core Processor 3.80 GHz		        #
#                     Ram: 32GB DDR4 3600mhz                    #
#             	Virtual Machine Ram: 4GB                        #
#         	Graphic: Geforce RTX 3070		                        #
#################################################################
#################################################################
#							                                                  #
#	    Firestorm Viewer Builds Compiled with:	                	#
#                                                               #
#################################################################
#							                                                  #
# -Microsoft Visual Studio 2022 Community Edition		            #
#							                                                  #
# - Microsoft Windows 10 SDK 10.0.22621.0		 	                      #
#
# -Microsoft DirectX SDK (June 2010)
#
# -Cmake 3.28.1					                                        #
#							                                                  #
# -Autobuild 4.dev6  with Python 3 Support	      	#
#							                                                  #
# -Python 3.12.1					                                      #
#							                                                  #
# -Git version 2.43.0					                                	#
#							                                                	#
# -cygwin		                                                   	#
#                                                               #
# -Nulsoft Install System 3.08			                            #
#							                                                  #
#################################################################

#################################################################################
#									    	                                                        #
#    Main Download Server 1: https://1drv.ms/f/s!AnQ_oIqDR87NkBe1llOxC-xHLfDH   #
#    Backup Download Server 2: https://my.hidrive.com/share/lfqyyy5xxz          #
#    Backup Download Server 3: https://keybase.pub/nogardrevlis		            	#
#									    	                                                        #
#################################################################################
-------------------------------------------------------------------------------------------------

Change Log:

30.10.2012
- changed channel format to Include Date used Repro and state use of AVX Instruction set.

Example: Private-Nogardrevlis-Lgpl2-301012-AVX or Private-Nogardrevlis-Lgpl2-301012

Repros are : Lgpl = Official Firestorm Repro or Lgpl2 = Tankmasters Firestorm Repro

-------------------------------------------------------------------------------------------------
01.11.2012
- Striped the Date out of the Channel again (would create to many new channel entrys in Linden Database)

New Formate: Firestorm-Private-Nogardrevlis-Lgpl-AVX / Firestorm-Private-Nogardrevlis-Lgpl
Firestorm-Private-Nogardrevlis-Lgpl2-AVX / Firestorm-Private-Nogardrevlis-Lgpl2

--------------------------------------------------------------------------------------------------
23.07.2013
- New channel Format for LGPL_chui Repository added

New Format: Firestorm-Private-Nogardrevlis-chui-AVX / Firestorm-Private-Nogardrevlis-chui

All Build are Always with Open Simulator functionality there is no Havoc Compatibility for Secondlife available but the Viewer works in Secondlife, Parthfinding is not available.

---------------------------------------------------------------------------------------------------
22.02.2014

- Updated AboutBuilds.txt
- No LGPL2 builds since no experimental features available @ the moment
- There x64 and x86 builds Available on the Server.

- Latest channel Format to reflect this is:

	x86 = Firestorm-Private-Nogardrevlis-Lgpl
	x86_AVX = Firestorm-Private-Nogardrevlis-Lgpl-AVX

	x64 = Firestorm-Private-Nogardrevlis-Lgpl-X64
	x64_AVX = Firestorm-Private-Nogardrevlis-Lgpl-X64-AVX

---------------------------------------------------------------------------------------------------
14.05.2014

- New Installer x64 duo changes what doesn't permit install from.msi Directly
- Only Provide x64 Builds right now, most People could run it normal, so I scraped 32bit Builds since months.

---------------------------------------------------------------------------------------------------
11.10.2014

- changed Host for my Builds to Microsoft One Drive

01.05.2015

- changes in Build environment - VS2013
- NEW KDU Lib
- changed Main Build System to a Virtual Machine running on my System

05.06.2015

- Updated AboutBuilds.txt to reflect last changes made to Compile environment
- formatting fixes AboutBuilds.txt

06.09.2015

- Updated About Builds removed secondary build machine duo upgrade to win 8 no longer used for compiling and Updated compile environment to vc2013 update 5
- Reflect changed Ram in main Build machine
- Updated Operating system to windows 10 in main build machine, Virtual machine stays on windows 7 to compile Viewer.
- New KDU Version: KDU v7.7.0
- Updated Vmware Workstation 11 to Vmware Workstation 12 Pro
- Added Virtualization software to Build Information to AboutBuild.txt

---------------------------------------------------------------------------------------------------

24.11.2015

- New KDU Version: KDU v7.7.1
- Uploaded slvoice_Beta.rar that contains Voice Files that fix some issue with voice Breaking up see:
http://wiki.secondlife.com/wiki/Release_Notes/Second_Life_Release/3.8.7.307744 for info.
-----------------------------------------------------------------------------------------------------

03.07.2016

- Special Build Version for AVX2 Compatible Systems are available in Folder : AVX2 - Special Edition
- Removed some old Versions from Server see FSCleanup.txt for updates
- Voice fix from slvoice_Beta.rar not longer needed for Newer Compiles, fix already in HG

-------------------------------------------------------------------------------------------------------
14.01.2018

- Updated About Builds to reflect Current Compile environment and System Info
- fmodstudio-1.10.02 Now Required to Build Viewer so it was Added in the Build
- New KDU Version : KDU v7.9.1

-------------------------------------------------------------------------------------------------------
25.01.2018

- Linden Lab Updated Compile environment inclusive windows x64 builds with Autobuild 1.1.7

-------------------------------------------------------------------------------------------------------

25.07.2018

- Reflected changes since Last Update AboutBuild

- Updated KDU Version: KDU v7.10.4
- Updated FMOD Version: FMOD Studio 1.10.08 (Compiled on same machine as Firestorm Build)
- Official Voice Fixes from Lindenlab with version : Vivox 4.9.0002.30313

03.12.2018

- Reflected changes since Last Update AboutBuild
- Updated FMOD Version: FMOD Studio 1.10.09 (Compiled on same machine as Firestorm Build)
- Updated KDU Version: KDU v7.10.5

26.12.2018

- Updated KDU Version: KDU v7.10.6
- Updated FMOD Version: FMOD Studio 1.10.10 (Compiled on same machine as Firestorm Build)

08.04.2019

- Updated About Builds to reflect Current Compile environment
- Reflected changes since Last Update AboutBuild
- Updated FMOD Version: FMOD Studio 1.10.12 (Compiled on same machine as Firestorm Build)

08.05.2020

- Reflected changes since Last Update AboutBuild
- Compile Source changed to Git Repository
- Only AVX and AVX 2 Builds will be Provided from this day onwards.
- Updated latest KDU Version v7.10.7
- Updated latest Fmod Version: FMOD Studio 2.01.00 (Compiled on same machine as Firestorm Build)
- Added Second Download Server Strato HiDrive : https://my.hidrive.com/share/lfqyyy5xxz

31.07.2020

- Updated Visual Studio Version to 2017 Community Edition Duo changes from Firestorm Team
- KDU Replace with openjpeg-1.5.1.2 temporarily since I missing a KDU Version that compiles agains VS2017 
- Updated Fmod Version fmodstudio-2.01.02
- Updated AboutBuild.txt

04.08.2020

- Replaced open openJpeg-1.5.1.2 again with Older but Working KDU v7.10.4 from 2018
- Updated AboutBuilds.txt

09.08.2020

- Updated latest Fmod Version: FMOD Studio 2.01.03 (Compiled on same machine as Firestorm Build)
- Updated AboutBuilds.txt

17.10.2020
- Builds now Compile Agains Windows 10 SDK (version 2004) instead of windows 8/7 Windows SDK
- Updated latest Fmod Version: FMOD Studio 2.01.05 (Compiled on same machine as Firestorm Build)
- Updated and Fixed some errors in AboutBuild.txt  

25.10.2020

- Updated Compile environment in AboutBuilds.txt

09.12.2020

- Updated Latest Fmod Version: FMOD Studio 2.01.06 (Compiled on same machine as Firestorm Build)
- Updated AboutBuilds.txt

03.01.2021

- Updated Computer environment ( New System AMD Ryzen 7 3700X )
- Updated Latest Fmod  Version: FMOD Studio 2.01.07
- Updated AboutBuilds.txt

01.08.2021
- Reflect Changes since last Update
- Cleaned up Build Directory
- Updated Latest Fmod Version: FMOD Studio 2.02.02
- Reflect changes to AboutBuilds.txt - Updated Vmware Workstation to Latest Version 16 Pro

14.10.2021
- Updated Fmod Version: FMOD Studio 2.02.03
- Updated and corected some mistakes in AboutBuilds.txt

07.02.2022
- Cleaned up Build Directory
- Updated Fmod Version: FMOD Studio 2.02.05
- Reflect changes AboutBuilds.txt

08.02.2022

- Fixed Bug in Fmod Package FMOD Studio 2.02.05

Bug Alarm: https://qa.fmod.com/t/known-issues-for-2-02-05/18331

Warnung Alle Versionen Die von mir vor dem 08.02.2022 hochgeladen wurden enthalten einen Crash Bug im Fmod Package.

Eine Gefixte Version werde ich sobald wie möglich Bereitstellen und alle Versionen nach dem 08.02.2022 werden diesen Bug nicht mehr enthalten.

02.03.2022

Updated Compile environment
. Autobuild 3.0.0-beta1 with Python 3 Support
. Python 3.8.9 ( Newer Versions doesn't Support Windows 7 anymore )

Updated AboutBuilds.txt
. added third Download Server Keybase: ( https://keybase.pub/nogardrevlis)
. added Autobuild Info to AboutBuilds.txt
. Updated Python info to Reflect change to Python 3
. Updated Cmake and NSIS and GIT Version Informations

07.03.2022
- Cleaned up Build Directory

31.07.2022
- Cleaned up Build Directory
- Updated Fmod Version: FMOD Studio 2.02.07
- Builds now include changes from LindenLab and Firestorm to the Graphic Sub System

01.02.2023
- Updated AboutBuild.txt
- Reflect changes to Fmod,Updated Fmod Version: FMOD Studio 2.02.10

07.02.2023
- Updated Fmod Version: FMOD Studio 2.02.12

21.03.2023
- Updated Fmod Version: FMOD Studio 2.02.13

04.04.2023
- Updated AboutBuilds.txt to reflect following changes
- Updated from Windows 7 to Windows 10, source change broke compile on Windows 7
- Updated CPU from AMD Ryzen 3700X to AMD Ryzen 5800X
- changed to newer Python Version 3.11 after switching to Windows 10
- Updated AutoBuild to autobuild 3.2.5.dev3+g371da97

16.04.2023
- Cleaned up Build Directory 

09.09.2023
- Updated Fmod Version: FMOD Studio 2.02.17

04.10.2023
- Updated Fmod Version: FMOD Studio 2.02.18

29.10.2023
-  Updated VMware® Workstation 17 Pro 17.5.0 build-22583795
-  Updated Compile Environment to Visual Studio Version to 2022 Community Edition
-  Updated Autobuild to Autobuild 4.dev6  with Python 3 Support
-  Updated Git to version 2.39.2

 05.01.2024
-   Updated Git to version 2.43.0
-   Updated Cmake to version 3.28.1
-   Updated Python to version 3.12.1
