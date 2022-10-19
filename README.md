# blood-bank-system
It is a blood bank system made using django

## Overview and Features

### There are 3 user rules in this
- Patient role
- Donor role
- Admin role

## Features for Patient
##### Patient can create blood request
![image](https://user-images.githubusercontent.com/66880935/196764941-6f1c507c-59a7-42de-90a1-b47e3b109c32.png)
##### Patient can see his requests history
![image](https://user-images.githubusercontent.com/66880935/196765358-926334db-cebc-474c-99c5-be26c199cdcf.png)
##### Patient can see number of requests he created, pending requests for approval, number of approaved requests, number of rejected requests
![image](https://user-images.githubusercontent.com/66880935/196765619-85c27379-d0bb-47a3-8673-be16fb59791c.png)

## Features for Donor

##### Donor has all the features that patient has like creating blood request, see request history etc...
##### Donor can apply to donate blood
![image](https://user-images.githubusercontent.com/66880935/196766352-2035eb5b-1309-4599-b78b-0c8072eebefe.png)
##### Donor can see donate history
![image](https://user-images.githubusercontent.com/66880935/196767129-3893ff62-9c8f-425b-89ad-c267aa6421e9.png)

## Features for Admin

##### Admin can see all the data like
- How much amount of each blood type is available and total blood in ml
- Number of requests made by patients and donors
- Number of Donors
![image](https://user-images.githubusercontent.com/66880935/196768039-a4f320b0-d57e-460d-af20-5dc847d5db60.png)

##### Admin can see Donors details and change their details too
![image](https://user-images.githubusercontent.com/66880935/196768504-8fd8d2cc-c4ba-4380-ac83-7043e930cda4.png)

##### Admin can see Patients details and change their details too
![image](https://user-images.githubusercontent.com/66880935/196768617-e97c05a6-d959-421f-8ac7-cf0fea3da270.png)

##### Admin can approve or reject Donor's requests and if approved Donor's blood quantity will be automatically added to total blood
![image](https://user-images.githubusercontent.com/66880935/196768915-5bf8e02b-f675-48d4-8823-d8c652483f86.png)

##### Admin can approve or reject Patients blood requests and admin can approve only when database has that type of blood and in required quantity
![image](https://user-images.githubusercontent.com/66880935/196769989-53c2cc0a-3dc0-41b9-876c-26012aa8ce27.png)

##### Admin can update the blood stock manually
![image](https://user-images.githubusercontent.com/66880935/196770239-e96dac91-80dd-4061-968a-f8611286fc9d.png)

# How to run this project ?

``` 
1) git clone https://github.com/yvrjprshr/blood-bank-system.git
2) pip install -r requirements
3) python manage.py makemigrations
4) python manage.py migrate
5) python manage.py runserver
6) open http://127.0.0.1:8000/ 
7) create users and interact with website
```

# Tech Stack
> HTML, CSS, JS, Django, sqlite
