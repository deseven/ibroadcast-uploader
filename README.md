# iBroadcast Uploader
Based on the original Python script from https://project.ibroadcast.com

## What's new in 0.6.1
 - Fix bug in reference to parallel_uploads argument 

## What's new in 0.6
 - The accepted range specified for '--parallel-uploads' was wrong. Fixed to accept numbers from 1 to 6. Default kept at 3.
 - Added the "--playlist", "--tag", and "--reupload" command line arguments

## What's new in 0.5
 - fixed parsing directories with special characters in their names
 - added progress bar
 - added local MD5 cache to skip hash recalculation every time
 - added command line arguments (directory, confirmation skip, parallel uploads, verbose and silent modes)
