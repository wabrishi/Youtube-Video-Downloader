# Youtube-Video-Downloader

What is python?
Python is an interpreted high-level general-purpose programming language. Python's design philosophy emphasizes code readability with its notable use of significant indentation. Its language constructs as well as its object-oriented approach aim to help programmers write clear, logical code for small and large-scale projects
Python has been an object-oriented language since it existed. Because of this, creating and using classes and objects are downright easy. This chapter helps you become an expert in using Python's object-oriented programming support.
If you do not have any previous experience with object-oriented (OO) programming, you may want to consult an introductory course on it or at least a tutorial of some sort so that you have a grasp of the basic concepts.
However, here is small introduction of Object-Oriented Programming (OOP) to bring you at speed −
Overview of OOP Terminology
•	Class − A user-defined prototype for an object that defines a set of attributes that characterize any object of the class. The attributes are data members (class variables and instance variables) and methods, accessed via dot notation.
•	Class variable − A variable that is shared by all instances of a class. Class variables are defined within a class but outside any of the class's methods. Class variables are not used as frequently as instance variables are.
•	Data member − A class variable or instance variable that holds data associated with a class and its objects.
•	Function overloading − The assignment of more than one behavior to a particular function. The operation performed varies by the types of objects or arguments involved.
•	Instance variable − A variable that is defined inside a method and belongs only to the current instance of a class.
•	Inheritance − The transfer of the characteristics of a class to other classes that are derived from it.
•	Instance − An individual object of a certain class. An object obj that belongs to a class Circle, for example, is an instance of the class Circle.
•	Instantiation − The creation of an instance of a class.
•	Method − A special kind of function that is defined in a class definition.
•	Object − A unique instance of a data structure that's defined by its class. An object comprises both data members (class variables and instance variables) and methods.
•	Operator overloading − The assignment of more than one function to a particular operator.
Creating Classes
The class statement creates a new class definition. The name of the class immediately follows the keyword class followed by a colon as follows −
class ClassName:
   'Optional class documentation string'
   class_suite
•	The class has a documentation string, which can be accessed via ClassName.__doc__.
•	The class_suite consists of all the component statements defining class members, data attributes and functions.
Example
Following is the example of a simple Python class –

•	The variable empCount is a class variable whose value is shared among all instances of a this class. This can be accessed as Employee.empCount from inside the class or outside the class.
•	The first method __init__() is a special method, which is called class constructor or initialization method that Python calls when you create a new instance of this class.
•	You declare other class methods like normal functions with the exception that the first argument to each method is self. Python adds the self argument to the list for you; you do not need to include it when you call the methods.

History of Python.
Python was conceived in the late 1980s by Guido van Rossum at Centrum Wiskunde & Informatica (CWI) in the Netherlands as a successor to ABC programming language, which was inspired by SETL, capable of exception handling and interfacing with the Amoeba operating system.  Its implementation began in December 1989. Van Rossum shouldered sole responsibility for the project, as the lead developer, until 12 July 2018, when he announced his "permanent vacation" from his responsibilities as Python's Benevolent Dictator for Life, a title the Python community bestowed upon him to reflect his long-term commitment as the project's chief decision-maker. January 2019, active Python core developers elected a 5-member "Steering Council" to lead the project. As of 2021, the current members of this council are Barry Warsaw, Brett Cannon, Carol Willing, Thomas Wouters, and Pablo Galindo Salgado.
Python 2.0 was released on 16 October 2000, with many major new features, including a cycle-detecting garbage collector and support for Unicode
Built in Function
Type	Mutability	Description	Syntax examples
bool	immutable	Boolean value	True
False
bytearray	mutable	Sequence of bytes	bytearray(b'Some ASCII')
bytearray(b"Some ASCII")
bytearray([119, 105, 107, 105])
bytes	immutable	Sequence of bytes	b'Some ASCII'
b"Some ASCII"
bytes([119, 105, 107, 105])
complex	immutable	Complex number with real and imaginary parts	3+2.7j
3 + 2.7j
dict	mutable	Associative array (or dictionary) of key and value pairs; can contain mixed types (keys and values), keys must be a hashable type	{'key1': 1.0, 3: False}
{}
ellipsisa
immutable	An ellipsis placeholder to be used as an index in NumPy arrays	...
Ellipsis
float	immutable	Double-precision floating-point number. The precision is machine-dependent but in practice is generally implemented as a 64-bit IEEE 754 number with 53 bits of precision. 	1.414
frozenset	immutable	Unordered set, contains no duplicates; can contain mixed types, if hashable	frozenset([4.0, 'string', True])
int	immutable	Integer of unlimited magnitude	42
list	mutable	List, can contain mixed types	[4.0, 'string', True]
[]
NoneTypea
immutable	An object representing the absence of a value, often called null in other languages	None
NotImplementedTypea
immutable	A placeholder that can be returned from overloaded operators to indicate unsupported operand types.	NotImplemented
range	immutable	A Sequence of numbers commonly used for looping specific number of times in for loops	range(1, 10)
range(10, -5, -2)
set	mutable	Unordered set, contains no duplicates; can contain mixed types, if hashable	{4.0, 'string', True}
set()
str	immutable	A character string: sequence of Unicode codepoints	'Wikipedia'
"Wikipedia"
"""Spanning
multiple
lines"""
tuple	immutable	Can contain mixed types	(4.0, 'string', True)
('single element',)
()


Programming Example 
•	Hello World Program 
•	Add two Numbers 

•	Add two Number using Input

What is Tkinter?
Tkinter is the de facto way in Python to create Graphical User interfaces (GUIs) and is included in all standard Python Distributions. In fact, it’s the only framework built into the Python standard library. 
This Python framework provides an interface to the Tk toolkit and works as a thin object-oriented layer on top of Tk. The Tk toolkit is a cross-platform collection of ‘graphical control elements’, aka widgets, for building application interfaces.
If you want to take advantage of the latest version of Tkinter, you’ll need to install a version of Python that supports Tcl/Tk 8.5 or greater. This will provide you with the Ttk (Tile extension integrated into Tk), which is required in order to run the current Tk widget set. 

Tkinter Programming
Tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit.
Creating a GUI application using Tkinter is an easy task. All you need to do is perform the following steps −
•	Import the Tkinter module.
•	Create the GUI application main window.
•	Add one or more of the above-mentioned widgets to the GUI application.
•	Enter the main event loop to take action against each event triggered by the user.

Example of Tkinter
Output:
  
Geometry Management
All Tkinter widgets have access to specific geometry management methods, which have the purpose of organizing widgets throughout the parent widget area. Tkinter exposes the following geometry manager classes: pack, grid, and place.
•	The pack() Method − This geometry manager organizes widgets in blocks before placing them in the parent widget.
•	The grid() Method − This geometry manager organizes widgets in a table-like structure in the parent widget.
•	The place() Method − This geometry manager organizes widgets by placing them in a specific position in the parent widget.

Tkinter Widgets
Tkinter provides various controls, such as buttons, labels and text boxes used in a GUI application. These controls are commonly called widgets.
There are currently 15 types of widgets in Tkinter. We present these widgets as well as a brief description in the following table –

Sr.No.	Operator & Description
1	Button
The Button widget is used to display buttons in your application.
2	Canvas
The Canvas widget is used to draw shapes, such as lines, ovals, polygons and rectangles, in your application.
3	Checkbutton
The Checkbutton widget is used to display a number of options as checkboxes. The user can select multiple options at a time.
4	Entry
The Entry widget is used to display a single-line text field for accepting values from a user.
5	Frame
The Frame widget is used as a container widget to organize other widgets.
6	Label
The Label widget is used to provide a single-line caption for other widgets. It can also contain images.
7	Listbox
The Listbox widget is used to provide a list of options to a user.
8	Menubutton
The Menubutton widget is used to display menus in your application.
9	Menu
The Menu widget is used to provide various commands to a user. These commands are contained inside Menubutton.
10	Message
The Message widget is used to display multiline text fields for accepting values from a user.
11	Radiobutton
The Radiobutton widget is used to display a number of options as radio buttons. The user can select only one option at a time.
12	Scale
The Scale widget is used to provide a slider widget.
13	Scrollbar
The Scrollbar widget is used to add scrolling capability to various widgets, such as list boxes.
14	Text
The Text widget is used to display text in multiple lines.
15	Toplevel
The Toplevel widget is used to provide a separate window container.
16	Spinbox
The Spinbox widget is a variant of the standard Tkinter Entry widget, which can be used to select from a fixed number of values.
17	PanedWindow
A PanedWindow is a container widget that may contain any number of panes, arranged horizontally or vertically.
18	LabelFrame
A labelframe is a simple container widget. Its primary purpose is to act as a spacer or container for complex window layouts.
19	tkMessageBox
This module is used to display message boxes in your applications.

Tkinter is Python's de-facto standard GUI (Graphical User Interface) package. It is a thin object-oriented layer on top of Tcl/Tk.
Tkinter is not the only GuiProgramming toolkit for Python. It is however the most commonly used one. CameronLaird calls the yearly decision to keep TkInter "one of the minor traditions of the Python world."
Tkinter Documentation
•	Python and Tkinter Programming by John Grayson (see also GuiBooks). This book just recently came back into print on demand, see the publisher's website.
•	Python GUI with Tkinter is a complete tutorial that covers all the widgets for the Tkinter library, complete with examples.
•	Thinking in Tkinter is an introduction to some basic Tkinter programming concepts.
•	TkDocs Tutorial, official Tkinter documentation that covers Python 3+ and Tk8.5, with easy to follow examples.
•	Graphical User Interfaces with Tk, a chapter from the Python Documentation.
•	Online Tcl/Tk Manual Pages - the official man pages at the Tcl Developer Xchange.
•	Tips for Python/Tk by Andreas Balogh (about useful documentation, GUI builders and tips using Grid and HList widgets).
•	The New Mexico Institute of Mining and Technology created its own Tkinter manual. It is available in HTML and PDF.
•	The Tkinter Life Preserver, by Matt Conway is still useful, though way out of date. It's the only document that explains how to read the Tcl/Tk manuals and translate the information there to Tkinter calls. HTML version, converted by Ken Manheimer.
•	The source: when all else fails: Read The Source, Luke!
o	Demo/tkinter/ in the Python source distribution.
	This contains many helpful examples, including updated versions of Matt Conway's examples.
o	Lib/lib-tk/Tkinter.py in any Python distribution.
•	Other prominent Tcl/Tk sites:
o	Tcl Developer Xchange
o	Tcl project at SourceForge
o	Tcl foundry at SourceForge
•	Other Tcl/Tk related links:
o	Simple toolsuite to create Tkinter GUIs on the fly from JSON files

Prerequisites: Python GUI – tkinter
YouTube is a very popular video-sharing website. Downloading a video’s/playlist from YouTube is a tedious task. Downloading that video through Downloader or trying to download it from a random website increases the risk of licking your personal data. Using the Python Tkinter package, this task is very simple-efficient-safe. Few bunch codes will download the video for you. For this, there are two Python libraries – Tkinter and pytube. 
Modules Required:
•	pytube :pytube is a lightweight, simple-to-use, dependency-free Python library that is used for downloading videos from the web.pytube, is not an auto-configured library. You need to install it before using it. Installation of pytube is easy when you have pip. In the Terminal or Command Prompt, type the following command to install pytube.
If you are on Mac OS X or Linux, chances are that one of the following two commands will work for you:
pip install pytube 
git clone git://github.com/NFicano/pytube.git pytube | cd pytube | python setup.py install
•	If you are on Window’s 
pip install pytube3
•	Tkinter: Tkinter is a Python binding to the Tk GUI toolkit. It is the standard Python interface to the Tk GUI toolkit or in simple words Tkinter is used as a Python Graphical User interface. Tkinter is the native library, you don’t need to install it externally, just import, while you use it.

Project Code

# Importing necessary packages
import tkinter as tk
from tkinter import *
from pytube import YouTube
from tkinter import messagebox, filedialog

# Defining CreateWidgets() function
# to create necessary tkinter widgets
def Widgets():

    head_label = Label(root, text="YouTube Video Downloader Using Tkinter",
                    padx=15,
                    pady=15,
                    font="SegoeUI 14",
                    bg="lightblue",
                    fg="red")
    head_label.grid(row=1,
                    column=1,
                    pady=10,
                    padx=5,
                    columnspan=3)

    link_label = Label(root,
                    text="YouTube link :",
                    bg="salmon",
                    pady=5,
                    padx=5)
    link_label.grid(row=2,
                    column=0,
                    pady=5,
                    padx=5)

    root.linkText = Entry(root,
                        width=35,
                        textvariable=video_Link,
                        font="Arial 14")
    root.linkText.grid(row=2,
                    column=1,
                    pady=5,
                    padx=5,
                    columnspan=2)

    destination_label = Label(root,
                            text="Destination :",
                            bg="salmon",
                            pady=5,
                            padx=9)
    destination_label.grid(row=3,
                        column=0,
                        pady=5,
                        padx=5)

    root.destinationText = Entry(root,
                                width=27,
                                textvariable=download_Path,
                                font="Arial 14")
    root.destinationText.grid(row=3,
                            column=1,
                            pady=5,
                            padx=5)

    browse_B = Button(root,
                    text="Browse",
                    command=Browse,
                    width=10,
                    bg="bisque",
                    relief=GROOVE)
    browse_B.grid(row=3,
                column=2,
                pady=1,
                padx=1)

    Download_B = Button(root,
                        text="Download Video",
                        command=Download,
                        width=20,
                        bg="Green",
                        pady=10,
                        padx=15,
                        relief=GROOVE,
                        font="Georgia, 13")
    Download_B.grid(row=4,
                    column=1,
                    pady=20,
                    padx=20)

# Defining Browse() to select a
# destination folder to save the video

def Browse():
    # Presenting user with a pop-up for
    # directory selection. initialdir
    # argument is optional Retrieving the
    # user-input destination directory and
    # storing it in downloadDirectory
    download_Directory = filedialog.askdirectory(
        initialdir="YOUR DIRECTORY PATH", title="Save Video")

    # Displaying the directory in the directory
    # textbox
    download_Path.set(download_Directory)

# Defining Download() to download the video

def Download():

    # getting user-input Youtube Link
    Youtube_link = video_Link.get()

    # select the optimal location for
    # saving file's
    download_Folder = download_Path.get()

    # Creating object of YouTube()
    getVideo = YouTube(Youtube_link)

    # Getting all the available streams of the
    # youtube video and selecting the first
    # from the
    videoStream = getVideo.streams.first()

    # Downloading the video to destination
    # directory
    videoStream.download(download_Folder)

    # Displaying the message
    messagebox.showinfo("SUCCESSFULLY",
                        "DOWNLOADED AND SAVED IN\n"
                        + download_Folder)

# Creating object of tk class
root = tk.Tk()

# Setting the title, background color
# and size of the tkinter window and
# disabling the resizing property
root.geometry("520x280")
root.resizable(False, False)
root.title("YouTube Video Downloader")
root.config(background="lightblue")

# Creating the tkinter Variables
video_Link = StringVar()
download_Path = StringVar()

# Calling the Widgets() function
Widgets()

# Defining infinite loop to run
# application
root.mainloop()

Generate Executable File & Setup
 Use pyinstaller to Generate executable file in python
Command:



Create Setup using Inno Setup software

Code to create Installer Setup:
; Script generated by the Inno Setup Script Wizard.
; SEE THE DOCUMENTATION FOR DETAILS ON CREATING INNO SETUP SCRIPT FILES!

#define MyAppName "Youtube Video Downloader"
#define MyAppVersion "1.0.15"
#define MyAppPublisher "Abhil group"
#define MyAppExeName "Youtube Video Downloader.exe"
#define MyAppAssocName MyAppName + ""
#define MyAppAssocExt ".md"
#define MyAppAssocKey StringChange(MyAppAssocName, " ", "") + MyAppAssocExt

[Setup]
; NOTE: The value of AppId uniquely identifies this application. Do not use the same AppId value in installers for other applications.
; (To generate a new GUID, click Tools | Generate GUID inside the IDE.)
AppId={{99805FF9-BFB4-4775-B62A-74FF1C409EAE}
AppName={#MyAppName}
AppVersion={#MyAppVersion}
;AppVerName={#MyAppName} {#MyAppVersion}
AppPublisher={#MyAppPublisher}
DefaultDirName={autopf}\{#MyAppName}
ChangesAssociations=yes
DisableProgramGroupPage=yes
; Uncomment the following line to run in non administrative install mode (install for current user only.)
;PrivilegesRequired=lowest
OutputBaseFilename=mysetup
SetupIconFile=C:\Users\Rishiraj\Desktop\python\output\Youtube Video Downloader\logo.ico
Compression=lzma
SolidCompression=yes
WizardStyle=modern

[Languages]
Name: "english"; MessagesFile: "compiler:Default.isl"

[Tasks]
Name: "desktopicon"; Description: "{cm:CreateDesktopIcon}"; GroupDescription: "{cm:AdditionalIcons}"; Flags: unchecked

[Files]
Source: "C:\Users\Rishiraj\Desktop\python\output\Youtube Video Downloader\{#MyAppExeName}"; DestDir: "{app}"; Flags: ignoreversion
Source: "C:\Users\Rishiraj\Desktop\python\output\Youtube Video Downloader\*"; DestDir: "{app}"; Flags: ignoreversion recursesubdirs createallsubdirs
; NOTE: Don't use "Flags: ignoreversion" on any shared system files

[Registry]
Root: HKA; Subkey: "Software\Classes\{#MyAppAssocExt}\OpenWithProgids"; ValueType: string; ValueName: "{#MyAppAssocKey}"; ValueData: ""; Flags: uninsdeletevalue
Root: HKA; Subkey: "Software\Classes\{#MyAppAssocKey}"; ValueType: string; ValueName: ""; ValueData: "{#MyAppAssocName}"; Flags: uninsdeletekey
Root: HKA; Subkey: "Software\Classes\{#MyAppAssocKey}\DefaultIcon"; ValueType: string; ValueName: ""; ValueData: "{app}\{#MyAppExeName},0"
Root: HKA; Subkey: "Software\Classes\{#MyAppAssocKey}\shell\open\command"; ValueType: string; ValueName: ""; ValueData: """{app}\{#MyAppExeName}"" ""%1"""
Root: HKA; Subkey: "Software\Classes\Applications\{#MyAppExeName}\SupportedTypes"; ValueType: string; ValueName: ".myp"; ValueData: ""

[Icons]
Name: "{autoprograms}\{#MyAppName}"; Filename: "{app}\{#MyAppExeName}"
Name: "{autodesktop}\{#MyAppName}"; Filename: "{app}\{#MyAppExeName}"; Tasks: desktopicon

[Run]
Filename: "{app}\{#MyAppExeName}"; Description: "{cm:LaunchProgram,{#StringChange(MyAppName, '&', '&&')}}"; Flags: nowait postinstall skipifsilent


Installation Process 
    












 

 











Project Screenshot 
First View 

 


















Paste YouTube Video Link Which one we want to download
 

















Select Destination to Save Video
 






Notification Dialog After Download Complete  














Video on Destination File 
 











Thank You  
