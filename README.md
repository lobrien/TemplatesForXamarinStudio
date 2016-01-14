# Templates for Xamarin Studio

Currently, this is just the Single File F# solution.

Compile with `/Applications/Xamarin\ Studio.app/Contents/MacOS/mdtool setup pack Manifest.addin.xml`

TODO:
[ ] Add in multiple F# single-file solutions, i.e., table-based
This is done by adding in `manifest.xml` new `Addin/Runtime/Import" elements and new "ProjectTemplate" elements. ProjectTemplate items must have unique id and then path to their  source.

[ ] Add in C# simple solutions, but maybe as a separate add-in. (There are two potential add-ins here: "F# Power Templates" and "Debugging Templates")

