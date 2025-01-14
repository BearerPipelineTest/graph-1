This folder contains code snippets and samples referenced by the book as well as additional sample files. More samples will be added over time.


Note that files with a ".groovy" extension but with all lowercase names are intended to be launched from within the Gremlin Console. Files with a ".groovy" extenstion and capitalized names, such as TinkerGraphTest.groovy, are stand alone groovy applications that should be run from outside of the console using the groovy runtime.

Files with a ".java" extension are stand alone Java applications that need to be compiled and run using a Java JDK and require the Apache TinkerPop Java JAR files to ve available.

Files that have "remote" in the name such as `RemoteStats.java` are designed to be run against a Gremlin Server rather than a local in memory TinkerGraph. It is important to understand the differences between these two environments and that is what these samples aim to help with.

Files with a ".py" extension are stand alone Python applications that require the Gremlin Python library to have been installed using PIP or an equivalent method. 

Files with a ".cs" extension are C# files that require a Microsoft .Net runtime and the Gremlin.Net driver installed via NuGet or similar. 

Files with a ".js" extension are JavaScript files designed to be run using Node.js and the Gremlin JavaScript driver available from NPM.

Files with a ".go" extension are Go files designed to be compiled and run using the Apache TInkerPop Go client, launched in April 2022

Some of the samples use data from CSV files that can be found in the *'/sample-data'* folder.
