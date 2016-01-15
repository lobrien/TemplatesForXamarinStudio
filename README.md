# Templates for Xamarin Studio

Compile with `/Applications/Xamarin\ Studio.app/Contents/MacOS/mdtool setup pack Manifest.addin.xml`

To add new projects: 

* In `manifest.xml` add new `Addin/Runtime/Import" elements and new "ProjectTemplate" elements. ProjectTemplate items must have unique id and then path to their  source.

* In `/templates`, create the specific variations. 
