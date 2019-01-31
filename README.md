# MDT
Stuff for MDT

MDT "ZTI" - settings for "Zero Touch Imaging". These settings make it zero touch imaging, you can pick the task to install and name the computer what you want or leave the default generated name. If you want to revert to a semi ZTI, just make a couple changes to the customsettings to assign the task, change YES to NO for the following: "SkipTaskSequence" and "SkipComputerName".  I commented on what they all do, if you google around, there is a lot more you can do with it as far as ZTI and other settings.  Place these in the following location, then update your deployment share. "..\DeploymentShare\Control"
