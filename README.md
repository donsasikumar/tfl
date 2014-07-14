tfl
===
This application suggests the best route to go from one location to another, in London.

Initially, the user is prompted to enter the pickup point at which the application lists the transport services in that area.Then the user selects one of the listed services. To this, the application responds with a list of drivers registered drivers.

Once the user selects a driver, the app displays the driver's review records.

After this the user is prompted to select the destination. So the user enters the destination.
At this, the application creates and plots a map of all stations and routes registered between them.

Then the app determines and displays the best path to reach the given destination from the source along with the distance.
At this point, the user needs to enter their registered username before proceeding.
The applicat also displays the best tariff for that Journey after applying available discounts.

The discounts applied considers the date and time of journey along with other user specific discounts.

Displayed below in the console debug information from running the application. [User Input is prefixed with **]


Enter pickup point[eg:Enter LV - London Victoria/LWL - London Waterloo/EU - London Euston/..] :

**LV

List of local transport services at London Victoria
Victoria Transport Services1
Victoria Transport Services2
Victoria Transport Services3
Victoria Transport Services4

Select Service [1/2/3/..] :

**1

List of registered Transporters from this area ..
Driver{licenseID='1'}
Driver{licenseID='2'}
Driver{licenseID='3'}
Driver{licenseID='4'}
Driver{licenseID='5'}

Select Driver [1/2/3..] :

**2

Driver{licenseID='3'}
ReviewRecord{author='Very good'}
ReviewRecord{author='good'}
ReviewRecord{author='Bad'}
ReviewRecord{author='Average'}
ReviewRecord{author='Very bad'}

Enter pickup point[eg:Enter LV - London Victoria/LWL - London Waterloo/EU - London Euston/..] :

**EU

INFO: Destination station:EU
EU
me='Euston'}

Suggested Route :
Station{stationCode='LV', stationName='Victoria'}
Station{stationCode='GP', stationName='Greenpark'}
Station{stationCode='OC', stationName='OxfordCircus'}
Station{stationCode='WS', stationName='Warrenstreet'}
Station{stationCode='EU', stationName='Euston'}

Total distance :22.0

Enter Username [user1/user2/..]:

**user1

Existing User :User{name='user1', address='BuckinghamPalace', cardDetails='goldcard', age=2}
Fare before discount :52.8

Fare after datetime discounts :44.0
INFO: Applying discount for NETWORK-RAILCARD
Fare after user discounts :7.919999999999999
INFO: Applying discount for FAMILY-RAILCARD
