Filename:		ica32.exe, ica32t.exe, wfica.cab, wficat.cab
For:			Citrix ICA Win32 Client
			(ICA 32-bit Windows Client)
Replaces: 		All versions prior to January 2001
Date:			January 2001
Language supported:	English



Description
--------------
The ICA 32-bit Windows Client supports the following platforms:
Windows 2000
Windows 98
Windows 95
Windows NT 4.0
Windows NT 3.51


Where to Find Documentation
---------------------------
This document contains last-minute information on the ICA Win32 
Client. For more information about the ICA Win32 Client, refer 
to the Citrix ICA Client Administrator’s Guide for the ICA Win32
Client, available in an Adobe Portable Document Format (PDF) file
(ICA_Win32_Guide.PDF). 

The file is in the \DOC directory on the Citrix ICA Client CD. 
Use the Adobe Acrobat Reader or Exchange program to view PDF files. 
You can download Acrobat Reader for free from Adobe’s Web site 
at http://www.adobe.com.

You can also find documentation on the Web at:
  * http://www.citrix.com/download, on the Citrix Downloads page;
    click ICA Clients 
  * http://www.citrix.com/support, on the Services Portfolio page;
    click the Product Documentation tab and choose ICA Clients


New Features in this Release
------------------------------

1. TCP/IP+HTTP server location allows you to locate Citrix servers
   across firewalls that do not support UDP broadcasts.

2. SpeedScreen Latency Reduction enhances user experience on slower
   network connections.

3. Multiple Monitor Support - The Citrix ICA Win32 Client supports 
   multiple monitors connected to a single computer.

4. Pass-through authentication provides the ability to pass the user’s
   desktop password to the server, eliminating the need for multiple 
   system and application authentications. 

5. Panning and Scaling - Panning provides scroll bars that allow you 
   to scroll an ICA session image configured at a higher resolution 
   than your local client desktop. Scaling provides controls that 
   enable you to shrink an ICA session image to fit your desktop.


Installation Instructions for the ICA Win32 Client
---------------------------------------------------
See the ICA Client Administrator's Guide for step-by-step
instructions for installing the ICA Win32 Client.


Limitations and Known Issues 
------------------------------

1. If you enable single sign-on on the ICA Win32 Client, auto client 
   update is disabled. 

2. When running an ICA session on a computer with multiple monitors 
   running at different color depths, moving the ICA session window
   between monitors will corrupt the display. If you want to move ICA
   sessions between monitors, you must set all monitors to the same 
   color depth.

3. If you install a Web browser after installing the ICA Win32 Web 
   Client, you must reinstall the ICA Win32 Web Client, if you are 
   using the Netscape Plug-In. The Netscape Plug-In needs to be 
   registered with the browser so that when you select an ICA file
   in an HTML file, the browser knows what to run to invoke the 
   ICA file. 

4. If you set an encryption level higher than Basic, you must add the
   following line to the appsrv.ini file in order to use the single
   sign-on feature: 

	AutoLogonAllowed=on


5. If the color depth of your local desktop is set to High or True 
   Color, running a 256-color ICA Client session causes a bold border
   around modified cells in Microsoft Excel 97 and Excel 2000. To fix
   this issue, adjust the color depth of your local desktop to match
   that of the ICA Client.

