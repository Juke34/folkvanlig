# folkvanlig
Specification related to the ikea bike folkvanlig 2

  * [General information](#general-information)
    * [Bike](#bike)
    * [Battery and Engine](battery-and-engine)
  * [The LCD Display](#the-lcd-display)
    * [Starting](#starting)
    * [Assist level selecting](#assist-level-selecting)
    * [Speed mode switch and Mileage mode switch](#speed-mode-switch-and-mileage-mode-switch)
    * [Walk Assistance](#walk-assistance)
    * [Data Reset](#data-reset)
    * [Parameter Setting](#parameter-setting)
      * [Basic menu](#basic-menu)
      * [Advanced menu](#advanced-menu)
  * [Miscellaneous](#miscellaneous)
  
## General information

Ikea price for the bike is 6 595 sek in Sweden

### Bike

| data | value
| --- | --- 
| Weight   | 25 kg
| Frame Size  | 53 cm
| max loading  | 130 kg
| Wheel size    | 29
| Tires | Cheng Shin 29X2.10 (52-622)
| Switches | Shimano Tourney, SiS reglage, "Cassette" / "Free wheel" rear (Shimano MF-TX21 14-28)
| Brakes | Disc - Tektro Aries, discs Tektro 6F
| Saddle | Selle Royal Free Way (with taillight)
| Front fork | no lockout
| Pedals | foldable in plastic

### Battery and Engine

Ikea price for the battery is 1 695 sek in Sweden

| data | value
| --- | --- 
| Battery | E-bike Smart Battery 36V 8.7Ah from Panasonic (price 1695 sek in sweden)
| Range | 50-70 km
| Engine| Rear drive
| Battery Capacity | 313 Wh
| Speed assistance | 6 assists levels
| Computer | APT Intelligence 800S

## The LCD Display

It is APT 800S.
Here information retrieved from [this page](http://webcache.googleusercontent.com/search?q=cache:TCjj4_giLpcJ:www.aptdevelop.com/Public/Upload/57689dbfa8e43.pdf+&cd=1&hl=fr&ct=clnk&gl=se&client=safari)

### Starting

Press and hold Power button for 1 second, then display will work and controller power supply turn on.During the working mode, if press and hold Power button for 1 second, then display will stop andcontroller output will be cut off. If no futher action to display within 5 minutes(could be set), display willcut off automatically and power output cut off.

### Assist level selecting

Short press UP/DOWN button to change the assist level. Top assist level is 9, 1 is the lowest, whendisplay turn on, automatically it will be level 1. 0 level is without any assistance.

### Speed mode switch and Mileage mode switch

Short press POWER button can switch change the speed mode & mileage mode, data sequence is as:Average Speed->Max Speed->Actual Speed->Single Trip->ODO->DST-> Time.

### Walk Assistance

Press and hold DOWN button for 2 seconds can get into walk assistance mode, actual speed can beshown, mode as P, release DOWN , then exit from walk assistance mode.

### Data Reset

Press and hold UP & DOWN buttons together for 1 second can reset several temporary data includingMAX Speed / AVG Speed/ Trip / Time.

### Parameter Setting

When system turn on, double press POWER button (press interval <0.3 second) can get into parametersetting state, under this, parameter could be set. And double press POWER button (press interval <0.3second) to exit. In parameter setting state, when flashing, press UP/DOWN buttons to adjust parameters,short press POWER button to switch parameter items.

#### Basic settings


| Abbreviation displayed | meaning | choice | default value
| --- | --- | --- | ---
| S7 | Kilometer/Mile |  km/h / MPH (Km / Mile) | km
| bL1 | Backlight Brightness | 1~5 to change the brightness of the backlight.1-darkest, 5-brightest. | ?
| OFF | Auto off time | 1 to 9, the number represent delay time (minutes) before display shutdownautomatically. | 5
| Wd | Wheel diameter | 16/18/20/22/24/26/700C/28, value represents the diameter of the wheel (inch). Wrong value forwheel diameter will cause speed & mileage abnormal. |
| bU0 | Voltage set | 24V/36V/48V/UbE, UbE means user-defined voltage setting, this parameter can be set throughcomputer. |
| PSd | Password/Speed Limit Setting | require to inputpasswords, press UP/DOWN buttons to change the password value (0~9), short press POWER buttonto switch the password item, password is 4 digits, the default password is "1919". Press POWER buttonwhen password adjustment is completed. Display will return to the Voltage set item if the password isincorrect. Correct password will enter the Speed Limit Setting item. | 0000

#### Advanced settings

| Abbreviation displayed | meaning | choice | default value
| --- | --- | --- | ---
| SPL | Speed limit | the value can be set from 10 to 41km/h. The maximum speed is restricted by the motor and controller, probably couldn’t reach thesetting value. | 25km/h
| HAL | Magnetic Pole numbers of speed sensor | 1-? |
| ASd | Direction of speed sensor | 0/1, 0 indicates forward, 1 indicates backward. | 0
| SAS | Power Assistance Start Over Set Magnet Qty | |
| SAr | Assistance level |
| HAd | | Throttle set | 0~1 to change the throttle OFF or ON. |
| HAr | Throttle 6KM | 0~1 to change the throttle 6km OFF or ON | 
| Sdr | Soft startup parameters | 1-3 |
| CUL | MAX Current Limit set | X-Y |  15A
| PAS | Range of assistance level setting | 0-3, 0-5, 0-8 and UBE| default is UBE
| ETE | Battery Pack Temperature | shows battery pack temperature. Unit: °C | None
| bSU | Battery Pack Voltage | shows battery pack voltages. Unit: mV |
| CUr | Real-time current | shows real-time current value. Unit: mA |
| rCP | Percentage of relative capacity | displays percentage of relative capacity value. Unit: % | 
| ACP | Absolute Battery Capacity SOC |  Such data will be calculated by BMS, Unit: %. |
| SCA | Battery Remaining Capacity | shows battery remaining capacity value. Unit: mAh |
| FCA | Full Charged Capacity | displays full capacity value. Unit: mAh |
| CYC | Battery cycle times | Shows the cycle value. Unit: times | 
| PCH | The current charging interval | shows current charging interval value. Unit: hr. | 
| bCH | Maximum charge time interval | hows the maximum charge time interval value. Unit: hr. |


#### Miscellaneous

[https://happyride.se/forum/read.php/1/3085047/3356627](https://happyride.se/forum/read.php/1/3085047/3356627)  
[https://happyride.se/forum/read.php/1/3401025](https://happyride.se/forum/read.php/1/3401025)
