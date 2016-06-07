# volcrash
Updated volatile patch for crash.

**_I am not the original author of this patch_**, but found I needed to update the patch ever so slightly to enable the `--volatile` functionality in crash. 

The original post may be found here: http://volatilesystems.blogspot.com.au/2008/07/linux-memory-analysis-one-of-major.html

Whilst I imagine most people who need apply this patch are probably more than capable of modifying the 4.0.6 patch to work with later versions, I've shared the patch here in case it helps someone out.

This has been updated and tested on crash 7.1.5

Apply patch with the usual `patch -p1 < volcrash-7.1.5.patch`
Build with `make`

This will enable the `--volatile` switch to allow crash to work with volatile memory images, refer to post above.


