# About The Project
Are you freezing and the landlord isn’t responding to your texts and phone calls?  We are proposing a way to alert the landlord without you having to pick-up your phone or fill out a complaint online form.  The application will be registered with the city, and hopefully in the future we will move to having direct access to the cities information system network. The Coolit system will alert the landlord when temperatures inside drop below the regulated temperatures set by the NY Housing Preservation and Development Department; therefore, prompting an increase to the heating levels indoors.

New York City require landlords to keep a stable temperature indoors between October 1st to May 31st, i.e. “Heat Season”.  During the hours of 6a-10pm landlords must keep the living area 68°, when the temperature outside drops below 55°; and during the hours of 10p-6a the temperature must remain 55° or higher inside when temperatures reach below 40° outside. As this may not seem like an impossible task, there are those who may not adhere to this mandate.  For many NYC tenants who are: unsuccessful with contacting their landlord, fear repercussions from landlords, unaware of tenant rights, and are tired of the run around from landlords; this unique system will do the hard work. 


## Buildings less than six units:
Tenants will be able to purchase the device and install in their unit if the building has less than six units.  The device can be mounted on the wall or placed on a flat smooth surface to properly read temperatures inside the home. It needs to be placed in a centralized location away from windows and heating sources.  The device will have a product number that will need to be registered on the the Coolit website along with tenant’s information. Each heat read monitor will have an on/off switch, to deactivate during the summer months and/or days when tenants will be gone for extended periods of time.  This will ensure the landlord will not be pinged for violations during the mandated winter periods.


### How does it work:
The landlord and tenant will be alerted simultaneously, every eight hours, totaling 24 hours. A “violation warning” text will be sent to both parties informing of the temperature inside compared to the temperature outside and the location; during the specified months and times. If the temperature is not adjusted within 24hrs, a “violation warning” will be sent directly to the 311-website complaint center. The temperature sensors will have its own personal management capability software, with the ability to submit complaint forms.  It will be a smart temperature device. The automatic alert will replace the older method of submitting a complaint via phone or web, by populating tenants’ information providing location and landlord registration information.  HPD will attempt to contact your building's managing agent to advise them that a complaint has been filed and that a violation may be issued if the condition is not corrected immediately. HPD will also attempt to call you back to see if the condition was corrected. If you indicate that the condition was corrected, HPD will close the complaint.


## Buildings more than six units:
The city and privately owned buildings with more than six units will provide temperature sensors installed in a central location in each unit, and connected to a centralized device management system.  Just as in an individual unit, the sensors will monitor the temperature inside during the “Heat Season”, and will need to be placed in a centralized location away from windows and heating sources. There will be a centralized management system per building and sensors for each apartment. Each device will have a product number that will need to be registered on the Coolit website and management system, complete with apartment number and building information.  The centralized management system will automatically deactivate during the summer months, June 1st-September 30th. 


### How does it work:
If the temperature drops below the mandated degree set by HPD, an alert will be sent to the landlord. The “violation warning” will go out three times during a 24-hour period, and if the issue is not rectified, a complaint will be submitted to the 311-website center.   With the centralized management system, it will be able to effectively send unified warnings to 311 (i.e. if more than one apartment has a heating violation, the violations will be compiled into one complaint listing the affected apartments). This will in turn limit the unnecessary traffic that 311 receives about heat complaints and by showing the severity of issues associated with the building, by compiling the data. All the devices will send its readings to the centralized management system, which will handle the communication to 311 and the landlord. It is through this system that will track and determine which apartments are not in compliance, and submit the appropriate complaint form, through an automatic form filler that will list the affected apartments. HPD will attempt to contact your building's managing agent to advise them that a complaint has been filed and that a violation may be issued if the condition is not corrected immediately. HPD will also attempt to call you back to see if the condition was corrected. If you indicate that the condition was corrected, HPD will close the complaint.


## Landlord gone wild:
Imagine coming in from battling the cold weather outside, only to find it just as cold inside.  The only way to crank up the heat is to contact your landlord, hope he answers and defrost your place before your plants die from frostbite. You make the dreaded phone call, followed by a text an hour later, then another phone call. After hours of trying to reach your landlord, you have given up hope that you will have heat for the night. Twenty-four hours has passed and still no heat.  You’ve given up on the landlord by placing a complaint with 311 and now waiting for a response. The old way involves either calling or filling out a four-step form online.  The amount of time it takes to reach someone on the phone or fill-out and submit the form is a very daunting and unappealing task.  The Coolit system will become the middleman for your heating woes. 


## Wireframes for project:


## Technologies Used:
*  HTML
*   CSS
*   JavaScript
*   Node.js
*   SQL
*   Twilio
*   Open Weather Map API
*   Temperature Sensor
*   Intel Edison w/Arduino Expansion Board
*   Cisco Meraki (possible hardware implementation of the centralized management system) or Software solution for the control system


## Installation instructions for dependencies:
This project includes a package.JSON file which provides details for the above dependencies and others. These files are imported into the node_modules folder by Node Package Manager. 
*   Download or clone repo.
*   Run npm install in terminal.
*   Run npm start from terminal.


## Build Strategy:

### Planning Stages:
*   Connecting Edison to Expansion Board 
*   Connecting Temperature Sensor to Analog connector in this case A0
*   Convert Analog readings into actual temperatures
*   Analog  Celsius  Fahrenheit
*   Connect backend to Weather API to fetch outdoor temperature
*   Set restrictions that both indoor and outdoor temperatures meet the condition for the complaint to be filed for the periods between October 1st to May 31st 
*   6a-10p; 68° indoors, 55° outdoors
*   10p-6a; 55° indoors, 40° outdoors
*   Implement Twilio 
*   Automatic form filler to match 311 complaint website


## Unsolved problems or major hurdles team had to overcome:
*   Due to the lack of time, we were unable to build a functioning application by deadline, because we spent a lot of time working with the hardware and compatibility issues.  
*   We experienced issues with MRAA module/LIBMRAA0 not connecting properly and setting up the XDK server port.


## Possible Future Improvements:

### In no particular order, we would like to add:
*   Provide the service to different metropolitan cities, with their city mandate information
*   Provide an overall temperature monitoring system for all seasons, to always to check on love ones regardless of the season
*   Nursing homes, daycares, etc.


## Authors:
1. Shantel
2. Sky
3. Quin

### Contributing Designers: 
Michaela and Po



