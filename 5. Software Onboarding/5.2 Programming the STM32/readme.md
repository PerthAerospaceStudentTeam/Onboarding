# Programming the STM32
The STM32 family of microcontrollers is primarily what we use as the flight computer. 

## First Project 
This will walk you through the steps required to create a simple STM32 Project that blinks one of the onboard LEDs. A more detailed tutorial that includes the setup and use of additonal hardware features can be found on the sharepoint [here]().  
1. Download and install STM32CubeIDE: https://www.st.com/en/development-tools/stm32cubeide.html
2. Once the install process has finished, launch the software and create a new STM32 Project. You may need to wait a few minutes while it downloads additional files.

![416148429-8c01b131-5703-4244-b378-b4c4ad4bd95f](https://github.com/user-attachments/assets/c74385df-d6e5-4fb9-97da-23ff34e397a1)

3. Enter the part number into into the search bar (L432KC) and select the nucleo board then click "Next >".

![image](https://github.com/user-attachments/assets/9a8dc436-9441-4a8a-b14f-9fb5a5db6107)

![image](https://github.com/user-attachments/assets/ba0da2a9-aec2-4de3-8cde-e519f5ae7eea)

4. Give the project a name. Something that includes the part number and function is recommended. e.g. "L432KC_Blink"
5. Keep the options at their default values and click "Finish". You may need to wait while it downloads all the API files. 

![416167364-21bd9539-7b54-4635-9061-74c1eab86d6a](https://github.com/user-attachments/assets/1c9704e3-4274-421e-9ce5-6a1d422aaa3f)

Once the project has been created you will be presented with the Pinout & Configuration screen. We need to do some additional setup before we can start running code. 

6. On the left side of the window, expand the "System Core" catagory and click on "SYS"
7. Select the "Debug" dropdown and select "Serial Wire". Notice that two of the pins on the diagram have turned green and been assigned to SWDIO and SWCLK respectively.

![image](https://github.com/user-attachments/assets/2cefb839-2d18-4671-aacd-abe89a490e17)

8. 

Steps to include
- Pin assignment 
- Configure clock 
- Code to toggle LED
- Debug mode and running code
- Finding information in reference manuals?  

## Video Resources
- [Getting Started with STM32 and Nucleo](https://youtube.com/playlist?list=PLEBQazB0HUyRYuzfi4clXsKUSgorErmBv&si=6eI9FrAluDvCqMZy) the first video in the series is similar to the above tutorial. Be aware that they are using a different nucleo board so the pin configuration will differ.
