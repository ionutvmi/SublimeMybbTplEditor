Sublime Mybb Template Editor
=============================
Sublime Mybb Template Editor will allow you to edit mybb templates directly from sublime text 3.  
The templates will be automatically updated in your database when you edit them.  

Installation
-----------------
**Via Package Control**  
Search for `Mybb Template Editor`

**Manually**  
Clone this project in your Packages folder under the name `Mybb Template Editor`.  
`git clone https://github.com/ionutvmi/SublimeMybbTplEditor.git "Mybb Template Editor"`

**Setup**
(Video Tutorial)(https://www.youtube.com/watch?v=HlUxKx8A-Xk)

1. Go to Admin CP -> Themes & Styles -> Templates -> Configure a new template
3. Go to Admin CP -> Themes & Styles -> Themes -> Configure a new template (make sure it has the proper template set defined)
3. Mark it as your default theme
4. Go to subline and install the mybb plugin
5. Go to Sublime -> Package Settings -> Mybb Plugin -> Settings user and configure the mysql credentials.
5. Access the package control (Ctrl+Shift+P) and search for mybb load template
6. Select your template, define a folder path and a new window will pop up
7. Edit your files and save them.

How to use
-----------------
Go to Preferences > Package Settings > MybbTpl and edit the settings to fit your system.  
Once that is done open the command pallete Ctrl+Shift+P and search for *Mybb Tpl: Load templates*.  
Choose the desired template set and happy coding. 

If you want to edit CSS themes: 
Ctrl+Shift+P and select Mybb Tpl: Load themes (CSS)   
Download and install the [updatecss.php](https://github.com/ionutvmi/SublimeMybbTplEditor/blob/master/updatecss.php) file on your development server.   
Set the correct url to the updatecss.php in the settings file.

Contributions
-----------------
If you find a bug or have suggestions open an issue [here](https://github.com/ionutvmi/SublimeMybbTplEditor/issues)

Donate 
-----------------
If you like my code you can support me by making a [donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=5VVJJXVFMQ9ZN)
