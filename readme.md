![Screenshot_20260310_165830](https://github.com/user-attachments/assets/96259782-8bdd-4e99-8455-15d8ed7f4675)


original source code for arduino coming from this page

https://gitee.com/coding_everything/xaobao_cheap_bus_servo_hack_record/tree/master

i just ask deepseek ai to convert it to be a web tool.

download main.html, open it on chrome.

use ttl module to connect your ubtech servo, only connect 1 servo at the time.

you can change servo ID, and test servo angle and speed.

![636333009_10162828994076395_4064788741446823381_n](https://github.com/user-attachments/assets/47017e3e-4a94-47cb-8e35-e71a1262fcd2)


ubtech servo port from left to right is gnd-vcc-data

you need to use 2s battery to power up the servo, wire like what i did.

gnd, servo+battery+gnd pin from module

vcc, servo+battery

data, servo+tx pin from module, rx(orange) is unnecessary

https://www.youtube.com/watch?v=i3N7W7t5f8s
