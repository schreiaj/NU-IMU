NU-IMU
======


Designed to work with the multiwii lite board

Requires [http://www.varesano.net/files/FreeIMU-20121122_1126.zip]

If you are using the multiwii you need to modify the FreeIMU.h to look like

```
  // Uncomment the appropriated version of FreeIMU you are using
  //#define FREEIMU_v01
  //#define FREEIMU_v02
  //#define FREEIMU_v03
  //#define FREEIMU_v035
  //#define FREEIMU_v035_MS
  //#define FREEIMU_v035_BMP
  // #define FREEIMU_v04

  // 3rd party boards. Please consider donating or buying a FreeIMU board to support this library development.
  //#define SEN_10121 //IMU Digital Combo Board - 6 Degrees of Freedom ITG3200/ADXL345 SEN-10121 http://www.sparkfun.com/products/10121
  //#define SEN_10736 //9 Degrees of Freedom - Razor IMU SEN-10736 http://www.sparkfun.com/products/10736
  //#define SEN_10724 //9 Degrees of Freedom - Sensor Stick SEN-10724 http://www.sparkfun.com/products/10724
  //#define SEN_10183 //9 Degrees of Freedom - Sensor Stick  SEN-10183 http://www.sparkfun.com/products/10183
  //#define ARDUIMU_v3 //  DIYDrones ArduIMU+ V3 http://store.diydrones.com/ArduIMU_V3_p/kt-arduimu-30.htm or https://www.sparkfun.com/products/11055
  #define GEN_MPU6050 // Generic MPU6050 breakout board. Compatible with GY-521, SEN-11028 and other MPU6050 wich have the MPU6050 AD0 pin connected to GND.
```
