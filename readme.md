
### ShareIt-pics

> a personal gallary and pictures to display your photos for others to see

#### Live Link

> Live preview: https://shareit3.herokuapp.com


### Author 

> by Hidri A.

### Description 

This is a web application that allows any users to view differnt photos that intersets and also,view the details such as location and also copy the link to the photo .

### User Story 

As user of the application you will be able to :
 * view differnt photos that interset uou
 * on click a single photo to expand it and views details of the phot
 * view differnt categories of photos
 * view photos based on the location they were taken
 * copy a link to the photo to share with my friends

 ## Development setup 

 To acces 

 1. Clone this repo:
 ``` gitt clone https:github.com/hidri10/Gallaray_image
 ```

 2. Move to the folder and install requirments
 ```
 cd imageshare
 pip install -r requirments.txt
 ```
3. Create the Database on psql shell 
``` SQL psql CREATE DATABASE pics;
```

4. Migrate the database and run application
```
python maange.py migrate
python manage.py runserver
```



## Technologies Used 
    Pyhton3
    Django
    Html
    Bootstrap
    Css


## Known Bags 
There are no bugs.

## Support and Contact Details
Please contact on gmail : agthidri2400@gmail.com


## Licensing 
This project is under the MIT License 2019