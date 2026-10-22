# BMET2922-PulseTouch1

#include <Arduino.h>
#include <BluetoothSerial.h>
#include <Wire.h>
#include <LiquidCrystal_I2C.h>
#include <math.h>

//Connections
const int PULSE_PIN  = 25;
const int BUTTON_PIN = 33;
const int LED_PIN    = 32;

const int LCD_SDA = 13;
const int LCD_SCL = 14;
