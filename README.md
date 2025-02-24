# **Bidirectional Counter Using Arduino and IR Sensors**

🚪 Welcome to the Bidirectional Counter Project Repository\!

This project demonstrates how to create a simple yet efficient bidirectional counter system using Arduino and IR sensors. The counter detects whether a person is entering or exiting through a single entry/exit point and updates the count accordingly. The real-time count is displayed on an LCD screen, making it a perfect DIY automation solution for monitoring people in restricted spaces.


📝 **Project Overview**

The bidirectional counter uses two IR sensors placed strategically to determine the direction of movement. By identifying the sequence in which the sensors are triggered, the system can differentiate between an entry and an exit. An Arduino board processes the sensor data and updates the counter, which is displayed on an LCD.

This project is great for gaining hands-on experience with:

* IR sensor interfacing  
* Arduino programming  
* I2C LCD Display controlling  
* Simple embedded system design


🛠 **Components Required**

* **Arduino Uno:** Microcontroller board for processing sensor data  
* **IR Sensors (2x):** To detect the direction of movement  
* **16x2 LCD I2C Display:** To display the real-time counter value  
* **Jumper Wires:** For electrical connections  
* **Breadboard:** For prototyping  
* **12V Power Supply:** power source for Controller, Display and Sensors


⚙️ **Installation and Setup**

1. **Clone the Repository:**  
* git clone https://github.com/YogeshwaranP-05/Bidirectional-Counter-using-IR-Sensors.git  
* cd Bidirectional-Counter-using-IR-Sensors

2. **Connect Components:**  
* Connect the IR sensors to the digital pins of the Arduino.  
* Connect the LCD display to the Arduino (use I2C module for simpler wiring).  
* Power up the system with a 5V supply.  
    
3. **Upload the Code:**  
* Open **`Bidirectional_counter-1.ino`** in the Arduino IDE.  
* Select the appropriate board and COM port.  
* Upload the code to your Arduino.

4. **Run the System:**  
* Place the IR sensors at the entry/exit point.  
* Observe the real-time counter updates on the LCD as people enter and exit.


📝 **Code Explanation**

* **IR Sensor Reading:** The code continuously monitors the state of both IR sensors.  
* **Direction Detection:** Based on the order in which sensors are triggered, the code determines entry or exit.  
* **Counter Update:** The count increases on entry and decreases on exit.  
* **LCD Display:** The counter value is displayed and refreshed in real time.


🤝 **Contributing**

We welcome contributions\! Feel free to fork this repository, enhance the project, and submit a pull request.


🧩 **License**

This project is licensed under the GNU GPL V3.0 License. See the **`LICENSE`** file for details.


📧 **Contact**

For any queries or suggestions, reach out to our Official Website: [www.circuitdigest.com](http://www.circuitdigest.com).

Happy coding and creating\! 🚀

