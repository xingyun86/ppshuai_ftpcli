========================================================================
       MICROSOFT FOUNDATION CLASS LIBRARY : FtpCli
========================================================================


AppWizard has created this Ftp application for you.  This application
not only demonstrates the basics of using the Microsoft Foundation classes
but is also a starting point for writing your application.

This file contains a summary of what you will find in each of the files that
make up your Ftp application.

FtpCli.dsp
    This file (the project file) contains information at the project level and
    is used to build a single project or subproject. Other users can share the
    project (.dsp) file, but they should export the makefiles locally.

FtpCli.h
    This is the main header file for the application.  It includes other
    project specific headers (including Resource.h) and declares the
    CFtpApp application class.

FtpCli.cpp
    This is the main application source file that contains the application
    class CFtpApp.

FtpCli.rc
    This is a listing of all of the Microsoft Windows resources that the
    program uses.  It includes the icons, bitmaps, and cursors that are stored
    in the RES subdirectory.  This file can be directly edited in Microsoft
	Visual C++.

res\FtpCli.ico
    This is an icon file, which is used as the application's icon.  This
    icon is included by the main resource file Ftp.rc.

res\FtpCli.rc2
    This file contains resources that are not edited by Microsoft 
	Visual C++.  You should place all resources not editable by
	the resource editor in this file.




/////////////////////////////////////////////////////////////////////////////

AppWizard creates one dialog class:

FtpCliDlg.h, FtpDlg.cpp - the dialog
    These files contain your CFtpDlg class.  This class defines
    the behavior of your application's main dialog.  The dialog's
    template is in Ftp.rc, which can be edited in Microsoft
	Visual C++.


/////////////////////////////////////////////////////////////////////////////
Other standard files:

StdAfx.h, StdAfx.cpp
    These files are used to build a precompiled header (PCH) file
    named Ftp.pch and a precompiled types file named StdAfx.obj.

Resource.h
    This is the standard header file, which defines new resource IDs.
    Microsoft Visual C++ reads and updates this file.

/////////////////////////////////////////////////////////////////////////////
Other notes:

AppWizard uses "TODO:" to indicate parts of the source code you
should add to or customize.

If your application uses MFC in a shared DLL, and your application is 
in a language other than the operating system's current language, you
will need to copy the corresponding localized resources MFC42XXX.DLL
from the Microsoft Visual C++ CD-ROM onto the system or system32 directory,
and rename it to be MFCLOC.DLL.  ("XXX" stands for the language abbreviation.
For example, MFC42DEU.DLL contains resources translated to German.)  If you
don't do this, some of the UI elements of your application will remain in the
language of the operating system.

/////////////////////////////////////////////////////////////////////////////
