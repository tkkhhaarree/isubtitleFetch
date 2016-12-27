# isubtitleFetch
<h3>A python script which downloads subtitles for all movies present in a specified folder.</h3>
This script first cleans the filename from keywords like 720p, hdrip, bluray etc to make it fit for searching on isubtitles.net,<br>
then from the results displayed, it picks the file name and subtitle file link, and finally downloads it for user.<br> <br>
Edit subtitle finder.py line 5 to the location where you keep your movies, then run the script and wait for it to run completely. subtitles will be downloaded in .rar format in the same folder which you specified. Extract the files and enjoy watching movies!
<br><br>
<B>Note: you need to have requests and Beautifulsoup module installed for running this script<br>
to install them, open cmd, change current directory to Scripts folder in your python installation directory, then type:<br>
'pip install requests' and,
'pip install bs4' one by one (without quotes) and wait for installation to complete.
