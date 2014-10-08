morganp-lightroom-presets
=========================

My personal library of presets for Adobe Lightroom.   
Idea of making these public came from [synapticism](https://github.com/synapticism/synaptic-lightroom-presets).

My presets are stored in :

    ~/Library/Application Support/Adobe/Lightroom/

Metadata Presets
==

2014 Copyright.lrtemplate
--
This is used on import to set the copyright for each image. Unfortunately it requires to be regenerated each year with the correct year. The settings are:

		copyright          = "Copyright 2014 Your Name. All Rights Reserved.",
		copyrightState     = true,
		creator            = "Your Name",
		creatorCity        = "complete",
		creatorWorkEmail   = "your@email",
		creatorWorkWebsite = "your_website",
		rightsUsageTerms   = "No rights granted without prior written permission.",


Export Presets
==

BlogW100-jpg-70
--

1. Outputs to a specific folder.
2. jpg set to [70%][jef_jpg].
3. long edge sized to 1000px.
4. [Output Sharpening][3phasesharp] for screen enabled.

Jpeg-92
--

1. Choose Folder Later. 
2. File name use the 'morganp-DATE-JobID-fname' template.
3. jpg set to [92%][jef_jpg].

Manually choose my DRV (Derivative) Folder for the shoot, 92% Quality has very little drop in quality with a large reduction in filesize. This is used for my final copies.



Filename Templates
==

morganp-DATE-JobID-fname
--

This allows exporting to files which follow conventions discussed in the [DAM (Digital Asset Managment)][dam] Book.

1. Unique identifier to me. (morganp)
2. Shoot date of image for effective sorting (YYYYMMDD)
3. Shoot Identifier, Stored in the JobID iptc field.
4. Original filename of RAW file.


[jef_jpg]: http://regex.info/blog/lightroom-goodies/jpeg-quality
[3phasesharp]: http://www.graphics.com/article-old/multipass-photoshop-sharpening-workflow
[dam]: https://www.amazon.co.uk/dp/0596523572?tag=morgue-21&camp=2902&creative=19466&linkCode=as4&creativeASIN=0596523572&adid=13SPKZJKBGHHH2HB82FN&
