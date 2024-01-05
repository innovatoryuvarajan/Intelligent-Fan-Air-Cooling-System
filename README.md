# Intelligent-Fan-Air-Cooling-System
Repository for MATLAB simulink challenge project hub sustainability and renemable energy challenge under the theme of Intelligent Fan Air Cooling System
Night-time temperatures are generally lower than daytime temperatures. We are modelling a simple fan mechanism that **pumps-in** or **extracts air** based on temperature difference between inside and outside.  
The cooler night-time air can be used to bring down the temperature of air and capacitive elements within the house. Over the course of the day, the air and the cooler structure will keep temperature lower, until it crosses the evening or night-time temperatures

# Explanation video:

[![Intelligent-Fan-Air-Cooling-System](https://img.youtube.com/vi/BMIiCEvg3oU/0.jpg)](https://www.youtube.com/watch?v=BMIiCEvg3oU)



#                                   REAL WORLD APPLICABILITY OF THE APPROACH ADOPTED

1. A closed-loop controller receives power from the BLDC via an inverter.
2. Current passes through its windings to control the speed and torque of the control unit.
3. BLDC motors have higher efficiency, with low maintenance requirements. 
4. They are more stable and long-lasting.

BLDC motor runs on low current, so that it can run longer on solar, regular, and inverters.

#                                             Novelty
1. We have made Nanocomposite paint coating by using **Novel magnesium oxide (MgO)-polyvinylidene fluoride (PVDF) polymer** , which comparatively provides the cooler air which is used to attain the required temperature through low power consumption.
2. Here we are using innovative fuzzy logic controller parameters and dynamic power gain parameters, hence we can able to change the RPM of the fan according to our needs.
3. We can be able to maintain the temperature of the room in constant throughout the day & there will be no need to operate the fan in full speed during night time. This serves as a small step towards the sustainability development. 



#                                          SPECIFICATION OF BLDC FAN:
*	Air delivery-270
*	Input voltage-140-285
*	Frequency-48-52
*	Power factor-0.98
*	Bearing-ZZ shielded double ball bearing
*	Remote-speed control and booster mode.

# Block Diagram :
![Blank diagram (1)_page-0001](https://github.com/yuvieeee/Intelligent-Fan-Air-Cooling-System/assets/114850519/228e26f3-8b1c-4f0a-92e3-33bdc59b00cc)


# Block Diagram Explanation:
1. The indoor and outdoor temperature is measured using LM35 Temperature sensor.
2. The output from LM35 is feed into fuzzy logic controller.
3. Fuzzy logic controller provides the calculated temperature value.
4. By using the calculated temperature value and power gain value we are controlling the RPM (Revolutions Per Minute) of our BLDC (Brushless Direct Current) fan.
5. The power gain values depend on  various parameters of the fan like number of wings of the fan, size of the wings, throughput from the fan, Maximum & Minimum RPM of the Fan etc.,;
6. We are using BLDC(Brushless Direct Current) which comparitively produces less heat. The BLDC Motor increases the lifespan of ceiling fan and it is also flexible to alter the RPM of the fan.
7. Here we use smart grid technology to power our fan & we paint the blades of our fan by using Nanocomposite paint,to increase the throughput of our fan.

#                                           Fuzzy Logic Controller

*The Fuzzy Logic Controller block implements a fuzzy inference system (FIS) in Simulink®. You specify the FIS to evaluate using the FIS name parameter.

*For more information on fuzzy inference, see Fuzzy Inference Process.

*To display the fuzzy inference process in the Rule Viewer during simulation, use the Fuzzy Logic Controller with Ruleviewer block.

*Here we using a fuzzy logic in between two areas(outdoor temperature & indoor temperature) these two different temperatures are detected by using temperature sensors(LM35)

*Temperature Sensor:
                 We are using LM 35 as temperature sensor. LM 35 is a precision
temperature sensor whose output is linearly proportional to Celsius Temperature. The LM35 is rated to operate from -55° Centigrade to 150° Centigrade with a linear scale factor of +10mv/° C

*After mesuring the temperature it will be headed to constant temperature

*And then depending upon the temperature, RPM controls takes place.

*It is the main challenge to intelligent fan 

#                               Temperature based Speed Control of BLDC Fan

Temperature proportional speed control is accomplished using pulse width modulation(PWM). The input value of temperature is proportional to the speed, and set the calibration range according to the speed requirement.

#                                    COATINGS

![download](https://github.com/yuvieeee/Intelligent-Fan-Air-Cooling-System/assets/114850519/cbea4b9c-cd4a-46ee-9249-74cabb418ed0)


* We are introducing the specific coating for cooling system in fan blades

* By using used ultra-white and ultra-emissive magnesium oxide (MgO)-polyvinylidene fluoride (PVDF) , nano-composite is being prepared from materials that are abundant on earth, cheap, non-toxic and harmless.

*Initially, polymer powders were transformed into a solution using solvent then, dielectric nanoparticles are dispersed inside the polymer matrix. After preparation, different spectroscopic techniques were used to characterize the optical properties of the prepared polymer nanocomposite paint. 

*The optimized MgO-PVDF with a dielectric nanoparticles resulted in large solar reflectance of 96.3% and a record high thermal emission of 98.5% due to Mg─O bond vibrations, and other stretching/bonding vibrations from the polymer.

* The nanocomposite paint exhibits  water-resistant hydrophobic properties and can easily be coated on stainless steel with high uniformity and good adhesion.

*“Our innovative research has led to the development of a cost-effective and environmentally sustainable paint capable of reducing surface temperatures (including buildings, tiles, pavers, etc.) by over 10°C during hot summer day.

# Further Development:
1. Power the fan by using smart grid mechanism for sustainability development.
2. Making the fan more intelligent by using iot technology.
3. Controlling the fan speed as per human density inside the room by mesuring their body temperature.

