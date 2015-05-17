# osatranscoder
A folder action script that will invoke HandbrakeCLI and the app Identify to streamline download/encode/tagging workflows.

The script will automatically traverse downloaded folders and discover transcoding eligible files. It will invoke HandbrakeCLI with a fixed quality setting of 20 and when the encode is finished, hand off the file to [Identify.app](http://identify2.arrmihardies.com) for tagging.


To use, edit the script in Script Editor and update the new_file_name variable to the desired destination path. Save the file to "/Library/Script/Folder Action Scripts/"

Then right click on your downloads folder and select "Services->Folder Actions Setup", then select "transcode file.scpt", then click "Attach"