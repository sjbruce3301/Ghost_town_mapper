# Ghost_town_mapper
 Scrapes Wikipedia pages for ghost town coordinates & status for export to Google Maps.

This script runs through Wikipedia pages listing ghost town coordinates in a particular state. To use, upload the URL of the wikipedia page. The script will scrape for all names, coordinates, and 'status' (what remains). Right now it's pretty clunky -- I manually set the correct columns of information for status (cell 7) so make sure to check that on the page, otherwise it will grab the wrong info.

LINK TO UPDATED MAP: https://www.google.com/maps/d/u/0/edit?mid=1tWOJrzlgUPMqd6tvaSc9LB-JA-V7qKE&ll=38.805789084345314%2C-101.4890324502883&z=7

The script generates the contents of a KML file that can be uploaded to Google Maps to plot. It outputs a link to a temp KML file, which you can open and then manually save to your computer. Then go to My Google Maps, and import the KML file.

An example KML file is included of the ghost town list in CO.

***Update: not all Wikipedia pages are laid out the same with coordinates, will be adding scrapers for other states using other websites. Eventually adding a function to mark as visited or not.

Feel free to reach out & request a particular state, or just a finished .kml file if you don't want to run the script yourself!