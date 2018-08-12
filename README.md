# shubhodeepForSkylark



ABOUT THE ASSINGMENT

1 parse the data in srt file

2 push the data into array by making objects  eg.({longitude:73.434234,latitude:"19.00213212",start:100 end:200})

3 traverse the folder of images and get the metadata of the images and    convert the  coordinates into a proper decimal format  or degree format

4 make an array of objects of all the images 

5 compare the srt data from the metadata by calculating the distance  between them  all the images less than 35 meters make a dictionary
 eg.({key:value}) where the key will be the time and value will be an array of filenames that are within 35 meters in that sec

6 store the data in CSV file

7 check the asssets file  


INSTRUCTIONS TO USE THE CODE:

1. python has been used in this project
2. library that has been used of python 
	
	->pysubs (for parsing the subtitle)
	
	->piexif (extracting the metadata)
	
	->geopy.distance   (calculate the distance between 2 coordinates)
	
	->pandas(to update a column in CSV file)

3.file   srtData.py has  the code to parse the srt file
4 file metaDta.py has the code  to extract the data from images folder
5. calculate distance between the coordinates using the file calculateDistance.py
6.file writeOnCsv.py  has the code to write the data on CSV file
7. file   readcsvFile.py to read the data from assests.csv and update the image_names column      
8.all the data has been save to mycsv.csv for the first assignment (35m range)
9.all the files are inside skylark folder
10. all the path has been used as per the folder


HOW TO RUN THE CODE:

1.open the  file writeOnCsv.py this is main file which needs to be run inorder to store the data in csv file 

2.to check the results open mycsv.csv and assets.csv  


