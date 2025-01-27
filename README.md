# Bus-Ticketing-and-Payment-System-using-AWS-Cloud
# Passengers can buy bus or railway tickets on our platform. We are using AWS EC2 service for that.


-First we go through to the AWS maagement console
![Screenshot (3)](https://github.com/user-attachments/assets/547a792c-bfa4-4a43-9a0e-60121c0460db)


-Now, search for EC2(elcastic cloud compute) service in search bar
![Screenshot (4)](https://github.com/user-attachments/assets/306f87ad-e50b-4758-af6f-1c3385e60af3)

![Screenshot (5)](https://github.com/user-attachments/assets/f6f7e1c2-5d97-4846-a2d1-3bc52e56a1eb)


-Create an Instance named by railway for the windows AMI(amazon machine image).
![Screenshot (6)](https://github.com/user-attachments/assets/b7ef1d90-c54a-4481-8e99-46580b2410f1)


-Connect instance using RDP client, for that we need administrator and password. So decrypt the password from .pem file and then connect instance and after connect we'll get the windows OS on separate window.
![27 01 2025_00 11 55_REC](https://github.com/user-attachments/assets/d3d10ecb-4264-4a1a-b4cf-6171ee9d875f)


-After connecting, download the XAMPP from internet explorer.
![27 01 2025_00 17 45_REC](https://github.com/user-attachments/assets/79059b57-8d09-4bdf-87bb-21a773a740c0)

![27 01 2025_00 18 53_REC](https://github.com/user-attachments/assets/a49199dc-9194-487c-abc3-5bd7276e3271)


-By following the below path of file, copy the source code in that folder. The source code is also attached here.
path:- C:\xampp\htdocs\Mumbai-Local-Train-Ticket-Booking-main
![27 01 2025_00 20 43_REC](https://github.com/user-attachments/assets/0ccb1279-7abc-4c8a-97e7-eb2bea50b426)

![27 01 2025_00 21 06_REC](https://github.com/user-attachments/assets/9171401e-3249-433e-995d-feb06c0234b9)

![27 01 2025_00 21 31_REC](https://github.com/user-attachments/assets/1d06251b-4c78-4db7-a9a9-4e3b20da1020)

![27 01 2025_00 22 21_REC](https://github.com/user-attachments/assets/793f89ff-ad98-481a-a646-07e26ffa518b)


-After that, open XAMPP and start Apache and MySql module.
![27 01 2025_00 26 10_REC](https://github.com/user-attachments/assets/8e3efa5d-fed3-4e91-aadc-cd77fc6fc655)


- Go to the admin of the xampp and then the xampp dashboard wil open.
![27 01 2025_00 26 30_REC](https://github.com/user-attachments/assets/be6278b1-6de4-42e0-8456-f9c8f80109cb)

![27 01 2025_00 26 48_REC](https://github.com/user-attachments/assets/a7515853-7554-461b-bd61-598cee95551a)


- Click on the phpMyAdmin of that dashboard and create new database named by train.
![27 01 2025_00 27 42_REC](https://github.com/user-attachments/assets/25a990ee-5872-4bfe-96ec-5fe9034346de)

![27 01 2025_00 28 17_REC](https://github.com/user-attachments/assets/83314f47-de0c-4e90-8be7-6e18b53add06)


-Then import the train.sql file which is in the source code.
![27 01 2025_00 28 45_REC](https://github.com/user-attachments/assets/a36da778-b088-4f22-bc6a-8a351dc6af1c)

![27 01 2025_00 28 45_REC](https://github.com/user-attachments/assets/5f17b839-4d1e-454f-bf1c-f4efb6032a8e)

![27 01 2025_00 31 13_REC](https://github.com/user-attachments/assets/020c6853-357d-44d5-a1b5-982f8f4e10fd)


-After this, open new web page and type localhost/Mumbai-Local-Train-Ticket-Booking-main at there.
![27 01 2025_00 33 27_REC](https://github.com/user-attachments/assets/07aa02ca-137b-4b7f-873f-d442de76880b)


-Here we have created our Bus Ticket or Railway Ticket booking application with the payment system, Bus Schedules, Train Schedules, etc.
![27 01 2025_00 34 07_REC](https://github.com/user-attachments/assets/2ac3db29-0946-4099-a8be-4cabc72516d3)

![27 01 2025_00 36 16_REC](https://github.com/user-attachments/assets/93da21fb-77a9-48dc-b0a3-95e9e2989d7e)

![27 01 2025_00 37 24_REC](https://github.com/user-attachments/assets/8662fbee-e51a-487a-afd4-49cab57da0a5)

![27 01 2025_00 38 07_REC](https://github.com/user-attachments/assets/ae5ccfa4-a2eb-4072-bb46-ddc2484b2b48)

![27 01 2025_00 38 56_REC](https://github.com/user-attachments/assets/1f4bf830-e5fd-497f-b16c-c754b80944f5)

![27 01 2025_00 39 15_REC](https://github.com/user-attachments/assets/2d71020a-313a-48fa-86da-2e691f4ae3df)

![27 01 2025_00 39 37_REC](https://github.com/user-attachments/assets/5d415c11-b25e-4933-a0c1-c8325d9c8d9f)

![27 01 2025_00 39 51_REC](https://github.com/user-attachments/assets/809cd1d3-03f0-4b8b-9e53-d5e7fb344aa9)

# That's it.....! We have cretaed a Ticket Booking and Payment application using AWS EC2 instance.
