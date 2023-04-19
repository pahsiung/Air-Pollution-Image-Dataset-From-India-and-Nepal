# India-and-Nepal-Air-Pollution-Image-Dataset

***Introduction:***
This dataset contains images of Air Pollution for different cities in India and Nepal.

**Cities of India**

1. ITO, Delhi
2. Dimapur, Nagaland
3. Spice Garden, Bengaluru
4. Knowlede Park III, Greater Noida
5. New Ind Town, Faridabad
6. Borivali East, Mumbai
7. Oragadam, Tamil Nadu

**City of Nepal**
1. Biratnagar

The dataset is divided into two folders: Combined_Dataset and Country_wise_Dataset.

Total number of images: 12,240

***Combined dataset:***

The combined dataset folder contains two subfolders.
1. All_img: This subfolder contains all the collected images from all AQI classes.
2. IND_and_NEP: This subfolder contains six different subfolders representing six different classes of AQI.

**Air Quality Index Class**
1. a_Good
2. b_Moderate
3. c_Unhealthy_for_Sensitive_Groups
4. d_Unhealthy
5. e_Very_Unhealthy
6. f_Severe

The csv file in this folder contains all the data and its parameters.
It is labeled as

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class

***Country_wise_Dataset:***

This folder contains two subfolders representing the countries from which the dataset was collected.

1. India: 
This subfolder contains the subfolder representing the names of all cities from where data were collected.
Each subfolder of cities contains folders representing the data collected for each respective AQI class, as well as a csv file.
which contains the details of each image, like we mentioned above.
Such as,

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class


2. Nepal: 
We managed to collect the image dataset from Nepal.
This subfolder contains the subfolder representing the name of the city from where data were collected.
This subfolder of the city contains folders representing the data collected for each AQI class and also a csv file.
which contains the details of each image, like we mentioned above.
Such as,

Location, Filename, Year, Month, Day, Hour, AQI, PM2.5, PM10, O3, CO, SO2, NO2, and AQI_Class

////////////////////////////////////////////////////////////////////////////////


****Instructions on how to use the AQI image dataset:****

1. Download the dataset from Kaggle and extract the zip file to a folder of your choice.

2. The dataset is divided into two folders: the Combined_Dataset and Country_wise_Dataset. 
Each folder contains subfolders and CSV files.

3. To access the images in the Combined_Dataset folder, go to the folder corresponding to the class of AQI you are interested in.
For example, if you are interested in the 'Unhealthy' class, go to the 'Unhealthy' folder. Inside this folder,
You will find a number of images representing different cities.

4. To access the data in the Country_wise_Dataset folder, go to the folder of the country you are interested in, either India or Nepal.
Inside each country folder, you will find subfolders representing different cities.
Each city folder contains a CSV file that lists the AQI values and other parameters for the city.

5. You can use this dataset to train machine learning models to predict AQI for different cities.
You can also use it for research on air pollution in different cities.

6. If you use this dataset for any purpose, please cite it as the source of the data in any publications or presentations.
resulting from the use of this dataset.

///////////////////////////////////////////////////////////////////////////

***Data Distribution for Each AQI Class***
![Data Distribution](https://user-images.githubusercontent.com/111570911/232965276-6c7e5726-308c-478d-a9cd-3654de8a3835.png)


/////////////////////////////////////////////////////////////////////

**Contributers**
1. Adarsh Rouniyar
2. Sapdo Utomo
3. Dr. John A.
4. Dr. Pao-Ann Hsiung


If you have any queries, please do contact us.
1. Adarsh Rouniyar

Email: adarsh@csie.io

2. Dr. John A.

Email: johnmtech@gmail.com 
