# Readme

This repo exists to help you out in case you are trying to use / compile a particular revision of OpenFrameworks Master branch roughly between mid 2016 and early 2018. 

When you try to run the `\OpenFrameworks\scripts\YOUR_PLATOFRM\download_libs.sh` script, you will notice it fails (beacuse the script tries to download some zip files from ci.openframeworks.cc that are no longer there).

To solve for this, replace `\OpenFrameworks\scripts\dev\download_libs.sh` with the `download_libs.sh` in this repo.

Then go ahead and run your platfrom's download script (ie OpenFrameworks\scripts\osx\download_libs.sh for osx) and it all should work.

See this [issue](https://github.com/openframeworks/openFrameworks/issues/5903) for more info.