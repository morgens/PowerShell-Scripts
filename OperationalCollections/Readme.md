This script will create a set of 134 SCCM collections for your various needs. These collections can be used for operational tasks afterward.

Blog Post with all details : https://systemcenterdudes.com/create-operational-sccm-collection-using-powershell-script/

If you already ran an older version of this script, the script will handle already created collections by removing them and recreate them.

Features :
- Handle collection that were created by a previous version of the script
- The collections will be placed in an "Operational" folder
- The collections are set to 7 days refresh period


Full list :
- All Clients
- All Clients Active
- All Client Inactive
- All Clients Online
- All Clients R2 CU0
- All Clients R2 CU1
- All Clients R2 CU2
- All Clients R2 CU3
- All Clients R2 CU4
- All Clients R2 CU5
- All Clients R2 SP1
- All Clients R2 SP1 CU1
- All Clients R2 SP1 CU2
- All Clients R2 SP1 CU3
- All Clients Not Latest
- All Client 1511
- All Client 1602
- All Client 1606
- All Client 1610
- All Client 1702
- All Client 1706
- All Client 1710
- All Client 1802
- All Client 1806
- All Client 1810
- All Client 1902
- All Client 1906
- All Client 1910
- All Client 2002
- All Client 2006
- All Client 2010
- All Client 2103
- All Client 2107
- All Clients Not Reporting HW Inv since 14 days
- All Clients Not Reporting SW Inv since 30 days
- All Clients X86
- All Clients X64
- All Laptops
- All HP Laptops
- All Lenovo Laptops
- All Dell Laptops
- All SCCM Distribution Points
- All SCCM Site Servers
- All SCCM Site Systems
- All Servers
- All Servers Physical
- All Servers Virtual
- All Servers Windows 2003 or 2003 R2
- All Servers Windows 2008 or 2008 R2
- All Servers Windows 2012 or 2012 R2
- All Servers Windows 2016
- All Servers Windows 2019
- All Systems Created Since 24h
- All Systems Disabled
- All Systems Non Client
- All Systems Obsolete
- All Systems with SCCM Console
- All Workstations
- All Workstations Windows 7
- All Workstations Windows 8
- All Workstations Windows 8.1
- All Workstations Windows 10
- All Workstations Windows 11
- All Workstations Windows XP
- All Windows Update Agent Version Outdated
- Mobile Devices - All Android
- Mobile Devices - All Ipad
- Mobile Devices - All Iphone
- Mobile Devices - All Windows Phone 10
- Mobile Devices - All Windows Phone 8
- Mobile Devices - All Windows Phone 8.1
- Mobile Devices - All Microsoft Surface
- Mobile Devices - All Microsoft Surface 3
- Mobile Devices - All Microsoft Surface 4
- Mobile Device - All
- Workstations | Windows 10 v1507
- Workstations | Windows 10 v1511
- Workstations | Windows 10 v1607
- Workstations | Windows 10 v1703
- Workstations | Windows 10 v1709
- Workstations | Windows 10 v1803
- Workstations | Windows 10 v1809
- Workstations | Windows 10 v1903
- Workstations | Windows 10 v1909
- Workstations | Windows 10 Current Branch (CB)
- Workstations | Windows 10 Current Branch for Business (CBB)
- Workstations | Windows 10 Long Term Servicing Branch (LTSB)
- Workstations | Windows 10 Support State - Current
- Workstations | Windows 10 Support State - Expired Soon
- Workstations | Windows 10 Support State - Expired
- Others | Linux Devices
- Others | MAC OSX Devices
- Office 365 Build Version | 1705
- Office 365 Build Version | 1709
- Office 365 Build Version | 1802
- Office 365 Build Version | 1803
- Office 365 Build Version | 1808
- Office 365 Build Version | 1902
- Office 365 Build Version | 1908
- Office 365 Build Version | 1912
- Office 365 Build Version | 2001
- Office 365 Build Version | 2002
- Office 365 Build Version | 2003
- Office 365 Build Version | 2004
- Office 365 Build Version | 2005
- Office 365 Build Version | 2006
- Office 365 Build Version | 2007
- Office 365 Build Version | 2008
- Office 365 Build Version | 2009
- Office 365 Build Version | 2010
- Office 365 Build Version | 2011
- Office 365 Build Version | 2012
- Office 365 Build Version | 2101
- Office 365 Build Version | 2102
- Office 365 Build Version | 2103
- Office 365 Build Version | 2104
- Office 365 Build Version | 2105
- Office 365 Build Version | 2106
- Office 365 Build Version | 2107
- Office 365 Build Version | 2108
- Office 365 Build Version | 2109
- Office 365 Build Version | 2110
- Office 365 Channel | Monthly
- Office 365 Channel | Monthly (Targeted)
- Office 365 Channel | Semi-Annual
- Office 365 Channel | Semi-Annual (Targeted)
- All systems having a duplicate device record


Tip : You can comment out any collections that you don't want using (#) at the begging of the "New/Add-CMCollection" lines in the "Create Collection" Section.

For more details, you can refer to the blog post link : https://systemcenterdudes.com/create-operational-sccm-collection-using-powershell-script/
