# CRM Test start guide

## 1. Change DANTE setting
Open load preset > Select 'expForCRM.xml'

## 2. Setting ip address
- iPad side

1. Open 'Touch OSC' application
2. You can see a setting menu (if not, tap the upper right button)
3. Click Connections > OSC
4. Change (or make sure) Host ip address to Windows PC's ip address
   1. Launch 'command prompt'
   2. Type 'ipconfig'
   3. Check the 'wireless.rit.edu's IPv4 Address and type it to the iPad's input box
   
- Windows PC side
5. Change the ip address on the Matlab code (it is located on Line 14). You can check the iPad's ip on the last line of the OSC setting menu.

## 3. Start experiment
1. Return the setting menu (tap upper left '<TouchOSC')
2. Click 'Done' bottom at the upper right
3. Then, you can run the Matlab code.
4. Type participant's name on the coming input box.
