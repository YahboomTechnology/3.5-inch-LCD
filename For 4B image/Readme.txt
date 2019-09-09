NOTE:
You can focus on the following GitHub web site, for the latest lcd drivers:
https://github.com/goodtft/LCD-show
===============================================================================================================
"LCD-show-170315.tar.gz" just for Raspbian (Release date:2017-03-02) or later,
DO NOT use it for the Raspbian version before 2017-03-02.

================================================================================================================
"LCD-show-160701.tar.gz" support Raspbian version before Raspbian-2017-02-16,such as(2017-02-16,2017-01-11,
2016-11-25,2016-09-23,2016-05-27,2016-05-10,2016-03-18,or earlier).
And This Driver also tesed on "kali-2.1.2"  ,"ubuntu-mate-16.04-beta2"

================================================================================================================
How to Install:
1.)Step1, Install Raspbian official mirror 

a)Download Raspbian official mirror:
https://www.raspberrypi.org/downloads/
b)Use¡°SDFormatter.exe¡±to Format your TF Card
c)Use¡°Win32DiskImager.exe¡± Burning mirror to TF Card

2.) Step2, Clone my repo onto your pi

git clone https://github.com/goodtft/LCD-show.git
chmod -R 755 LCD-show
cd LCD-show/

3.)Step3, According to your LCD's type, excute:

In case of 2.8" LCD
sudo ./LCD28-show

In case of 3.2" LCD
sudo ./LCD32-show

In case of 3.5" LCD
sudo ./LCD35-show

In case of 3.97" LCD
sudo ./LCD397-show

In case of 4.3" LCD
sudo ./LCD43-show

In case of 5" LCD
sudo ./LCD5-show

In case of 7inch(B)-800X480 RPI LCD
sudo ./LCD7B-show

In case of 7inch(C)-1024X600 RPI LCD
sudo ./LCD7C-show

If you need to switch back to the traditional HDMI display
sudo ./LCD-hdmi


Wait a few minutes,the system will restart automaticall , enjoy with your LCD.


