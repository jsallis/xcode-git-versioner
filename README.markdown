xcode-git-versioner
===================

xcode-git-versioner is an Xcode auto-versioning script written in Ruby which updates your Info.plist file CFBundleVersion to the latest git revision number

Usage
-----

1. Right-click the target you want to add the versioning phase to (usually the target that builds your app)
2. Select: Add -> New Build Phase -> New Run Script Build Phase
3. Specify /usr/bin/ruby as the Shell for the script
4. Paste the script body into the Script text area
5. Ensure that the build phase is at the end of the target's list of build phases 

Credits
-------

The script is based on an original Perl script by Marcus S. Zarra and Matt Long available [here](http://www.cimgf.com/2008/04/13/git-and-xcode-a-git-build-number-script/).
