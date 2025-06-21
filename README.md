# linux_deploy
boot script for initialising linux environment on android 4.0.4
So, can't we use old android mobile like raspbery pi ?
yes, we can, so here is script I prepared for sony xperia tipo dual
its touch is broken so I had to manage lots of stuff to make it 
touch less. luckly adb was on. so I rooted it, installed custom
recovery and custom ROM. installed Linux Deploy app and installed 
alpine linux via rootfs. set it up for ssh and other stuff. Now
all we need is automate all things on boot. so, after boot we
dont need to access it using adb to start linux and sshd. all
should start automatically and ready to access linux environment.
further, we are starting adb on tcpip so we can access android
shell from within linux environment. Now our tiny linux machine
is ready.


## Disclaimer

This project is provided "as is," without warranty of any kind. 
The creator(s) make no guarantees regarding its functionality, accuracy, or suitability for any purpose.
By using this project, you acknowledge that the creator(s) are **not liable** for any issues, 
damages, or consequences arising from its use.
Use at your own discretion.
