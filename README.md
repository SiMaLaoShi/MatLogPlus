![Icon](./app/src/main/res/mipmap-hdpi/ic_launcher.png)MatLog
=========



### 20221024

- 增加通過pid來过滤日志

![image-20221024161507882](image-20221024161507882.png)



It's CatLog, but with material goodness.

Graphical log reader for Android.

[<img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png"
      alt="Get it on Google Play"
      height="90">](https://play.google.com/store/apps/details?id=com.pluscubed.matlog)
[<img src="https://f-droid.org/badge/get-it-on.png"
      alt="Get it on F-Droid"
      height="90">](https://f-droid.org/app/com.pluscubed.matloglibre)

Based on Nolan Lawson's CatLog: [Google Play][1], [GitHub][2]

Overview
---------
MatLog is a free and open-source material-style log reader for Android based on CatLog.

It shows a scrolling (tailed) view of the Android "logcat" system log, 
hence the goofy name.  It also allows you to record logs in real time, send logs via email, 
and filter using a variety of criteria.

FAQs
-------------
Taken from CatLog's FAQ:

#### Where are the logs saved?

On the SD card, under ```/sdcard/catlog/saved_logs/```.

#### I can't see any logs!

This problem typically shows up on custom ROMs.  First off, try an alternative logging app, to verify that
the problem is with your ROM and not MatLog.

Next, see if your ROM offers system-wide settings to disable logging.  Be sure to reboot after you change anything.

If that still doesn't work, you can contact the creator of your ROM to file a bug/RFE.

Development
-------------
- Select `fdroid` build variants to build and run immediately
- For `play` variants:
    - Put `google-services.json` from Firebase in app/src/main/play/
    - Put `fabric.properties` in app/
    - Put signing keys and Fabric API key in local.properties

License
---------
```
Copyright (C) 2018  Daniel Ciao

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

```

[1]: https://play.google.com/store/apps/details?id=com.nolanlawson.logcat
[2]: https://github.com/nolanlawson/Catlog
[3]: https://plus.google.com/u/0/communities/108705871773878445106
