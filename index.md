## Welcome to the Urban Belonging Toolkit

On this page you will find the links to all relevant code to setup your own version of the Urban Belonging app or work with the resulting data from the app. 

### Setting up your own app and server
Code and more detailed information on setting up your own version of the Urban Belonging app can be found [here](<-- link to UB app github -->)

**Server**

The back-end server consists of two parts. 
1. The back-end server api handles all traffic from the mobile application. Additionaly, there are endpoints for the admins to export the data gathered using the app. The exports can be used to further work with the data. For example using the notebooks shown later on this page. THe code and a more detailed explanation on how to setup the API can be found [here](https://github.com/Urban-Belonging/urbanbelonging-api). 

2. An image processor handling the resizing of thumbnails, uploads to S3 compatible storage and finally returning the URLS of the uploaded images. The code and a more detailed explanation on how to setup the API can be found [here](<-- link to UB image processer github -->)


### Working with the data

Python notebooks have been made available to use as a starting point to work with the data from the app:

- [Converting JSON to CSV file and aggregate data statistics](https://github.com/Urban-Belonging/UB-scripts/blob/main/Data%20preperation/convertJsonToCSV.ipynb)
- [Download all pictures to seperate folder on your system](https://github.com/Urban-Belonging/UB-scripts/blob/main/Data%20preperation/photosToFolders.ipynb)
- [Converting the location tracking data](https://github.com/Urban-Belonging/UB-scripts/blob/main/Data%20preperation/convertRouteData.ipynb)
- [Creating Gephi networks based on the slider and tag data](https://github.com/Urban-Belonging/UB-scripts/blob/main/Gephy%20networks/Urban%20Belonging%20networks%2023-09-2021.ipynb)
- [Creating small cards (for print) containing relevant data for each photo to be used in workshop settings](https://github.com/Urban-Belonging/UB-scripts/blob/main/Workshop%20Content/createPhotoCards.ipynb)
![Workshop 1 example](/assets/example_1_cards)
![Workshop 2 example](/assets/example_2_cards)


