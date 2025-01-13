# Release Notes

### v1.4.2 (20)

**🎉 Released:**
- 6th January 2025

**🐞 Bug Fix:**
- The "Apply Markers to Existing Final Cut Pro Clip" drop zone now works correctly with FCPXML v1.13 and Final Cut Pro 11. Thanks for reporting Jeff Roy!

---

### v1.4.1 (19)

**🎉 Released:**
- 13th August 2024

**🐞 Bug Fix:**
- Fixed a bug/regression introduced in the v1.4.0 update where we accidentally broke "Process Comments Locally". Apologies! HUGE thanks to KenHell, Maksim Tarasenko, Gary Roll and Hamin Yoon for reporting!

---

### v1.4.0 (18)

**🎉 Released:**
- 2nd August 2024

**🔨 Improvements:**
- Added support for Adobe Premiere CSVs. Thanks Michael Angelo!
- Wipster CSV support has been improved. We now display replies properly.
- Frame.io FIOJSON  support has been improved. The markers on 29.97fps projects should now more accurately match the Frame.io website. Thanks Shih-Cheng Yang!
- All of the timecode processing logic and maths has been completely redesigned and rewritten, so that we can better support all frame rates, and ensure everything is frame accurate. We now use TimecodeKit for timecode handling. HUGE thanks to Steffan Andrews for his incredible work!
- The default ChatGPT prompt has been updated to work in frames, rather than seconds for better accuracy. If you have a custom prompt, you should press the "Reset Prompt" button in the bottom settings to update the prompt to the new format.
- The latest OpenAI ChatGPT models are now supported.

---

### v1.3.2 (17)

**🎉 Released:**
- 6th May 2024

**🐞 Bug Fix:**
- Fixed support for the latest Frame.io V4 FIOJSON format. Thanks for reporting D.L. Watson!

---

### v1.3.1 (15)

**🎉 Released:**
- 24th April 2024

**🐞 Bug Fix:**
- Fixed support for the latest Vimeo CSV format. Thanks for reporting Dave & YevantZ!

---

### v1.3.0 (14)

**🎉 Released:**
- 30th June 2023

**🥳 New Features:**
- Added the ability to export Avid Media Composer Marker Text files. Thanks for suggesting Scott Simmons!
- Added support for importing the Timecode+ TSV format. Thanks for suggesting pulpjedi!

**🔨 Improvements:**
- Various improvements to the user interface. Marker Toolbox now looks a lot nicer!
- We moved the OpenAI API key into the Settings panel, and added a "Validate" button so that you can check that the API key is valid.
- All settings are now saved between the main application and the Final Cut Pro Workflow Extension, meaning that if you change a setting in the Workflow Extension, it will also change in the main application and vice versa.

---

### v1.2.0 (11)

**🎉 Released:**
- 22nd June 2023

**🥳 New Features:**
- The main Marker Toolbox application now shows the full user interface, so that you can use it as a standalone application - instead of just as a Final Cut Pro Workflow Extension.
- Added a **Save Resolve EDL** button, to allow you to export comments as a Resolve EDL. Thanks for suggesting Scott Simmons!
- Added a **Save FCPXML** button, allowing you to save a FCPXML without Final Cut Pro running.
- Added ability to **Apply Markers to Existing Final Cut Pro Clip**. This allows you to drag in a Clip, Multicam Clip or Synchronised Clip from Final Cut Pro, apply markers to it, then send it back to Final Cut Pro. Thanks for your suggestions Iain Anderson & Kevin Luk!
- We now support the Frame.io `FIOJSON` format, including annotations. Whilst the official Frame.io Workflow Extension does essentially do exactly the same thing as Marker Toolbox, the titles imported are basically unreadable, so Marker Toolbox corrects this. We also have slightly nicer/simpler looking arrow annotations. Marker Toolbox also seems to render annotations more correctly than the Workflow Extension in some cases (i.e. there are times when annotations seem to be missing from the Frame.io Workflow Extension). Thanks for suggesting Jeff Asher & Benjamin Evans!
- Over the last week Dropbox accidentally broke `JSON` exporting support for Dropbox Replay, and when they fixed it, they accidentally used the "condensed version" (used by `CSV`) of the `JSON`. This has now been fixed on the Dropbox Replay end, however Marker Toolbox now supports this alternative `JSON` format, just incase it ever happens again.

---

### v1.1.0 (9)

**🎉 Released:**
- 16th May 2023

**🥳 New Features:**
- Added [Wipster](https://www.wipster.io) CSV support. Thanks for suggesting Alister Robbie!

**🔨 Improvements:**
- The **Process Comments Locally** algorithm now supports time units without spaces in-between (i.e. "1hr10mins"), and shortened time units (i.e. "h", "m", "s", "f"). Thanks for reporting Matthieu Laclau!

---

### v1.0.1 (8)

**🎉 Released:**
- 8th April 2023

**🥳 New Features:**
- Added support for Dropbox Replay JSON files. Thanks for suggesting Aaron Trinder!

**🔨 Changes:**
- Vimeo CSV files will now use Frame Rate setting, instead of defaulting to 25fps.

---

### v1.0.0 (7)

**🎉 Released:**
- 6th April 2023

This is the first release of Marker Toolbox. Woohoo!