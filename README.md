# test-nucleo-rtos-sample
https://developer.mbed.org/users/kenjiArai/code/Nucleo_rtos_sample/
Necleo L152RE rtos sample (also for F401RE & F411RE mbed)
I test this above now.
I got shown bellow on the run.
<pre>
Created on Jan 21 2016 03:01:08 (UTC)

line:235
Use External CLK (Good for RTC)
line:241

Set time into RTC
 e.g. >15 2 7 10 11 12 -> Feb. 7th, '15, 10:11:12
 If time is fine, just hit enter
>?

line:243
line:247
line:251
line:253
line:258
line:275
lline:ine:171
279
line:283
line:287
line:291
line:293
line:142


Monitor for mbed system, created on Jan 21 2016 [Help:'?' key]

>?

Monitor for mbed system, created on Jan 21 2016
a - Show analog data
d - Show control data
m - Show mail data
s - Show USER Button
t - Check and set RTC
x - Goto HW monitor
q - Return to main

>x


Debug Interface for mbed system, created on UTC: Jan 21 2016(03:01:08) [Help:'?' key]

>?

Debug Interface for mbed system, created on UTC: Jan 21 2016(03:01:08)
m  - Entry Memory Mode
m>? -> Aditinal functions can see by ?
p  - Entry Port Mode
p>? -> Aditinal functions can see by ?
r  - Entry Register Mode
r>? -> Aditinal functions can see by ?
s  - System Clock -> sf, System / CPU information -> sc
q  - Quit (back to called routine)

>s

sc - System CPU information
sf - System Clock

>sc

CPU = ARM Cortex-M4
Variant:0
Revision:1
CPU ID: 0x410fc241
DBG ID: 0x10006433
Unique device ID(94bits):(1) 0x00260029 (2) 0x30345119 (3) 0x39353933

>sf

CR       = 0x03077083
PLLCFGR  = 0x07415408
CFGR     = 0x0000100a
CIR      = 0x00000000
AHB1RSTR = 0x00000000
APB2RSTR = 0x00000000
APB1RSTR = 0x00000000
AHB1ENR  = 0x00000007
APB2ENR  = 0x00000100
APB2LPENR= 0x00077931
APB1LPENR= 0x10e2c80f
CSR      = 0x0e000000
Power Control
CR       = 0x00008100
CSR      = 0x00004000

fVCO = fPLL-in x (PLLN/PLLM), fPLL-out = fVCO/PLLP, fUSB-out = fVCO/PLLQ
Use PLL with PLLN=336, PLLM=8
Use HSE(not Xtal but External Clock)=8000000Hz
PLL/Base   freq=336000000Hz
Use PLL with PLLP=4, PLLQ=7
PLL/System freq=84000000Hz
PLL/USB    freq=48000000Hz

SYSCLK clock freq. =84000000Hz
HCLK   clock freq. =84000000Hz
PCLK1  clock freq. =42000000Hz
PCLK2  clock freq. =84000000Hz

RTC Clock
Use LSE(external Xtal)=32768Hz


>
</pre>
