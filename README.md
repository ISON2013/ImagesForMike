# ImagesForMike
The Notebook code and output images for Dr Michael Roman's paper, covering the years 2020-2000. 

All processed images found in MikeFITS. 

The images are corrected using the I/F factor (possibly without CTE corrections, when I was writing the data section of my report I realised that I may have been using the wrong versions of the files, once my April 9th deadlines are out of the way, I'll investigate it and if needed re-update this section)

WFPC2 images are "fudged" calibration, as this excerpt from my 4 year MPhys project states:
"There was an issue which occurred when calibrating the WFPC2 data to
the WFC3, as after calculating the reflectance with the I/F calculation function, the older data appeared systematically dimmer than the newer WFC3
data. As Neptune appeared to be in a relatively stable state of brightness
across all filters between the years of 2004-2008, and then again in 2009-2011
(one of the reasons for the gap in imagery between 2011 and 2015), it was
decided that the assumption that Neptune didn’t change very much in the
one year between the image in 2008, and the image in 2009 was valid. In
addition to this, the methane absorption band filters in WFPC2 were highly
vignetted, as well as the plate scale (one of the inputs to the I/F equation)
being resampled from the original value of WFPC2. As both the filter properties and the plate scale of the detector are vitally important to the I/F
calculation, and could be the potential source of the error, the WFPC2 I/F
values were manually modified by adjustment of the PlateScale term to ensure the
mean albedo across the entire planetary disk remained consistent before and
after the WFPC2-WFC3 transition." 
This correction can be seen in MapFunc.py

The list of images which were used to make this data can be found in the excel spreadsheet. 

The notebook also prints the expected position of the planicentre, however it can be seen that this might be a little inaccurate, it is probably best to apply your own algorithms to that.
