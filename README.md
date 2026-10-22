sooperlooper-lv2
=======================

An LV2 version of the old LADSPA [SooperLooper plugin by Jesse Chappell](http://essej.net/sooperlooper/oldplugin.html).
This is a fork of [MOD Audio's LV2 plugin](https://github.com/mod-audio/sooperlooper-lv2-plugin).

Currently it supports:

 * stereo in/out
 * record/overdub
 * play/pause
 * undo
 * redo

Changes compared to MOD Audio's variant:

 * Only stereo supported
 * record implies playing (original made distinction, could not record if play was also not active)
 * wet level in dB instead of normalized 0-1 range
 * removed dry level control
