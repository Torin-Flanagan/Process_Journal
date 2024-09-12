# Responsive Design and Technology Task 2 #
### Mobile Web App That Displays An Overview Of Key Components When Riding a Bike/Motorbike ###

## 1. Conceptualisation ##
### 1.1 Design Intent ###
Summary: A web app that can be used by a user through a website address, then asking for permission to use the user's phone/device's geographic location, camera, and gyroscope for input. As a result, the web app will then be able to produce an output displaying the speed, which is calculated through obtaining the time travelled from point A - point B, along with presenting a display of the current lean/tilt angle. Lastly, it is key as prior knowledge that this web app can be used for anything bike/motorbike related due to the the app utilising the user's geographic location, camera, and gyroscope from their phone while riding a bike/motorbike. It should also be noted that a bike/motorcycle involved activity is not the only situation when this web app can be used, other examples could include using the web app while sailing, flying, snowboarding, etc.

### 1.2 Research ###
Through using research of other similiar project found on the web, it has helped to gain a deeper understanding of what myself, Sean, and Jay are aiming to achieve for the project, along with how we are going to do so. Research found during this phase will greatly affect what we aim to create paired with each phase during development. This will include how we develop the web interface, how this interface communicates with the user's phone, and what informational components of the user's phone we are aiming to extract data from? The influence of this research will be seen more apparent later within this process journal.

### 1.2.1 Related Project 1 ###

![Alt text](./Images/Smart_Wheelchair.webp)

This project utilises a similiar concept as the concept we have devised ourselves. However, differences with the smart wheelchair incldue that the wheelchair iteslef comes with built-in sensors on the seat, collecting data every second in the background of the patient using the wheelchair. Data collected from this wheelchair then provides insight into the patient's seatin behaviours and the energy the patient requires in order to maintain correct posture. Another possible variation to this smart wheelchair could be to adapt fall detection so that the patient in the wheelchair knows when the wheelchair could possibly fall, giving time to call for assistance. These key features of the smart wheelchair then allow people to monitor the patient from a remote location, or more realistically when they are out of reach from that patient. A Possible idea from this project that could be interpreted into ours is being able to remotely access the data obtained, no matter where you are.

**Reference:** Deshpande, C. (2020, December 21). Top 10 Ultimate Internet of Things (IoT) Projects. Simplilearn.com. https://www.simplilearn.com/internet-of-things-iot-projects-article

### 1.2.2 Related Project 2 ###

![Alt text](./Images/Road%20Sense.gif)

The following project integrates a smartphone application designed to estimate road conditions using data from the accelerometer, gyroscope, and GPS. According to the research, machine learning techniques are applied to predict road quality based on this data. By leveraging the RoadSense app, the need for specialized vehicle sensors was eliminated, making the solution more scalable. The goal of the app is to provide users with real-time information on road conditions before they travel, potentially contributing to improved road infrastructure. The study highlights that combining data from the gyroscope and accelerometer proved to be the most effective approach, as these sensors can detect vehicle movements caused by potholes, rough surfaces, and other road irregularities. This insight is highly relevant to our project, as the accelerometer and gyroscope are effective in detecting sudden movements such as shakes, bumps, and tilts. These factors are essential characteristics of bike and motorbike usage, potentially making these sensors highly beneficial for advancing our project. 

**Reference:** Allouch, A., Koubaa, A., Abbes, T., & Ammar, A. (2017). RoadSense: Smartphone Application to Estimate Road Conditions Using Accelerometer and Gyroscope. IEEE Sensors Journal, 17(13), 4231–4238. https://doi.org/10.1109/jsen.2017.2702739

### 1.2.3 Related Project 3 ###

![Alt text](./Images/Portraits_Nebula.webp)

The third related project utilises the use of a camera in order to mimic the appearance of the user of the artwork, a similiar ideology of a mirror, but instead of a refelction the artwork uses flip-discs (small dime-size circles that can rotate 60 times per second usining electromagnets). Portraits Nebula is the name of the artwork and is summarised as an interactive kinetic artwork that uses customised flip-discs, when you engage with the artwork it will use a camera to record a breif clip of the interactions the user performs while being recorded. It then plays these cpatured interactions at a later time, eventually cycling through every portrait captured while the artwork/device has been initiated. In relation to our web app project, the artwork utilises the advantage of a camera in a similiar approach to our design which could possibly include snapshotting/recording interactions the user performs while using the web app.

**Reference:** Digital Kinetic Artwork - Portraits by BREAKFAST. (2024, July 16). BREAKFAST. https://breakfaststudio.com/works/portraits-nebula

### 1.2.4 Related Project 4 ###
‌
![Alt text](./Images/Asteroid_Suit.webp)

As seen above, the name of the suit is Ceres and it is a grey, jumpsuit like wearable technology that from afar looks like it just randomly vibrates as the user walks around with the jumpsuit on. However, in more detail the jumpsuit is equipped with small buzzers located near the user's shoulder blades and back, providing a buzz like sensation to the user's skin. The contributor as to why these buzzers are occuring on the users shoulder blades and back is due to the jumpsuit having microcontrollers connected to NASA's Near Earth Object API where these vibrations are indications of asteroids nearing Earth's orbit. It is quite clear that this related project is an example of how you can use geographic location of anything to then display in another form, with this example it is showing how the use of NASA's API obtains the geographic locations of asteroids near Earth's orbit, indicated by the jumpsuit lighting up and vibrating. With an example like this, it shows how open minded you can be in regards to using geographic location as a means to display any other form of responsive design. In relation to our project, an extended possibility using geographic location could be having the users phone record tracks and paths the user follows for furutre reference through similiar use with an API.

**Reference:** Plaugic, L. (2018, April 14). These three designers make wearables that measure the world around you. The Verge. https://www.theverge.com/2018/4/14/17233430/wearable-media-fashion-tech-nyc-ceres-jumpsuit-interactive

### 1.2.5 Related Project 5 ###

![Alt text](./Images/Human_Gyroscope.png)

Implementation of a gyroscope was created which could rotate 360 degrees in all dimensions, being controlled with a software-GUI paired with some type of joystick. Implementation of this project consists in the field of simulators such as a plane simulator, the design focuses on a gyroscopic view paired with software development, the prototype is more so seen as an idea for future investors who wish to apply this theology with a full scale, real-time used model, being much larger in price and scale. Regarding our project, this ideology can be used when considering the use of a gyroscope with the design, it will be viewed as treated in a similiar manner as seen in this example. The key difference however would be the implmentation of this gyroscopic use being obtained from the user's phone which then displays the user's tilt angle on the web app. In future development there could also be more extended use with a gyroscope such as utilising it for gesture-based navigation, motion controls, integrated augmented reality features responding to the user's movements, and etc.

**Reference:** Svensson, M. and Johannesson, J. (2013). The Human Gyroscope. [PDF] p.45. Available at: https://www.diva-portal.org/smash/get/diva2:647956/FULLTEXT01.pdf [Accessed 8 Sep. 2024].

### 1.2.6 Related Project 6 ###

![Alt text](./Images/Device_Orientation_API.jpg)

The above image displays a simple web page that displays the z-axis, x-axis, and y-axis of the user's phone once permission has been granted to use the device's hardware. An Inertial Measurement Unit (IMU) is used for the webpage, an IMU combines 3-axis accelerometers with 3-axis gyroscopes, and sometimes 3-axis magnetometers to then get a more accurate display of the device's orientation. On top of this, the IMU used does onboard analysis, combining these different sensors applied with signal processing to then produce a smooth and useful signal as the final output. The way this API works is that an event listener is added and listens for the event type 'deviceorientation', the event itself contains three variables represetning the z-axis, x-axis, and y-axis. From this the event handler then simply updates the text readouts of these rotation values as a web app. This API is highly valuable for our project, as one of our core components(being the gyroscope) relies directly on the Device Orientation API, together with geographic location and camera functionality, the gyroscope forms a key element of our web app's design. It is most likely that this Device Orientation API will be used in our project as it meets exactly the needs we require for the gyroscope aspect of the web app, however, we will then try to edit and improve this API's functionality and appearance to better suit our web app's needs.

Here is the link to access the live web app: https://tgifford-usc.github.io/WebAPIExamples/

**Reference:** Log In to Canvas. (2024). Usc.edu.au. https://learn.usc.edu.au/courses/27670/pages/8-dot-2-%7C-device-orientation-api?module_item_id=632692

### 1.2.7 Related Project 7 ###

![Alt text](./Images/Media_Capture_API.png)

Similiar to Related Project 6, this image showcases another simple web page but instead it displays a live camera (top) that when the 'Take photo' button is pressed, the web page takes a photo of the user and displays the photo in a static form (bottom). However, this web page doesn't save the photos and only holds the most recent photo taken once the 'Take photo' button has been triggered. This webpage operates by treating the device's cameras as video cameras, generating a live video stream directly from the camera. 
The process begins by using the Media Capture API to access the camera's video stream. This stream is then attached to an HTML video element, allowing for the display of the live feed, extraction of individual frames, or both. A final step involves rendering a captured video frame onto an HTML canvas element, converting it to an image format, such as PNG. From there, the captured frame can be manipulated or processed in any desired way. In relation to our mobile web app, the Media Capture API will also most likely be used due to the API showcasing very similiar results to what we are aiming to design for the web app. However, this API will be modified and adapted to better suit the needs of our web app, but it is hard to tell what these changes could include to the Media Capture API as of this stage in the design.

**Reference:** Log In to Canvas. (2024). Usc.edu.au. https://learn.usc.edu.au/courses/27670/pages/8-dot-3-%7C-media-capture-api?module_item_id=632693

### 1.2.8 Related Project 8 ###

![Alt text](./Images/Geolocation_API.png)

Once again another API is being used here, however, this time it is the use of a Geolocation API that displays your current latitude and longitiude once the 'Show my location' button has been pressed on a simple web app. This web page is extremely simple just like the last two APIs, leaving a lot of room to add and customise the API to better suit our web app project. The way this API works is that the user's location is described using the GeolocationPosition object instance, which contains a GeolocationCoordinates object instance inside. There are only two things contained within the Geolocation instance, a coords property which includes the GeolocationCoordinates instance and a timestamp property holding a timestamp (given as Unix time in milliseconds of when the position data was obtained). Inside the GeolocationCoordinates instance there are a number of properties, but the two being used are the latitude and longitude, other bits of information you can obtain from the GeolocationCoordinate's object include altitude, speed, what direction the device is facing, and accuracy measures of the altitude, longitude, and latitude data. For our web app project, this API satisfies the requirements for geographic location functionality but will need adjustments and modifications to align more closely with our desired outcomes, additionally it must be optimized to integrate seamlessly with the rest of our web app.

**Reference:** Using the Geolocation API Web APIs, MDN. (n.d.). Developer.mozilla.org. https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API/Using_the_Geolocation_API






‌