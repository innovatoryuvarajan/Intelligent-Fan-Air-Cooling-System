# Intelligent-Fan-Air-Cooling-System
Repository for MATLAB simulink challenge project hub sustainability and renemable energy challenge under the theme of Intelligent Fan Air Cooling System
Night-time temperatures are generally lower than daytime temperatures. We are modelling a simple fan mechanism that **pumps-in** or **extracts air** based on temperature difference between inside and outside.  
The cooler night-time air can be used to bring down the temperature of air and capacitive elements within the house. Over the course of the day, the air and the cooler structure will keep temperature lower, until it crosses the evening or night-time temperatures

# Explanation video:

[![Intelligent-Fan-Air-Cooling-System](https://img.youtube.com/vi/BMIiCEvg3oU/0.jpg)](https://www.youtube.com/watch?v=BMIiCEvg3oU)



# Real World Application of the Adopted Approach
* Step into a future where comfort meets sustainability. Our Intelligent Fan Air Cooling System isn't merely a concept; it's a revolution in home climate control.
* Imagine a home where the fan isn't simply a device; it's an intelligent companion. By utilizing night-time cool air, it actively regulates temperatures, reducing the need for energy-intensive cooling during the day.
* Why this project? It's not solely about efficiency; it's a commitment to sustainable living. The BLDC motor, powered by solar and conventional sources, signifies a shift towards cleaner, longer-lasting technology. It's not merely a motor; it's a greener tomorrow.
* what sets us apart? Our Nanocomposite paint. It's not just a coating; it's a cool embrace. By reflecting sunlight and reducing surface temperatures, it transforms homes into havens. This isn't merely paint; it's a promise of comfort in every stroke.
* Enter the Fuzzy Logic Controller. It's not merely about temperature control; it's about adapting to your lifestyle. By intelligently adjusting fan speed, it ensures a seamless blend of technology and comfort. It's not merely a controller; it's a personalized climate concierge.
* The Temperature Sensor isn't merely a gadget; it's a guardian of your comfort. Sensing shifts in temperature, it communicates with the fan, ensuring a constant, soothing environment. It's not merely a sensor; it's a silent sentinel.
* Why embark on this journey? It's not just about innovation; it's about a better quality of life. By reducing the need for full-speed operation at night, our system is a small yet impactful step towards sustainability. It's not merely a project; it's a path to a harmonious coexistence with nature.And what lies ahead? We don't merely stop; we evolve. Integrating smart grid mechanisms, IoT technology, and human density-based speed control, our vision extends beyond the ordinary. It's not merely about the fan; it's about a future where technology adapts to human needs.

# Novelty
1. We have made Nanocomposite paint coating by using **Novel magnesium oxide (MgO)-polyvinylidene fluoride (PVDF) polymer** , which comparatively provides the cooler air which is used to attain the required temperature through low power consumption.
2. Here we are using innovative fuzzy logic controller parameters and dynamic power gain parameters, hence we can able to change the RPM of the fan according to our needs.
3. We shall maintain the temperature of the room in constant throughout the day & there will be no need of operating the fan in full speed during night time. This serves as a small step towards the sustainability development. 



# Specification of BLDC fan:
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
2. The output from LM35 is fed into the fuzzy logic controller.
3. Fuzzy logic controller provides the calculated temperature value.
4. By using the calculated temperature value and power gain value we are controlling the RPM (Revolutions Per Minute) of our BLDC (Brushless Direct Current) fan.
5. The power gain values depend on  various parameters of the fan like number of wings, size of the wings, throughput from the fan, Maximum & Minimum RPM of the Fan etc.,;
6. We are using BLDC(Brushless Direct Current) which comparitively produces less heat. The BLDC Motor increases the lifespan of ceiling fan and it is also flexible to alter the RPM of the fan.
7. Here we use smart grid technology to power our fan & we paint the blades of our fan by using Nanocomposite paint,to increase the throughput of our fan.

# Fuzzy Logic Controller

* The Fuzzy Logic Controller block implements a fuzzy inference system (FIS) in Simulink®. You specify the FIS to evaluate using the FIS name parameter.

* For more information on fuzzy inference, see Fuzzy Inference Process.

* To display the fuzzy inference process in the Rule Viewer during simulation, use the Fuzzy Logic Controller with Ruleviewer block.

* Here we are using a fuzzy logic in between two areas(outdoor temperature & indoor temperature) these two different temperatures are detected by using temperature sensors(LM35)

* Temperature Sensor:
                 We are using LM 35 as temperature sensor. LM 35 is a precision
temperature sensor whose output is linearly proportional to Celsius Temperature. The LM35 is rated to operate from -55° Centigrade to 150° Centigrade with a linear scale factor of +10mv/° C

* After mesuring the temperature it will be headed to constant temperature

* And then depending upon the temperature, RPM control takes place.

* It is the main challenge to intelligent fan 

# Temperature based Speed Control of BLDC Fan

Temperature proportional speed control is accomplished using pulse width modulation(PWM). The input value of temperature is proportional to the speed, and set the calibration range according to the speed requirement.

# Coatings

![download](https://github.com/yuvieeee/Intelligent-Fan-Air-Cooling-System/assets/114850519/cbea4b9c-cd4a-46ee-9249-74cabb418ed0)


* We are introducing the specific coating for cooling system in fan blades

* By using ultra-white and ultra-emissive magnesium oxide (MgO)-polyvinylidene fluoride (PVDF) , nano-composite is being prepared from materials that are abundant on earth, cheap, non-toxic and harmless.

* Initially, polymer powders were transformed into a solution using solvent then, dielectric nanoparticles are dispersed inside the polymer matrix. After preparation, different spectroscopic techniques were used to characterize the optical properties of the prepared polymer nanocomposite paint. 

* The optimized MgO-PVDF with a dielectric nanoparticles resulted in large solar reflectance of 96.3% and a record high thermal emission of 98.5% due to Mg─O bond vibrations, and other stretching/bonding vibrations from the polymer.

* The nanocomposite paint exhibits  water-resistant hydrophobic properties and can easily be coated on stainless steel with high uniformity and good adhesion.

* “Our innovative research has led to the development of a cost-effective and environmentally sustainable paint capable of reducing surface temperatures (including buildings, tiles, pavers, etc.) by over 10°C during hot summer day.

# Further Development:
1. Power the fan by using smart grid mechanism for sustainability development.
2. Making the fan more intelligent by using iot technology.
3. Controlling the fan speed as per human density inside the room by mesuring their body temperature.

