# Release Notes

### 1.2.0

**🎉 Released:**
- 20th June 2023

**🥳 New Features:**
- The main Marker Toolbox application now shows the full user interface, so that you can use it as a standalone application - instead of just as a Final Cut Pro Workflow Extension.
- Added a **Save Resolve EDL** button, to allow you to export comments as a Resolve EDL. Thanks for suggesting Scott Simmons!
- Added a **Save FCPXML** button, allowing you to save a FCPXML without Final Cut Pro running.
- Added ability to **Apply Markers to Existing Final Cut Pro Clip**. This allows you to drag in a Clip, Multicam Clip or Synchronised Clip from Final Cut Pro, apply markers to it, then send it back to Final Cut Pro. Thanks for your suggestions Iain Anderson & Kevin Luk!
- We now support the Frame.io `FIOJSON` format, including annotations. Whilst the official Frame.io Workflow Extension does essentially do exactly the same thing as Marker Toolbox, the titles imported are basically unreadable, so Marker Toolbox corrects this. We also have slightly nicer/simpler looking arrow annotations. Marker Toolbox also seems to render annotations more correctly than the Workflow Extension in some cases (i.e. there are times when annotations seem to be missing from the Frame.io Workflow Extension). Thanks for suggesting Jeff Asher & Benjamin Evans!
- Over the last week Dropbox accidentally broke `JSON` exporting support for Dropbox Replay, and when they fixed it, they accidentally used the "condensed version" (used by `CSV`) of the `JSON`. This has now been fixed on the Dropbox Replay end, however Marker Toolbox now supports this alternative `JSON` format, just incase it ever happens again.

---

### 1.1.0

**🎉 Released:**
- 16th May 2023

**🥳 New Features:**
- Added [Wipster](https://www.wipster.io) CSV support. Thanks for suggesting Alister Robbie!

**🔨 Improvements:**
- The **Process Comments Locally** algorithm now supports time units without spaces in-between (i.e. "1hr10mins"), and shortened time units (i.e. "h", "m", "s", "f"). Thanks for reporting Matthieu Laclau!

---

### 1.0.1

**🎉 Released:**
- 8th April 2023

**🥳 New Features:**
- Added support for Dropbox Replay JSON files. Thanks for suggesting Aaron Trinder!

**🔨 Changes:**
- Vimeo CSV files will now use Frame Rate setting, instead of defaulting to 25fps.

---

### 1.0.0

**🎉 Released:**
- 6th April 2023

This is the first release of Marker Toolbox. Woohoo!