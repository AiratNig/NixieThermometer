# NixieThermometer
Термометр/гигрометр на индикаторных лампах ИН-14 и ИН-19А.

<img src="https://github.com/AiratNig/NixieThermometer/blob/master/img/IMG_2782.JPG" width="30%"> <img src="https://github.com/AiratNig/NixieThermometer/blob/master/img/IMG_2781.JPG" width="30%">


Список элементов

|ID|Name|Designator|Footprint|Quantity|
|--|----|----------|---------|--------|
|1|ATTINY44A-SSU|U1|SOP-14|1|
|2|FQD10N20CTM|Q1|DPAK|1|
|3|1N4148WS|D1, D3, D4, D5, D6, D7, D8, D9, D10, D11, D12|SOD-323|11|
|4|LED|LED1, LED2, LED3|SMD_3528|3|
|5|BC847|Q14|SOT-23-3|1|
|6|E1J|D2|SOD123|1|
|7|IN-19A|N3||1|
|8|SHT30-DIS-B `*`|U8|DFN-8|1|
|9|HTU21D, SI7012 or HDC1080DMBR `*`|U6|WSON-6|1|
|10|U-F-M5DD-Y-L|X1||1|
|11|XC6206P332MR|U5|SOT-23-3|1|
|12|BZV55-C75|D13|SOD-80|1|
|13|100u|C2, C4, C7|CASE-B_3528|3|
|14|220uH|L1|CD75|1|
|15|BC857|Q2|SOT-23-3|1|
|16|1u 250V|C1|SMD_1812|1|
|17|100n|C3, C5, C6, C8, C9, C10|SMD_0603|6|
|18|TLP127|U2, U3, U4|SOP-6|3|
|19|TS-1088R-02026|SW1||1|
|20|10|R1|SMD_0603|1|
|21|1k|R2, R3, R4, R5, R6, R12, R16, R18, R19, R20|SMD_0603|10|
|22|300k|R7|SMD_0805|1|
|23|10k|R8|SMD_0805|1|
|24|10k|R9, R10, R11, R14, R15|SMD_0603|5|
|25|68k|R13|SMD_0805|1|
|26|5.1k|R17|SMD_0603|1|
|27|BH1750FVI-TR|U7|WSOF-6|1|
|28|MMBTA42|Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10, Q11, Q12|SOT-23-3|10|
|29|IN-14|N1, N2||2|
|30|2N7002DW|Q13|SOT-363|1|

\* - Для каждого типа датчика своя прошивка

Для питания индикаторных ламп используется напряжение ~180В, поэтому нельзя касаться при работе устройства элементов С1, D2, R8, R7, U2, U3, U4.<br/>

Для включения/выключения подсветки зажать перед подачей питания кнопку SW1.

Фьюзы ATtiny44: low: `0xE2`, high: `0xDF`, extended: `0xFF`


