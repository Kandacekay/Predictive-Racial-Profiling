# Predictive-Racial-Profiling

For the Data Cleaning(Dren LaPhayne)
I used several references for the portions consisting of (conversion of Lat/Lon, datetime, convert_time also a refresher for converting files into MongoDB friendly files links below):
https://gis.stackexchange.com/questions/78838/converting-projected-coordinates-to-lat-lon-using-python
https://www.geeksforgeeks.org/python-datetime-module/, https://www.programiz.com/python-programming/datetime
https://www.programcreek.com/python/?CodeExample=convert+time, https://stackoverflow.com/questions/71613686/how-to-convert-time-to-datetime-now
https://stackoverflow.com/questions/24890979/python-convert-object-into-json-for-mongodb

I started first with shaving some columns by opening all of the Excel files individually(which led me to removing 2014 excel file as it was giving me issues combination wise).
Then I went into python to combine all of the files once I had their headers named the same and then did further cleaning upon renaming several columns, converting the Arrest Date & Time to date and 12hr time formats. I also converted the Y and X coordinates into Lat and Lon for Kandace to easily have it plotted in the future and that did take some looking into to fix properly.

I ended up redoing the process after starting it to make sure the processes were in the right spots and able to be used as they should. It took a few hours as there was a lot of touch and go, a lot of small errors during the cleaning process. I used Excel, Jupyter Lab & Notebook will be used to pass the MongoDB files. 
