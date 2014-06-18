ofxPQLabs
=============================

### Original version
Original 32bit verison by jvcleave:  
https://github.com/jvcleave/ofxPQLabs

### This version
This version has a 64bit branch by Sosolimited.
It must be run on a 64bit openframeworks install:  
https://github.com/prisonerjohn/openFrameworks/tree/feature-64bit

How it was created from the original:
* replaced the old PQLabs files with the new Mac C++ SDK (mt_mac_sdk_c_v1.3.7): http://multitouch.com/sdk.html
* some constants were renamed to follow renamed vars in new PQMTClient file
* “using namespace PQ_SDK_MultiTouch;” was required now in /src/ header files
* “tcq.app_id = GetTrialAppID();” was commented as GetTrialAppID() doesn’t exit anymore in PQMTClient.h


###Changelog

* Created on June 18, 2014, by JC.