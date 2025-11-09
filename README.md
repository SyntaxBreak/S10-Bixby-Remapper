# S10 Bixby Remapper
A Kernel SU Bixby remapping module to address the EroFS filesystem of ExtremeROM V2.6+

This is still a very rough version of the project so use it at your own risk. I made this because I could no longer directly update the keylayout file of my S10+ after [ExtremeROM](https://github.com/ExtremeXT/ExtremeROM/releases/tag/v2.6.0) changed to EroFS system partition after version 2.6.

Later on, I plan to make this customisable through either an initial setup or WebUI for choosing a specific function to remap to (taken from [this](https://xdaforums.com/t/root-remap-bixby-button-with-simple-double-and-long-press.3839544/) list). For now it **hardcoded** to be `MEDIA_PLAY_PAUSE`. If you want to manually edit this, change line #481 `key 703` in Generic_internal.kl.

Enjoy!
