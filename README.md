# Geo-heatmap-using-Google-Location-history

"Google is tracking all of us.."

Let us find out ourselves.

## Installation:
Install Dependencies by running the command : ***pip install -r requirements.txt***

## Usage / Execution: 
1. Go to [Google Takeout](https://takeout.google.com/settings/takeout?pli=1) to download your location data. 
2. De-select everything and then check **Location History — JSON format**. 
3. Download your data as a zip archive, then unzip it. You should now have a JSON file on your computer that contains every instance of when your phone stored your location (which, if you have location services enabled, happens more often than you might think). Be aware that all of this might take a little while depending on how much data there is about you. I had it in GBs :astonished: !! 
4. Run the python script by: ***python geo_heatmap.py location_history.json*** and wait for a HTML page to load up in your default browser showing the heatmap of the location data google had stored in its server for **you** 

![image](https://user-images.githubusercontent.com/29462447/79127562-bf4de480-7dbf-11ea-9c41-4ab3d13cda2e.png)

**Note:**
I have also made usage of the argparse python package with which you can supply arguments by specifying dates with range - for which you want the data. Have a look at the script :smiley:
