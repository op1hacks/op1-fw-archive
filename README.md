# OP-1 Firmware Archive

An archive of (almost) all OP-1 firmware versions with additional info about each file.


## Versions

Versions are listed in chronological order.

### [op1_11701.op1](raw/master/firmware/op1_11701.op1)

    - FIRMWARE VERSION: UNKNOWN
    - BUILD VERSION: 11701
    - BUILD DATE: 2011/05/20
    - BUILD TIME: 19:58:21
    - BOOTLOADER VERSION: 1.20
    - OLDEST FILE: 2011/03/02 15:44
    - NEWEST FILE: 2011/05/20 17:59

*Change Log*

No reset should be needed to install this OS. But if you have old sampler patches with the same name they need to be manually removed via disk mode one by one.

* Switching instrument while receiving external MIDI could sometimes trigger an error. Fixed.
* When switching between synth and drum with sequencers active in both modes an error would sometimes trigger. Fixed.
* What-you-hear was not possible to record to tape. Fixed.
* Solo was not kept if navigating away from the tape screen. Fixed. 
* Sliding of clips could sometimes make the audio go silent. Fixed.
* Solo was disabled when the tape was in record. Fixed.
* Snapshots saved within the same minute would get the same name. Fixed.
* Snapshots could not be renamed. Fixed.
* When sampling with the sequencer on Hold the OP-1 would crash. Fixed.
* When recording in loop mode near the end of the tape an error could be triggered. Fixed.
* OP-1 adjusts USB power usage to what is available from USB host. The OP-1 now works with iPad.
* Improved USB dedicated charger detection.
* Disk mode has been updated.
* USB stability has been improved.


### [op1_11855.op1](raw/master/firmware/op1_11855.op1)

    - FIRMWARE VERSION: UNKNOWN
    - BUILD VERSION: 11855
    - BUILD DATE: 2011/06/16
    - BUILD TIME: 16:20:46
    - BOOTLOADER VERSION: 1.28
    - OLDEST FILE: 2011/03/02 15:46
    - NEWEST FILE: 2011/06/16 14:25

*Change Log*

We recommend everyone that is upgrading from an OS lower then #11851 to do a "8". Format Drive in the TE-Boot menu.
Doing a Format is only needed the first time this OS is installed. Remember to backup your data!

* Factory Presets have been added.
* Sustain loops and base note are now imported into synth sampler patches.
* Disk Mode now listens to the 'Eject' USB message.
* After extended usage in certain conditions the OP-1 could get into a state that required a reset. Fixed.
* When using octave shift and pitch at the same time in the Drum Sampler the pitch would sometimes be incorrect. Fixed. 
* When switching between sounds in the presetbrowser and playing at the same time under certain conditions an error would rigger. Fixed.
* The Drum Sampler could under rare conditions trigger an error. Fixed.
* When using the Synth Sampler and the Value LFO on loop points an error could be triggered. Fixed.
* Notes could get stuck in the presetbrowser. Fixed.
* USB MIDI was disabled if USB Disk Mode had previously been used. Fixed.
* When the snapshot space was full a cryptic icon was displayed. Fixed.
* In Drum mode the MIDI Note number sent was incorrect. Fixed.
* Value LFO sent to Drum Pitch did not function. Fixed.
* Value LFO sent to Synth Sampler Start did not function. Fixed.
* Not all values that should was saved on power off. Fixed.
* At the very start and end of the tape a squeal could be heard when scrubbing. Fixed.


### [op1_12011.op1](raw/master/firmware/op1_12011.op1)

    - FIRMWARE VERSION: UNKNOWN
    - BUILD VERSION: 12011
    - BUILD DATE: 2011/09/29
    - BUILD TIME: 13:47:59
    - BOOTLOADER VERSION: 1.31
    - OLDEST FILE: 2011/03/30 08:32
    - NEWEST FILE: 2011/09/29 13:38


### [op1_12234.op1](raw/master/firmware/op1_12234.op1)

    - FIRMWARE VERSION: R. 12234
    - BUILD VERSION: 12234
    - BUILD DATE: 2011/12/05
    - BUILD TIME: 12:10:14
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2011/03/30 08:32
    - NEWEST FILE: 2011/12/05 11:14


### [op1_12469.op1](raw/master/firmware/op1_12469.op1)

    - FIRMWARE VERSION: R. 12469
    - BUILD VERSION: 12469
    - BUILD DATE: 2012/01/19
    - BUILD TIME: 05:24:14
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2010/06/09 17:44
    - NEWEST FILE: 2012/01/19 04:36


### [op1_12470.op1](raw/master/firmware/op1_12470.op1)

    - FIRMWARE VERSION: R. 12470
    - BUILD VERSION: 12469:12470 (modified)
    - BUILD DATE: 2012/01/20
    - BUILD TIME: 09:00:48
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2010/06/09 17:44
    - NEWEST FILE: 2012/01/20 16:42

*Change Log*

* Added Finger sequencer.
* Added DrumBox drum synth.
* Added Drum key copy.
* Added ChopLifter.
* Added MIDI Timing Clock.
* Added MIDI LFO.
* Tape did not stop at end of tape. Fixed.
* Drum voices could be interrupted. Fixed.
* Pressing Help would trigger an assert when the battery was low. Fixed.
* Tap Tempo is improved.


### [op1_12616.op1](raw/master/firmware/op1_12616.op1)

    - FIRMWARE VERSION: R. 12616
    - BUILD VERSION: 12616
    - BUILD DATE: 2012/03/21
    - BUILD TIME: 17:58:54
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2012/03/21 14:16
    - NEWEST FILE: 2012/03/21 17:00

*Change Log*

* Tape import from external material now possible.
* Added MIDI Start and Stop.
* Added Finger key copy.
* Sequencers now respond to external MIDI notes.
* Battery indicator improved.
* Added MIDI indicators in the signal flow screen.
* Added Hi Res rec level control in tape screen with shift.
* Drum Sampler snapshot saving did not always function correctly. Fixed.
* What you hear downmix was not done correctly. Fixed.
* Ghost jumps backwards could sometime result in a gap in playback. Fixed.
* LFO did not update all graphics correctly. Fixed.


### [op1_12788.op1](raw/master/firmware/op1_12788.op1)

    - FIRMWARE VERSION: R. 12788
    - BUILD VERSION: 12788
    - BUILD DATE: 2012/05/25
    - BUILD TIME: 15:34:52
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2011/03/02 15:46
    - NEWEST FILE: 2012/05/25 15:08


### [op1_13042.op1](raw/master/firmware/op1_13042.op1)

    - FIRMWARE VERSION: R. 13042
    - BUILD VERSION: 13042
    - BUILD DATE: 2012/08/28
    - BUILD TIME: 17:04:53
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2011/03/02 15:46
    - NEWEST FILE: 2012/08/28 15:08

*Change Log*

* Nitro effect added.
* Crank LFO added.
* Bend LFO added.
* Crank mode in Endless added.
* Crank mode in Tombola added.
* Ableton Live controller mode added.
* Fallback to Internal Sync added.
* When doing a Tape Erase with Album playing the audio would loop. Fixed.
* Doing a Tape Lift during some conditions could trigger an assert. Fixed.
* Pro Tip: Shift+Synth & Shift+Drum to Recall the current patch.


### [op1_13585.op1](raw/master/firmware/op1_13585.op1)

    - FIRMWARE VERSION: R. 13585
    - BUILD VERSION: 13585
    - BUILD DATE: 2013/05/25
    - BUILD TIME: 20:08:25
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2013/04/04 11:54
    - NEWEST FILE: 2013/05/26 15:25

*Change Log*

* DNA synth added.
* CWO effect added.


### [op1_13747.op1](raw/master/firmware/op1_13747.op1)

    - FIRMWARE VERSION: R. 13747
    - BUILD VERSION: 13747
    - BUILD DATE: 2013/10/02
    - BUILD TIME: 17:20:23
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2012/03/21 14:16
    - NEWEST FILE: 2013/11/11 20:22


### [op1_14167.op1](raw/master/firmware/op1_14167.op1)

    - FIRMWARE VERSION: R. 14167
    - BUILD VERSION: 14167
    - BUILD DATE: 2014/03/25
    - BUILD TIME: 00:35:53
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2013/12/06 08:53
    - NEWEST FILE: 2014/03/24 23:59


### [op1_14203.op1](raw/master/firmware/op1_14203.op1)

    - FIRMWARE VERSION: R. 14203
    - BUILD VERSION: 14203
    - BUILD DATE: 2014/04/15
    - BUILD TIME: 10:15:36
    - BOOTLOADER VERSION: 1.35
    - OLDEST FILE: 2013/12/06 08:53
    - NEWEST FILE: 2019/04/25 13:42

*Change Log*

* DSynth synthesizer engine
* Sketch sequencer
* Master tune
* M1 and M2 now works together


### [op1_218.op1](raw/master/firmware/op1_218.op1)

    - FIRMWARE VERSION: R. 00218
    - BUILD VERSION: 00218
    - BUILD DATE: UNKNOWN
    - BUILD TIME: UNKNOWN
    - BOOTLOADER VERSION: 2.02
    - OLDEST FILE: 2016/01/25 10:34
    - NEWEST FILE: 2019/04/25 13:42


### [op1_220.op1](raw/master/firmware/op1_220.op1)

    - FIRMWARE VERSION: R. 00220
    - BUILD VERSION: 00220
    - BUILD DATE: 2017/04/19
    - BUILD TIME: 22:03:30
    - BOOTLOADER VERSION: 2.11
    - OLDEST FILE: 2016/01/25 10:34
    - NEWEST FILE: 2017/04/20 08:17


### [op1_225.op1](raw/master/firmware/op1_225.op1)

    - FIRMWARE VERSION: R. 00225
    - BUILD VERSION: 00225
    - BUILD DATE: 2017/07/17
    - BUILD TIME: 12:10:00
    - BOOTLOADER VERSION: 2.13
    - OLDEST FILE: 2017/07/01 09:11
    - NEWEST FILE: 2017/07/17 10:12

*Change Log*

* all new presets
* new synth voltage
* new sequencer arpeggio
* tape loops are now automatically crossfaded
* tape effect chop twice as short
* tape effect chop now works at tape start/stop position and across loop wrap 
* in the fm radio press green encoder to autotune
* endless sequencer extended to 128 steps
* tremolo lfo updated with extra waveforms
* PO sync mode added
* sync to external midi clock now directly drives sequencers
* added tempo nudge when running on external tempo


### [op1_235.op1](raw/master/firmware/op1_235.op1)

    - FIRMWARE VERSION: R. 00235
    - BUILD VERSION: 00235
    - BUILD DATE: 2019/01/07
    - BUILD TIME: 17:45:00
    - BOOTLOADER VERSION: 2.18
    - OLDEST FILE: 2017/05/02 12:11
    - NEWEST FILE: 2019/04/25 12:06

*Change Log*

* shift + stop toggles hi-res tape grid for editing
* when in external sync sequencers are now started in sync with the beat
* pattern sequencer did not always play correctly when triggered from external MIDI: fixed.
* dropping a synth sample patch on a synth slot could under some circumstances generate an assert: fixed.
* when lifting clips from a loop sometimes the cut was not perfect: fixed.
* tape/mixer mutes was not faded like tape solo is: fixed.


## Missing files

* op1_11029.op1
* op1_11082.op1
* op1_11230.op1
* op1_11346.op1
* op1_11381.op1
* op1_11479.op1
* op1_216.op1 (private beta)


## Sources

* https://teenage.engineering
* http://oper8.free.fr/op1_os
* https://op-forums.com
