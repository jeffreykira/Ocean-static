### Requirements
---
OceanKTV v2.0.6 requires:
- INTEL or AMD based NAS
- QTS 4.2.x/4.3.x
- HD Station 3.0.0 or higher. 

### Installation
---
###### Location
//172.17.25.252/daily_build/Solution_Team/OceanKTV/v2/
###### For INTEL based NAS
- poseidon-release-221.1487-2.0.6.42-intel.qpkg (QTS 4.2.x)
- poseidon-release-221.1487-2.0.6.43-intel.qpkg (QTS 4.3.x)
###### For AMD based NAS
- poseidon-release-221.1487-2.0.6.42-omx.qpkg (QTS 4.2.x)
- poseidon-release-221.1487-2.0.6.43-omx.qpkg (QTS 4.3.x)

### Known issues and limitations
---

- [#102696, #102713, #102722](http://172.17.25.222/bugzilla/show_bug.cgi?id=102696) Limited mouse support in TV app because TV app was optimized for QNAP remote controller.
- [#104495](http://172.17.25.222/bugzilla/show_bug.cgi?id=104495) No app description in HD Station app list.
- [#103060](http://172.17.25.222/bugzilla/show_bug.cgi?id=103060) The i18n need to be improved in some countries.
- [#94041](http://172.17.25.222/bugzilla/show_bug.cgi?id=94041) An alert "cannot connect to remote server" may appear sometimes when launching TV app.
- Mic port in some USB sound cards cannot be detected due to HD Station's limitation.
- Web app only supports IE 11 or higher, but Chrome/Firefox/Safari is no problem.
- The transcode function does not support files with Dolby/DTS audio encoding (including AC3).
- Not compatiable with old Mobile apps (iOS: v2.1.1, Android: v2.1.0.3).






---
---
---


### v2.0.6 release notes

#### Previous Version In App Center
---
v1.421.4 / v.1.430.4 (20170313)

#### Features
---

- User can import songs from any folder (USB disk included), no need to rename lots of files from now on.
- User can maintain Karaoke songs' Metabase in a straightforward process.
- Search local or cloud songs getting more easily.
- Support transparent Metabase migration, migration may need several minutes according to the song count.

#### Enhancements
---

###### Server
- Enhance the stability.
- Performance tuning.


###### Web
- UI redesign that user can finish tasks more quickly in the current scenario (singing or management).


###### TV
- Redesign home screen, also make screen flow more logical and friendly.
- Enhance the stability.
- Performance tuning.


#### Fixes
---


###### Server
- [#102436](http://172.17.25.222/bugzilla/show_bug.cgi?id=102436) disable OceanKTV app in App Center shall also disable TV app.
- [#102476](http://172.17.25.222/bugzilla/show_bug.cgi?id=102476) wrong detection of "audio out" and "mic in" port map in some model.
- [#73084](http://172.17.25.222/bugzilla/show_bug.cgi?id=73084) invalid search reuslt when keyword contains special characters.


###### Web
- [#102343](http://172.17.25.222/bugzilla/show_bug.cgi?id=102343) metadata edit not work as expected.
- [#102488, #102532, #102550, #102568, #102574, #102604, #102600, #102610, #102895, #102897, #102899, #104571] UI issues.


###### TV
- [#102493](http://172.17.25.222/bugzilla/show_bug.cgi?id=102493) playing hangs when song file moved or deleted.
- [#103146](http://172.17.25.222/bugzilla/show_bug.cgi?id=103146) app hangs when press power key on remote controller.
- [#93555, #93560, #94065, #94905, #94908, #94958, #95131, #95221, #103127, #103140] unstable screen navigation and many unexpected behavior.
- [#101047](http://172.17.25.222/bugzilla/show_bug.cgi?id=101047) Audio channel will not come back to stereo.



