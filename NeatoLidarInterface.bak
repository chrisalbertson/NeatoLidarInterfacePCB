EESchema Schematic File Version 4
LIBS:NeatoLidarInterface-cache
EELAYER 29 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "Neato LIDAR Interface Board"
Date "2019-05-26"
Rev "1.0"
Comp ""
Comment1 "Chris Albertson"
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Transistor_BJT:PN2222A Q1
U 1 1 5CE9D2CE
P 5150 5050
F 0 "Q1" H 5341 5096 50  0000 L CNN
F 1 "PN2222A" H 5341 5005 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-18-3" H 5350 4975 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/PN/PN2222A.pdf" H 5150 5050 50  0001 L CNN
	1    5150 5050
	-1   0    0    -1  
$EndComp
$Comp
L Connector_Generic:Conn_01x02 J3
U 1 1 5CE9F90D
P 4700 4400
F 0 "J3" H 4618 4075 50  0000 C CNN
F 1 "Conn_01x02" H 4618 4166 50  0000 C CNN
F 2 "Connector_JST:JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical" H 4700 4400 50  0001 C CNN
F 3 "~" H 4700 4400 50  0001 C CNN
	1    4700 4400
	-1   0    0    1   
$EndComp
$Comp
L Connector_Generic:Conn_01x04 J2
U 1 1 5CEA01E9
P 4700 3100
F 0 "J2" H 4650 3350 50  0000 L CNN
F 1 "Conn_01x04" H 4650 3450 50  0000 L CNN
F 2 "Connector_JST:JST_PH_B4B-PH-K_1x04_P2.00mm_Vertical" H 4700 3100 50  0001 C CNN
F 3 "~" H 4700 3100 50  0001 C CNN
	1    4700 3100
	-1   0    0    -1  
$EndComp
$Comp
L Connector_Generic:Conn_01x02 J1
U 1 1 5CEA0E19
P 4700 1950
F 0 "J1" H 4618 1625 50  0000 C CNN
F 1 "Conn_01x02" H 4618 1716 50  0000 C CNN
F 2 "Connector_JST:JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical" H 4700 1950 50  0001 C CNN
F 3 "~" H 4700 1950 50  0001 C CNN
	1    4700 1950
	-1   0    0    1   
$EndComp
$Comp
L Connector:Conn_01x02_Male J5
U 1 1 5CEA20AE
P 6100 4100
F 0 "J5" V 6050 4000 50  0000 L CNN
F 1 "Conn_01x02_Male" V 5950 3750 50  0000 L CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 6100 4100 50  0001 C CNN
F 3 "~" H 6100 4100 50  0001 C CNN
	1    6100 4100
	0    1    1    0   
$EndComp
$Comp
L SBCandBreakouts:STM32BluePill U1
U 1 1 5CEAC22A
P 7550 2450
F 0 "U1" H 7550 2500 50  0000 C CNN
F 1 "STM32BluePill" H 7550 2700 50  0000 C CNN
F 2 "MyFootprints:STM32BluePill" H 7550 2450 50  0001 C CNN
F 3 "" H 7550 2450 50  0001 C CNN
	1    7550 2450
	1    0    0    -1  
$EndComp
Text Notes 2700 3300 0    50   ~ 0
1 - RED +5V\n2 - BRN Tx (not used)\n3 - ORG Rx (data from LIDAR, 115200 baud)\n4 - BLK Ground
Text Notes 2700 4350 0    50   ~ 0
1 - BLK Ground, to motor
Text Notes 2700 4450 0    50   ~ 0
2 - RED, Nominal 3 volts to motor
Text Notes 2550 2050 0    50   ~ 0
Optional External Power Input\n    1 - Ground\n    2 - +5 V
$Comp
L power:GND #PWR04
U 1 1 5CEC1135
P 6850 5600
F 0 "#PWR04" H 6850 5350 50  0001 C CNN
F 1 "GND" H 6855 5427 50  0000 C CNN
F 2 "" H 6850 5600 50  0001 C CNN
F 3 "" H 6850 5600 50  0001 C CNN
	1    6850 5600
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR03
U 1 1 5CEC21AC
P 5050 5600
F 0 "#PWR03" H 5050 5350 50  0001 C CNN
F 1 "GND" H 5055 5427 50  0000 C CNN
F 2 "" H 5050 5600 50  0001 C CNN
F 3 "" H 5050 5600 50  0001 C CNN
	1    5050 5600
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR01
U 1 1 5CEC31F1
P 4900 2350
F 0 "#PWR01" H 4900 2100 50  0001 C CNN
F 1 "GND" H 4905 2177 50  0000 C CNN
F 2 "" H 4900 2350 50  0001 C CNN
F 3 "" H 4900 2350 50  0001 C CNN
	1    4900 2350
	1    0    0    -1  
$EndComp
Wire Wire Line
	5050 5250 5050 5600
Wire Wire Line
	4900 1950 4900 2350
$Comp
L Connector:Conn_01x02_Male J4
U 1 1 5CEC4797
P 5550 3550
F 0 "J4" H 5750 3800 50  0000 C CNN
F 1 "Conn_01x02_Male" H 5450 3700 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 5550 3550 50  0001 C CNN
F 3 "~" H 5550 3550 50  0001 C CNN
	1    5550 3550
	-1   0    0    -1  
$EndComp
$Comp
L power:GND #PWR02
U 1 1 5CEF9ED5
P 4900 3550
F 0 "#PWR02" H 4900 3300 50  0001 C CNN
F 1 "GND" H 4905 3377 50  0000 C CNN
F 2 "" H 4900 3550 50  0001 C CNN
F 3 "" H 4900 3550 50  0001 C CNN
	1    4900 3550
	1    0    0    -1  
$EndComp
Wire Wire Line
	6950 3200 4900 3200
Wire Wire Line
	4900 3300 4900 3550
Wire Wire Line
	5350 3550 5350 3100
Wire Wire Line
	5350 3100 4900 3100
Wire Wire Line
	6950 4500 5350 4500
Wire Wire Line
	5350 4500 5350 3650
Wire Wire Line
	6850 4400 6950 4400
Wire Wire Line
	6000 4300 5100 4300
Wire Wire Line
	6100 4300 6950 4300
Wire Wire Line
	4900 1850 5100 1850
Wire Wire Line
	5100 1850 5100 3000
Connection ~ 5100 4300
Wire Wire Line
	5100 4300 4900 4300
Wire Wire Line
	4900 3000 5100 3000
Connection ~ 5100 3000
Wire Wire Line
	5100 3000 5100 4300
Wire Wire Line
	4900 4400 5050 4400
Wire Wire Line
	5050 4400 5050 4850
Wire Wire Line
	6850 4400 6850 5600
$Comp
L power:GND #PWR05
U 1 1 5CF2666C
P 8700 3000
F 0 "#PWR05" H 8700 2750 50  0001 C CNN
F 1 "GND" H 8705 2827 50  0000 C CNN
F 2 "" H 8700 3000 50  0001 C CNN
F 3 "" H 8700 3000 50  0001 C CNN
	1    8700 3000
	1    0    0    -1  
$EndComp
Wire Wire Line
	8150 2600 8700 2600
Wire Wire Line
	8700 2600 8700 2700
Wire Wire Line
	8150 2700 8700 2700
Connection ~ 8700 2700
Wire Wire Line
	8700 2700 8700 3000
Text GLabel 8200 3100 2    50   Input ~ 0
PB_10
Wire Wire Line
	8200 3100 8150 3100
Wire Wire Line
	5500 5050 5350 5050
$Comp
L Device:R R1
U 1 1 5CE9F166
P 5650 5050
F 0 "R1" V 5857 5050 50  0000 C CNN
F 1 "1K" V 5766 5050 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 5580 5050 50  0001 C CNN
F 3 "~" H 5650 5050 50  0001 C CNN
	1    5650 5050
	0    -1   -1   0   
$EndComp
Wire Wire Line
	5800 5050 5950 5050
Text GLabel 5950 5050 2    50   Input ~ 0
PB_10
$EndSCHEMATC
