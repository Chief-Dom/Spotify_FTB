----------------------------------------------------------------------
Acoustics - For The Birds
----------------------------------------------------------------------

-----------------------------------
Overview:
-----------------------------------
An application accessible to every platform, this project benefits any music profesional or enthusiast by allowing them to better connect with the music in their library.   

-----------------------------------
Install Instructions:
-----------------------------------
- Clone the repository using ```git clone```
- Make a new conda enviorment with python 3
- Activate the enviorment
- ```cd``` to the top or the cloned directory

- Initialization:
   - For Mac & Linux run the command: ```python __init__.py```
   - For Windows or if your enviorment has python 2 run the command: ```python3 __init__.py```

- Navigation & Utilization of App:
   - To view the notebooks run ```jupyter notebook```, make sure your enviorment is active

-----------------------------------
Componets:
-----------------------------------
**Website**
> Made with Django, hosted using Docker

   Stack
  :-----:
| - Python |
| - Django |
  -------

**Mobile App**
>> Made with Java, hosted using Docker
>> Will eventually make a swift varient

   Stack
  :-----:
| - Java   |
| - Swift  |
  -------
  
**Our Database**  
> Must store the organized clusters of each user
>> Will do so by making the Track URI a base 62 number and performing a **radix sort**
>> Once sorted each cluster will be stored as a **binary search tree** 

> SQL will be used to locate each clients data 

> MongoDB will be used for the nodes of the tree

   Stack
  :-----:
| - SQL     |
| - MongoDB |
  -------
  
**Utility Functions**

|              Built               |
|        :------------------:      |
|  - get_track_analysis(id)        |
|  - get_track_features(id_list)   | 

               
|               Future                                |
|              :------:                               |
|  - artist_correlation_matrix(artist_id)             |
|  - generate_new_songs(artist_correlation_matrix)    | 
              
              
**Plotting & Analytics**
> This is intended to provide the user with insightful information for songs and playlists


   -------
**ML Models**

- Clustering Analysis (unsupervised)
- Song Classification, parse a playlist to find songs 


