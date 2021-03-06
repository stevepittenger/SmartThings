<h1>Garageio Integration For SmartThings</h1>
Here within lies a service manager and device handler for controlling Garageio controlled doors from within SmartThings.  All existing functionality for SmartThings typed garage doors is included and thus Garageio controlled doors can be utilized with any and all SmartThings Garage Door SmartApps.

<h3>Manual Installation</h3>
<h4>Step 1.</h4>
Device Type Code: https://github.com/bmmiller/SmartThings/blob/master/devicetypes/bmmiller/garageio-device.src/garageio-device.groovy

Add device type through https://ide.smartthings.com

<h4>Step 2.</h4>
Service Manager Code: https://github.com/bmmiller/SmartThings/blob/master/smartapps/bmmiller/garageioservicemgr.src/garageioservicemgr.groovy

Add smart app through https://ide.smarthings.com

<h4>Step 3.</h4>
Go to SmartThings app on phone, click the pick '+' and add your new SmartApp called "GarageioServiceMgr" under "My Apps" and go through the setup.  You will be required to enter your user (email) and password here.

<h4>Step 4.</h4>
You should be given the choice of doors on your account that you want to control.  Select the ones you want to control and complete setup.

<h3>Changelog</h3>
<ul>
  <li>v1.3   - Added watchdogTask() to restart polling if it stops, inspiration from Pollster
  <li>v1.2   - Added multiAttributeTile() to make things look prettier. No functionality change.
  <li>v1.1.1 - Tiny fix for service manager failing to complete
  <li>v1.1   - GarageioServiceMgr() and Device Handler impplemented to handle ChildDevice creation, deletion, polling, and ST suggested implementation.</li>
  <li>v1.0   - GarageioInit() implementation to handle polling in a Smart App, left this way for quite a while</li>
  <li>v0.1   - Initial working integration</li>
</ul>
		
