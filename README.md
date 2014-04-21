
Project: EvZigZag


Category: Travel Planning

Project Presentation

The proposed mobile app is targeted for people willing to use a rental or car sharing electric vehicle while
travelling. With the coming car battery range improvements it will become more common to rent an
electric vehicle when travelling.

When travelling, by opposition to regular commute, your itinerary and schedule might change from your
original plans for various reasons. For example you might be discovering a new area and want to make a
little detour to see a particular place or spent more time than expected at a museum or a restaurant. Thus the
given project name “EV Zigzag” was chosen to describe this type of travelling.

Several applications have been developed to help a driver finding local recharging stations along a trip, to
make possible reservations, and to define a timetable to include the battery charging needs. However,
when using a rental car those applications would not be able to access all the information related to
the car battery diagnostic information, because the driver is not the owner of the car.

The rental company after registering a new car with the car manufacturer will have an account allowing to
access diagnostic information. But the rental company might not be willing to provide a personalized EV
account to each new car driver for privacy and security reasons.

So a driver will need to enter manually the car battery status information to the application used
during the trip for finding and selecting a charging station. Entering battery status information will not
be very practical for most of the drivers and will not be very precise.

The proposed solution is to implement a service providing a secure interface allowing applications, used by
a driver renting an electric vehicle, to access the diagnostic information provided by the car manufacturer to
the registered rental car.


Project overview

This project will be articulated around two main projects. The first project will be a mobile client app,
running on various types of smartphones, or running directly on the electrical car internal display.

The mobile client app will be used first to enter information about the rented car to be able to access the
registered rental car diagnostic information. Second, the client app would be used to select which
application will be authorized for accessing the service and what type of information should be accessible.

The mobile client app should be able to interact with various applications used by the driver during the trip
to inform those applications about itinerary changes or up-to-date battery diagnostic information.


The second part of the project will be a server broker allowing the mobile app to securely get access to
the diagnostic information regarding the battery status.

Initially the rental company will use the secure broker to register the rental electric cars for which
diagnostic battery information will be made available.

The secure broker will then be able transfer the requests sent by the mobile client to the registered car
diagnostic information. The secured broker will then return the result of the request back to the mobile
client application.






