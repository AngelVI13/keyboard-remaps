# For linux
put `.Xmodmap` in home directory and just reboot.

NOTE: More info on remapping can be found [here](https://askubuntu.com/a/176714)
NOTE2: To see a list of current mappings run `xmodmap -pke`.

# For Windows
1. Install [MSKLC](https://www.microsoft.com/en-US/download/details.aspx?id=102134)
NOTE: Might have to install [.NET 3.5](https://www.microsoft.com/en-US/download/details.aspx?id=21)

2. Load `kb_layout.klc` in MSKLC and click `Project > Build DLL and Setup Package`
3. Go to the selected folder and run the install script.
