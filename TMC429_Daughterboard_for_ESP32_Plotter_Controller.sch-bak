EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "TMC429 Daughterboard for ESP32 Plotter Controller"
Date "2021-02-20"
Rev "A"
Comp "Mark Benson"
Comment1 "github.com/markjb/TMC429_Daughterboard_for_ESP32_Plotter_Controller"
Comment2 ""
Comment3 "Daughterboard deisgn to fit RevA 'Diamond Chimp'"
Comment4 "Designed to test the TMC429 monition controller BOB"
$EndDescr
$Comp
L custom:TMC2130 U1
U 1 1 6027F176
P 2250 2100
F 0 "U1" H 2675 1278 50  0000 C CNN
F 1 "TMC2130" H 2675 1189 47  0000 C CNN
F 2 "custom:StepstickTMCv2" H 2350 2100 50  0001 C CNN
F 3 "" H 2350 2100 50  0001 C CNN
	1    2250 2100
	1    0    0    -1  
$EndComp
$Comp
L custom:TMC2130 U2
U 1 1 6027FEC0
P 5350 2100
F 0 "U2" H 5775 1278 50  0000 C CNN
F 1 "TMC2130" H 5775 1189 47  0000 C CNN
F 2 "custom:StepstickTMCv2" H 5450 2100 50  0001 C CNN
F 3 "" H 5450 2100 50  0001 C CNN
	1    5350 2100
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x08_Male J1
U 1 1 6028123A
P 1650 2400
F 0 "J1" H 1500 2550 50  0000 C CNN
F 1 "X Stepper A" H 1350 2400 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical" H 1650 2400 50  0001 C CNN
F 3 "~" H 1650 2400 50  0001 C CNN
	1    1650 2400
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x08_Male J2
U 1 1 60283A69
P 3750 2500
F 0 "J2" H 3722 2382 50  0000 R CNN
F 1 "X Stepper B" H 3700 2300 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical" H 3750 2500 50  0001 C CNN
F 3 "~" H 3750 2500 50  0001 C CNN
	1    3750 2500
	-1   0    0    1   
$EndComp
$Comp
L Connector:Conn_01x08_Male J4
U 1 1 6028A8DE
P 4750 2400
F 0 "J4" H 4650 2400 50  0000 C CNN
F 1 "Y Stepper A" H 4500 2300 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical" H 4750 2400 50  0001 C CNN
F 3 "~" H 4750 2400 50  0001 C CNN
	1    4750 2400
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x08_Male J5
U 1 1 6028ABFC
P 6750 2500
F 0 "J5" H 6722 2382 50  0000 R CNN
F 1 "Y Stepper B" H 6722 2473 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical" H 6750 2500 50  0001 C CNN
F 3 "~" H 6750 2500 50  0001 C CNN
	1    6750 2500
	-1   0    0    1   
$EndComp
$Comp
L custom:TMC429-BOB U3
U 1 1 6028C968
P 5400 4800
F 0 "U3" H 6075 5000 50  0000 C CNN
F 1 "TMC429-BOB" H 5850 3700 50  0000 C CNN
F 2 "custom:TMC429-BOB" H 5400 4800 50  0001 C CNN
F 3 "" H 5400 4800 50  0001 C CNN
	1    5400 4800
	1    0    0    -1  
$EndComp
Wire Wire Line
	5350 2700 5250 2700
Wire Wire Line
	3100 2100 3500 2100
Wire Wire Line
	3100 2200 3400 2200
Wire Wire Line
	3100 2300 3550 2300
Wire Wire Line
	3100 2400 3550 2400
Wire Wire Line
	3100 2500 3550 2500
Wire Wire Line
	3100 2600 3550 2600
Wire Wire Line
	5150 4900 5400 4900
Wire Wire Line
	2250 2600 1900 2600
Wire Wire Line
	6200 2100 6500 2100
Wire Wire Line
	6200 2200 6400 2200
Wire Wire Line
	6200 2300 6550 2300
Wire Wire Line
	6200 2400 6550 2400
Wire Wire Line
	6200 2500 6550 2500
Wire Wire Line
	6200 2600 6550 2600
Wire Wire Line
	6200 2700 6300 2700
Wire Wire Line
	6200 2800 6400 2800
Wire Wire Line
	5350 2600 4950 2600
Text Notes 2500 925  0    50   ~ 0
X Motor
Text Notes 5625 900  0    50   ~ 0
Y Motor
Text Notes 7375 6350 0    50   ~ 0
Left limit on Pin 3, Right on Pin 4\n
Connection ~ 5150 4900
Text Notes 9700 5900 0    50   ~ 0
REF1 = X Left\nREF2 = Y Left\nREF3 = Z Left\nREFR1 = X Right\nREFR2 = Y Right\nREFR3 = Z Right
Wire Wire Line
	1850 2200 2200 2200
Wire Wire Line
	1850 2300 2100 2300
Wire Wire Line
	2250 2500 2000 2500
Wire Wire Line
	1850 2100 2250 2100
Wire Wire Line
	4950 2100 5000 2100
Wire Wire Line
	4950 2200 5300 2200
Wire Wire Line
	4950 2300 5200 2300
Wire Wire Line
	4950 2500 5350 2500
Wire Wire Line
	2200 2200 2200 1200
Connection ~ 2200 2200
Wire Wire Line
	2200 2200 2250 2200
Wire Wire Line
	2100 2300 2100 1200
Connection ~ 2100 2300
Wire Wire Line
	2100 2300 2250 2300
Wire Wire Line
	2000 2500 2000 1200
Connection ~ 2000 2500
Wire Wire Line
	2000 2500 1850 2500
Wire Wire Line
	5400 5200 4650 5200
Wire Wire Line
	5400 5300 4650 5300
Wire Wire Line
	5400 5400 4650 5400
Text Label 4650 5300 0    50   ~ 0
MOSI
Text Label 4650 5400 0    50   ~ 0
MISO
Text Label 4650 5200 0    50   ~ 0
SCK
Text Label 2100 1200 3    50   ~ 0
SCK
Text Label 2200 1200 3    50   ~ 0
MOSI
Text Label 2000 1200 3    50   ~ 0
MISO
Wire Wire Line
	1850 2400 2250 2400
Wire Wire Line
	4950 2400 5100 2400
Text Notes 1750 3550 0    50   ~ 0
TMC429 SPI Chip Select (was X_Dir)
Text Notes 1750 3750 0    50   ~ 0
TMC429 Interrupt (was X_Step)
$Comp
L Device:C C1
U 1 1 602A71A9
P 4700 4600
F 0 "C1" H 4815 4646 50  0000 L CNN
F 1 "100n" H 4815 4555 50  0000 L CNN
F 2 "Capacitor_SMD:C_0805_2012Metric" H 4738 4450 50  0001 C CNN
F 3 "~" H 4700 4600 50  0001 C CNN
	1    4700 4600
	1    0    0    -1  
$EndComp
Wire Wire Line
	4700 4750 4700 4900
Wire Wire Line
	4700 4900 5150 4900
Wire Wire Line
	5400 4800 5300 4800
Wire Wire Line
	5300 4800 5300 4450
Text Notes 2850 4750 0    50   ~ 0
3v3 operation requires a 100n\ncap between 3v3 and gnd.\n5v line connected to 3v3.
Wire Wire Line
	5350 3150 5350 2800
Wire Wire Line
	5250 3150 5250 2700
Wire Wire Line
	4950 2800 4950 3150
Wire Wire Line
	4950 2700 5050 2700
Wire Wire Line
	5050 2700 5050 3150
Wire Wire Line
	3100 2800 3400 2800
Wire Wire Line
	1850 2800 1850 3150
Wire Wire Line
	1950 2700 1950 3150
Wire Wire Line
	1850 2700 1950 2700
Wire Wire Line
	2250 2800 2250 3150
Wire Wire Line
	2250 2700 2150 2700
Wire Wire Line
	2150 2700 2150 3150
Text Label 2150 3150 1    50   ~ 0
X_Step
Text Label 2250 3150 1    50   ~ 0
X_Dir
$Comp
L custom:TMC2130 U4
U 1 1 602EC41B
P 8350 2100
F 0 "U4" H 8775 1278 50  0000 C CNN
F 1 "TMC2130" H 8775 1189 47  0000 C CNN
F 2 "custom:StepstickTMCv2" H 8450 2100 50  0001 C CNN
F 3 "" H 8450 2100 50  0001 C CNN
	1    8350 2100
	1    0    0    -1  
$EndComp
Wire Wire Line
	8350 2700 8250 2700
Text Notes 8775 925  0    50   ~ 0
Z Motor
Wire Wire Line
	8350 3150 8350 2800
Wire Wire Line
	8250 3150 8250 2700
Wire Wire Line
	3400 2800 3400 2200
Connection ~ 3400 2800
Wire Wire Line
	3400 2800 3550 2800
Connection ~ 3400 2200
Wire Wire Line
	3400 2200 3550 2200
Wire Wire Line
	4650 5100 5400 5100
Wire Wire Line
	5400 5500 4650 5500
Wire Wire Line
	4650 5700 5400 5700
Text Label 4650 5500 0    50   ~ 0
CLK_429
Text Label 4650 5700 0    50   ~ 0
INT_429
Text Label 4650 5100 0    50   ~ 0
CS_429
Text Label 1950 3150 1    50   ~ 0
INT_429
Text Label 1850 3150 1    50   ~ 0
CS_429
Text Label 4950 3150 1    50   ~ 0
CLK_429
Wire Wire Line
	6300 5700 6850 5700
Wire Wire Line
	6300 5600 6850 5600
Wire Wire Line
	6300 5500 6850 5500
Wire Wire Line
	6300 5400 6850 5400
Wire Wire Line
	6300 5300 6850 5300
Wire Wire Line
	6300 5200 6850 5200
Wire Wire Line
	5300 2200 5300 1200
Connection ~ 5300 2200
Wire Wire Line
	5300 2200 5350 2200
Wire Wire Line
	5200 2300 5200 1200
Connection ~ 5200 2300
Wire Wire Line
	5200 2300 5350 2300
Wire Wire Line
	5100 2400 5100 1200
Connection ~ 5100 2400
Wire Wire Line
	5100 2400 5350 2400
Text Label 5100 1200 3    50   ~ 0
MISO
Text Label 5200 1200 3    50   ~ 0
SCK
Text Label 5300 1200 3    50   ~ 0
MOSI
Text Label 5250 3150 1    50   ~ 0
Y_Step
Text Label 5350 3150 1    50   ~ 0
Y_Dir
Text Label 8250 3150 1    50   ~ 0
Z_Step
Text Label 8350 3150 1    50   ~ 0
Z_Dir
Wire Wire Line
	5000 2100 5000 1200
Connection ~ 5000 2100
Wire Wire Line
	5000 2100 5350 2100
Wire Wire Line
	8350 2100 7600 2100
Wire Wire Line
	8350 2200 7600 2200
Wire Wire Line
	8350 2300 7600 2300
Wire Wire Line
	8350 2400 7600 2400
Wire Wire Line
	8350 2500 7600 2500
Wire Wire Line
	1900 2600 1900 1200
Connection ~ 1900 2600
Wire Wire Line
	1900 2600 1850 2600
Wire Wire Line
	8350 2600 7600 2600
Wire Wire Line
	9200 2800 9350 2800
Wire Wire Line
	9200 2700 9800 2700
Wire Wire Line
	9200 2200 9350 2200
Wire Wire Line
	9200 2100 9350 2100
Wire Wire Line
	6500 2100 6500 1200
Connection ~ 6500 2100
Wire Wire Line
	6500 2100 6550 2100
Wire Wire Line
	6400 2200 6400 1200
Connection ~ 6400 2200
Wire Wire Line
	6400 2200 6550 2200
Wire Wire Line
	6400 2200 6400 2800
Connection ~ 6400 2800
Wire Wire Line
	6400 2800 6550 2800
Wire Wire Line
	9350 2200 9350 2800
Connection ~ 9350 2200
Wire Wire Line
	9350 2200 9800 2200
Connection ~ 9350 2800
Wire Wire Line
	9350 2800 9800 2800
$Comp
L Connector:Conn_01x04_Male J7
U 1 1 6037A51B
P 9800 2500
F 0 "J7" H 9772 2382 50  0000 R CNN
F 1 "Z Motor" H 9772 2473 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Horizontal" H 9800 2500 50  0001 C CNN
F 3 "~" H 9800 2500 50  0001 C CNN
	1    9800 2500
	-1   0    0    1   
$EndComp
Wire Wire Line
	9200 2300 9600 2300
Wire Wire Line
	9200 2400 9600 2400
Wire Wire Line
	9200 2500 9600 2500
Wire Wire Line
	9200 2600 9600 2600
Text Label 6400 1200 3    50   ~ 0
GND
Text Label 6500 1200 3    50   ~ 0
VMOT
Text Label 9800 2100 2    50   ~ 0
VMOT
Text Label 9800 2200 2    50   ~ 0
GND
Text Label 7600 2200 0    50   ~ 0
MOSI
Text Label 7600 2300 0    50   ~ 0
SCK
Text Label 7600 2500 0    50   ~ 0
MISO
Text Label 7600 2400 0    50   ~ 0
CS_Z
Text Label 5050 3150 1    50   ~ 0
CS_Z
Text Label 7600 2600 0    50   ~ 0
DCO
Text Label 1900 1200 3    50   ~ 0
DCO
Text Label 3400 1200 3    50   ~ 0
GND
Wire Wire Line
	3500 2100 3500 1200
Connection ~ 3500 2100
Wire Wire Line
	3500 2100 3550 2100
Wire Wire Line
	3100 2700 3300 2700
Wire Wire Line
	6300 2700 6300 1200
Connection ~ 6300 2700
Wire Wire Line
	6300 2700 6550 2700
Wire Wire Line
	3400 2200 3400 1200
Wire Wire Line
	3300 2700 3300 1200
Connection ~ 3300 2700
Wire Wire Line
	3300 2700 3550 2700
Text Label 3500 1200 3    50   ~ 0
VMOT
Text Label 3300 1200 3    50   ~ 0
3v3
Text Label 6300 1200 3    50   ~ 0
3v3
Text Label 9800 2700 2    50   ~ 0
3v3
Text Label 9800 2800 2    50   ~ 0
GND
Text Label 5000 1200 3    50   ~ 0
EN
Text Label 7600 2100 0    50   ~ 0
EN
Text Label 6850 5700 2    50   ~ 0
X_Step
Text Label 6850 5600 2    50   ~ 0
X_Dir
Text Label 6850 5300 2    50   ~ 0
Y_Step
Text Label 6850 5200 2    50   ~ 0
Y_Dir
Text Label 6850 5500 2    50   ~ 0
Z_Step
Text Label 6850 5400 2    50   ~ 0
Z_Dir
Wire Wire Line
	4700 4450 5300 4450
Wire Wire Line
	5400 5000 5300 5000
Wire Wire Line
	5300 5000 5300 4800
Connection ~ 5300 4800
Wire Wire Line
	8025 6100 7575 6100
Wire Wire Line
	8025 6000 7575 6000
Wire Wire Line
	7575 5900 8025 5900
Text Label 7575 6100 0    50   ~ 0
GND
Text Label 7575 5700 0    50   ~ 0
3v3
Wire Wire Line
	6300 4800 6850 4800
Wire Wire Line
	6300 4900 6850 4900
Wire Wire Line
	6300 5000 6850 5000
Wire Wire Line
	8000 5150 7550 5150
Wire Wire Line
	8000 5250 7550 5250
Wire Wire Line
	8000 5350 7550 5350
Text Label 7575 5900 0    50   ~ 0
REF1
Text Label 6850 4800 2    50   ~ 0
REF1
Text Label 6850 4900 2    50   ~ 0
REF2
Text Label 6850 5000 2    50   ~ 0
REF3
Text Label 7550 5150 0    50   ~ 0
REF2
Wire Wire Line
	5150 4900 5150 6050
Text Label 5150 6050 1    50   ~ 0
GND
Wire Wire Line
	5300 4450 5300 4250
Connection ~ 5300 4450
Text Label 5300 4250 3    50   ~ 0
3v3
Text Notes 4900 3750 0    50   ~ 0
Clock for TMC429 (16MHz) to be generated by ESP32 (was Y_Dir)
Text Notes 4900 3550 0    50   ~ 0
SPI Chip select for Z Stepper (was Y_Step)
$Comp
L Connector:Conn_01x02_Male J3
U 1 1 602D8535
P 2700 1225
F 0 "J3" V 3250 1350 50  0000 R CNN
F 1 "X Stepper C" H 3100 1325 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 2700 1225 50  0001 C CNN
F 3 "~" H 2700 1225 50  0001 C CNN
	1    2700 1225
	0    1    1    0   
$EndComp
$Comp
L Connector:Conn_01x02_Male J6
U 1 1 602E44E6
P 5800 1200
F 0 "J6" H 5772 1082 50  0000 R CNN
F 1 "Y Stepper C" H 6150 1300 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 5800 1200 50  0001 C CNN
F 3 "~" H 5800 1200 50  0001 C CNN
	1    5800 1200
	0    1    1    0   
$EndComp
$Comp
L Connector:Conn_01x02_Male J8
U 1 1 602E4C4C
P 8800 1200
F 0 "J8" H 8772 1082 50  0000 R CNN
F 1 "Z_Limit" H 9150 1300 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Horizontal" H 8800 1200 50  0001 C CNN
F 3 "~" H 8800 1200 50  0001 C CNN
	1    8800 1200
	0    1    1    0   
$EndComp
Wire Wire Line
	2600 1425 2600 1925
Wire Wire Line
	2700 1425 2700 1925
Wire Wire Line
	5800 1400 5800 1925
Wire Wire Line
	5700 1400 5700 1925
Wire Wire Line
	8700 1400 8700 1925
Wire Wire Line
	8800 1400 8800 1925
Text Notes 9250 1525 0    50   ~ 0
Z Stepper Limit pin not \nconnected to anything\nbut available should we \nwish to do endstop detection
Text Label 7550 5350 0    50   ~ 0
GND
Text Label 7550 4950 0    50   ~ 0
3v3
Wire Wire Line
	5900 4600 5900 4300
Text Label 5900 4300 3    50   ~ 0
REFR2
Text Label 5800 4300 3    50   ~ 0
REFR3
Wire Wire Line
	5800 4300 5800 4600
Text Label 6850 5100 2    50   ~ 0
REFR1
$Comp
L Connector:Conn_01x06_Male J9
U 1 1 60377FA7
P 8200 4375
F 0 "J9" H 8172 4257 50  0000 R CNN
F 1 "Z Limit" H 8172 4348 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_2x03_P2.54mm_Horizontal" H 8200 4375 50  0001 C CNN
F 3 "~" H 8200 4375 50  0001 C CNN
	1    8200 4375
	-1   0    0    1   
$EndComp
$Comp
L Connector:Conn_01x06_Male J10
U 1 1 60379433
P 8200 5150
F 0 "J10" H 8172 5032 50  0000 R CNN
F 1 "Y Limit" H 8172 5123 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_2x03_P2.54mm_Horizontal" H 8200 5150 50  0001 C CNN
F 3 "~" H 8200 5150 50  0001 C CNN
	1    8200 5150
	-1   0    0    1   
$EndComp
$Comp
L Connector:Conn_01x06_Male J11
U 1 1 60379FDD
P 8225 5900
F 0 "J11" H 8197 5782 50  0000 R CNN
F 1 "X Limit" H 8197 5873 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_2x03_P2.54mm_Horizontal" H 8225 5900 50  0001 C CNN
F 3 "~" H 8225 5900 50  0001 C CNN
	1    8225 5900
	-1   0    0    1   
$EndComp
Text Label 7550 4175 0    50   ~ 0
3v3
Text Label 7550 4575 0    50   ~ 0
GND
Text Label 7550 4375 0    50   ~ 0
REF3
Wire Wire Line
	7550 4575 8000 4575
Wire Wire Line
	8000 4475 7550 4475
Wire Wire Line
	8000 4375 7550 4375
Text Label 7550 4075 0    50   ~ 0
3v3
Text Label 7550 4475 0    50   ~ 0
GND
Text Label 7550 4275 0    50   ~ 0
REFR3
Wire Wire Line
	7550 4275 8000 4275
Wire Wire Line
	8000 4175 7550 4175
Wire Wire Line
	8000 4075 7550 4075
Wire Wire Line
	8000 4850 7550 4850
Wire Wire Line
	8000 4950 7550 4950
Wire Wire Line
	8000 5050 7550 5050
Text Label 7550 5050 0    50   ~ 0
REFR2
Text Label 7550 5250 0    50   ~ 0
GND
Text Label 7550 4850 0    50   ~ 0
3v3
Wire Wire Line
	8025 5800 7575 5800
Wire Wire Line
	8025 5700 7575 5700
Wire Wire Line
	7575 5600 8025 5600
Text Label 7575 6000 0    50   ~ 0
GND
Text Label 7575 5600 0    50   ~ 0
3v3
Text Label 7575 5800 0    50   ~ 0
REFR1
Wire Wire Line
	6300 5100 6850 5100
$Comp
L Device:CP C2
U 1 1 603BEA9A
P 10550 2400
F 0 "C2" H 10668 2446 50  0000 L CNN
F 1 "47uF 25v" H 10668 2355 50  0000 L CNN
F 2 "Capacitor_SMD:CP_Elec_6.3x5.4" H 10588 2250 50  0001 C CNN
F 3 "~" H 10550 2400 50  0001 C CNN
	1    10550 2400
	1    0    0    -1  
$EndComp
Wire Wire Line
	9350 2100 9350 1750
Wire Wire Line
	9350 1750 10550 1750
Connection ~ 9350 2100
Wire Wire Line
	9350 2100 9800 2100
Wire Wire Line
	9350 2800 9350 2975
Wire Wire Line
	10550 1750 10550 2250
Wire Wire Line
	10550 2550 10550 2975
Wire Wire Line
	9350 2975 10550 2975
$EndSCHEMATC
