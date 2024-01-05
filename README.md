# Intelligent-Fan-Air-Cooling-System
Repository for MATLAB simulink challenge project hub sustainability and renemable energy challenge under the theme of Intelligent Fan Air Cooling System
Night-time temperatures are generally lower than daytime temperatures. we are modelling a simple fan mechanism that **pumps-in** or **extracts air** based on temperature differential between inside and outside.  
The cooler night-time air can be used to bring down the temperature of air and capacitive elements within the house. Over the course of the day, the air and the cooler structure will keep temperatures lower, until it crosses the evening or night-time temperatures

#                                   REAL WORLD APPLICABILITY OF THE APPROACH ADOPTED

1. A closed-loop controller receives power from the BLDC via an inverter.
2. Current passes to its windings to control the speed and torque of the control unit.
3. BLDC motors have high efficiency, with low maintenance requirements. 
4. They are more stable and long-lasting.

BLDC motor runs on low current so can run longer on solar, regular, and inverters.

#                                             Novelty
1. We made Nanocomposite paint coating by using **Novel magnesium oxide (MgO)-polyvinylidene fluoride (PVDF) polymer** , comparatively provides the cool air which is used to attain the required temperature by low power consumption.
2. Here we using innovative fuzzy logic controller parameters and dynamic power gain parameters, thus we can able to change the RPM of the fan based on our needs. 


#                                          SPECIFICATION OF BLDC FAN:
•	Air delivery-270
•	Input voltage-140-285
•	Frequency-48-52
•	Power factor-0.98
•	Bearing-ZZ shielded double ball bearing
•	Remote-speed control and booster mode.

# Block Diagram :
![Blank diagram (1)_page-0001](https://github.com/yuvieeee/Intelligent-Fan-Air-Cooling-System/assets/114850519/228e26f3-8b1c-4f0a-92e3-33bdc59b00cc)


# Block Diagram Explanation:
1. Measures the indoor and outdoor temperature by using LM35 Temperature sensor.
2. The output from LM35 is feed into fuzzy logic controller.
3. Fuzzy logic controller provides the calculated temperature value.
4. By using the calculated temperature value and power gain value we controlling the RPM(Revolutions Per Minute) of our BLDC(Brushless Direct Current) fan.
5. The power gain values depends on the various parameters of the fan like Number of wings of the fan, Size of the wings, Throughput from the fan, Maximum & Minimum RPM of the Fan and etc;
6. we use BLDC(Brushless Direct Current) for comparitly less heat generated in BLDC Motor hence its increases lifespan of ceiling fan and also flexible to alter the RPM of the fan.
7. Here we use smart grid technology to power our fan & we painting the blades of our fan by using Nanocomposite paint coation,to increase the throughput of our fan.

#                                           Fuzzy Logic Controller

*The Fuzzy Logic Controller block implements a fuzzy inference system (FIS) in Simulink®. You specify the FIS to evaluate using the FIS name parameter.

*For more information on fuzzy inference, see Fuzzy Inference Process.

*To display the fuzzy inference process in the Rule Viewer during simulation, use the Fuzzy Logic Controller with Ruleviewer block.

*Here we using a fuzzy logic in between two areas(outdoor temperature & indoor temperature) these two different temperatures are detected by using temperature sensors(LM35)

*Temperature Sensor:
                 We are using LM 35 as temperature sensor. LM 35 is a precision
                temperature sensor whose output is linearly proportional to
                Celsius Temperature. The LM35 is rated to operate from -55°
                Centigrade to 150° Centigrade with a linear scale factor of +10mv/° C

*After mesuring the temperature it will headed to constant temperature

*And then dependimg upon the temperature RPM controls takes part

*It is the main challenge to intelligent fan 

#                               Temperature based Speed Control of BLDC Fan

Temperature proportional speed control is accomplished using pulse width modulation(PWM). The input value of temperature is proportional to the speed, and set the calibration range according to the speed requirement.

#                                    COATINGS

![download](https://github.com/yuvieeee/Intelligent-Fan-Air-Cooling-System/assets/114850519/cbea4b9c-cd4a-46ee-9249-74cabb418ed0)


* We introducing the specific coating for cooling system in fan blades

* By using used ultra-white and ultra-emissive magnesium oxide (MgO)-polyvinylidene fluoride (PVDF) nano-composite prepared from materials that are earth abundant, cheap, non-toxic and non-harmful

*Initially, polymer powders were transformed into a solution using solvent and then, dielectric nanoparticles are dispersed inside the polymer matrix. After preparation, different spectroscopic techniques were used to characterize the optical properties of the prepared polymer nanocomposite paint. 

*The optimized MgO-PVDF with a dielectric nanoparticles resulted in large solar reflectance of 96.3% and a record high thermal emission of 98.5% due to Mg─O bond vibrations, and other stretching/bonding vibrations from the polymer

* The nanocomposite paint exhibited water-resistant hydrophobic properties and can be easily coated on stainless steel and so on with high uniformity and good adhesion

*“Our innovative research has led to the development of a cost-effective and environmentally sustainable paint capable of reducing surface temperatures (including buildings, tiles, pavers, etc.) by over 10°C during hot summer day.
