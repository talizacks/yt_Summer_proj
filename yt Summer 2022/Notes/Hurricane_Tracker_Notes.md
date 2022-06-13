# **Hurricane Tracker Notes**
- Stuck:
	- What are the axes???
		- In the documentation, they say that the shape of the files is (3408, 10, 128, 257, 6) but we have it as (142, 24, 10, 128, 257, 6). But they also say that the width and height are 128 and 257, respectively. 128x257 pixels is the dimensionality of each plot so maybe we aren't varying height at all. Perhaps, height and width are their backwards way of referring to lat and lon. But then there is the question of what are we varying?
		- {![[img_trn_vid2.mov]]}