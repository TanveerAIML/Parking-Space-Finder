# Parking-Space-Finder

A Parking Space Finder is a system that uses various technologies to automatically count the number of vehicles parked in a designated area, such as parking lot or a parking garage. The system typically includes cameras and image processing software that can identify and track vehicles as they enter and exit the parking area. The data is then used to provide real-time information about the numberof available parking spaces, which can be displayed on a moniter or website for the public to view. The system can also store data on a parking usage over time to help identity paterns and trends in parking demand.

There are different types of parking space finder but this project is based on video-based system. It uses cameras to capture the images of the paarked cars, then the system use image processing techniques to detect and track the cars and provide the count.

There are some reasons why this system may be needed:-
1. <b>Managing parking demand:</b> By counting the number of cars in a parking lot, the system can help parking lot operators and city officials understand the demand for parking in a given area. This information can be used to create more efficient parking policies, such as adjusting the rates for parking meters based on the time of the day or the number of available spaces.
2. <b>Imporving trafic flow:</b> By providing real-time information about the number of available parking spaces, the system can help drivers make more informed decisions about where to park. This can reduce traffic congestion and improve the flow of vehicles in and out of the parking lot.
3. <b>Identifying trends:</b> By collecting data on parking usage over time, the system can help identify patterns and trends in parking demand. This information can be used to make decisions about future development and infrastructure improvements, such as adding more parking spaces or building new parking garages.
4. <b>Enhancing customer experience:</b> By providing real-time parking availability information to customers, it can help them to make better decisions and also save time. This can lead to enhanced customer experience and satisfaction.
5. <b>Smart city integration:</b> The system can be integrated with other smart city infrastructure, such as traffic lights and public transportation systems to optimize the overall transportation experience.
6. <b>Revenue generation:</b> By providing accurate parking occupancy data, it can help the parking operator to optimize the pricing strategy, it can also help to identify the revenue-generating and non-revenue generating parking spots.

These are just a few examples of how a parking space finder system can be used in the real-world.

### Below you will found the piece of my work:-
https://user-images.githubusercontent.com/74559160/212773280-a879e11f-63a2-4415-96e6-69f8574caa48.mp4

Steps to create parking space finder:-
1. Uses <b>cv2</b> and <b>pickle</b> library to collect the position of the parking spaces.
2. Image processing techniques to identify and trackcars as they enter and exit the parking lot. Object detection technique is used to track the cars.
3. With different functions of cv2 to capture the data of parking space. Functions like <b>cvtColor, GaussianBlur, and adaptiveThreshold</B>.
4. <b>Cvzone</b> library to put text related to parking space availability.
<br>

The goal of a parking space finder system is to provide accurate and real-time information about the number of available parking spaces to help drivers find a spot to park, and to help parking lot operators and city officials manage parking demand more efficiently.
