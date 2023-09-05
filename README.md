# 800L-SMS

THIS IS A WORK IN PROGRESS

Things that could help. 

* Update Line 7 in the src/main.cpp, SMS_TARGET with the number you want to send to, // SMS_TARGET Example for UK +44XXXXXXXXX
* If Sending from an iPhone make sure you send as SMS, I had to disable iMessage settings. 
* At some point in the future the 2G/3G networks will be disabled or turned off, so the 800L will likely stop working.
* Used Platform IO Extension for VS Code, so you may need to add it to your instance of VS Code. 

* There are companies out there that provide IoT SIMs which seem much cheaper than the normal companies, although they seem to use the same infrastructure.  The one I have signed up for is https://www.soracom.io/, awaiting the SIM to be delivered as of 05/09/2023.

* Tested in the UK on the EE Network and found out the hard way the Pay-As-You-Go Sims stopped working after 6 months of no activity.

![image](https://github.com/RamblingGeekUK/800L-SMS/assets/7108949/1c8bd80e-4c1c-4fce-8b74-b0ec55451f04)
https://ee.co.uk/help/mobile/manage-use/pay-as-you-go/pay-as-you-go-credit-run-out-when-i-havent-made-calls#:~:text=If%20you%20haven%27t%20used,any%20credit%20will%20be%20removed


OG Code found here : https://forum.arduino.cc/t/can-somebody-help-me-to-how-read-the-received-sms-on-esp32-ttgo-t-call-using-arduino-ide/1157804/12
