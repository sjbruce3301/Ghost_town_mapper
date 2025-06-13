# Ghost_town_mapper
 Scrapes Wikipedia pages for ghost town coordinates & status for export to Google Maps

This script runs through Wikipedia pages listing ghost town coordinates in a particular state. To use, upload the URL of the wikipedia page. The script will scrape for all names, coordinates, and 'status' (what remains). Right now it's pretty clunky -- I manually set the correct columns of information for status (cell 7) so make sure to check that on the page, otherwise it will grab the wrong info.

The script generates the contents of a KML file that can be uploaded to Google Maps to plot. I am using a temp file because the path was not writable for me. It outputs a link to the temp KML file, which you can open and then manually save to your computer. Then go to My Google Maps, and import the KML file.

If the KML file link isn't working, just change the script to print the KML contents, then copy and paste into a text file, and save as .kml

An example KML file is included of the ghost town list in CO.