<link href="stylesheet.css" rel="stylesheet"></link>

# <p style="text-align: center;">Local Movie Database</p>
## <p style="text-align: center;">Will Dargan</p>
## <p style="text-align: center;">Summer 2024</p>
<div class="page"></div>

## Contents
<ul class="leaders">
    <li><span>1 - Abstract</span><span><strong>3</strong></span></li>
    <li class="nested">
        <ul class="leaders inner">
            <li><span>1.1 - Features</span><span><strong>3</strong></span></li>
            <li><span>1.2 - Libraries</span><span><strong>3</strong></span></li>
            <li class="nested">
                <ul class="leaders inner">
                    <li><span>1.2a - SQLite3</span><span><strong>3</strong></span></li>
                    <li><span>1.2b - Tkinter</span><span><strong>3</strong></span></li>
                </ul>
            </li>
        </ul>
    </li>
</ul>
<div class="page"></div>

## 1 - Abstract
This program provides a GUI wrapper for searching and editing an SQLite3 database storing data about any number of films the user wishes to store. The program is set up in a portable design by default, however file paths can be changed by the user at a later date. The program also allows for a number of aesthetic customisations by the user.
### 1.1 - Features
This program includes the following features:
1. A table with which the user may view a number of records of the database.
   * Includes anchored headings for each column
   * Scrollable JiT loaded records from the database
2. A menubar which provides access to a separate settings menu and save and load functionality.
3. A separate menu for changing global settings.
   * The ability to change save locations
   * The ability to edit the database schema
   * The ability to change the appearance of the app
### 1.2 - Libraries
The libraries used to interface with the database and produce the GUI are both included in Python's standard library. These are SQLite3 and Tkinter respectively. Other libraries may ultimately be used in the development of this project, however the two aforementioned libraries will definitely feature in the final program.
#### 1.2a - SQLite3
This library is a Python wrapper for the original SQLite C module. It provides classes and methods for interfacing with a local disk stored database and does not require a separate server to host the database itself. Due to this nature, SQLite is suited to small, fast-access databases making it perfect for this sort of application.
#### 1.2b - Tkinter
The inclusion of Tkinter in the Python standard library and the fact that it is a wrapper for a C library means that there is plenty of documentation available for all of the included features. The library also uses a simple system of customisable preset widgets which makes the creation of small interactive applications quick and easy. Given the narrow scope of this project, Tkinter should be a perfect choice for a GUI library.
<div class="page"></div>

## 2 - Basic Database Design
<div class="page"></div>

## 3 - UI Design
<div class="page"></div>

## 4 - Development