# QuadX_2560happymodel_PIDAutoCHN_V6
/*
project_QuadX_2560happymodel_PIDAutoCHN_V6

1. Automatic  Takeoff 

2. Landing

3. GPS Position Hold

by: tinnakon kheowree  

tinnakon_za@hotmail.com

tinnakonza@gmail.com

http://quad3d-tin.lnwshop.com/

https://www.facebook.com/tinnakonza

date: 22-12-2557(2014)  V.1 QuadX_2560 GY86_PIDAuto_V1

date: 28-12-2557(2014)      QuadX_2560 GY86_PIDAuto_V2   ,Write P-PID Controller

date: 28-12-2557(2014)      QuadX_2560 GY86_PIDAuto_V3   ,Ultrasonic and baro ,,Ultrasonic max 0.8 m change to Baro

date: 30-12-2557(2014)      QuadX_2560 GY86_PIDAuto_V4   ,tuning P-PID Controller

date: 31-12-2557(2014)      QuadX_2560 GY86_PIDAuto_V5   ,tuning Altitude Hold , Position Hold

support:  Board MWC Mega 3.0 flight control

http://quad3d-tin.lnwshop.com/product/26/mwc-mega-3-0-flight-control

• Atmega2560

• MPU6050 Gyro Accelerometer //400kHz nois gyro +-0.05 deg/s , acc +-0.04 m/s^2

• MS561101BA Barometer

• HMC5883L Magnetometer //400kHz

• GPS BS-300

• Ultrasonic Sensor Module

• ESC Dargon 30A

• motor sunny 2212 1400kv 

Quad4-X

---------motor---------

int MOTOR_FrontL_PIN = 2;

int MOTOR_FrontR_PIN = 5;

int MOTOR_BackL_PIN = 6;

int MOTOR_BackR_PIN = 3;

----------rx-----------           
#define THROTTLEPIN                1  //PIN 62 =  PIN A10

#define ROLLPIN                    2  //PIN 63 =  PIN A8

#define PITCHPIN                   0  //PIN 64 =  PIN A9

#define YAWPIN                     3  //PIN 65 =  PIN A11

#define AUX1PIN                    4  //PIN 66 =  PIN A12

#define AUX2PIN                    5  //PIN 67 =  PIN A13

#define AUX3PIN                    6  //PIN 68 =  PIN A14

#define AUX4PIN                    7  //PIN 69 =  PIN A15
*/
