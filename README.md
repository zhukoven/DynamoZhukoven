Zhukoven.com is a custom Dynamo package for the Revit users. It helps automate repeatable tasks, overcome Revit and Dynamo limitations, 
and provides you with workarounds to increase productivity and save time.

# Current version compatibility
Zhukoven package is currently developed in Dynamo `2.3` 🐢 and does not support Dynamo `1.3.X` 💔 due to the breaking changes in the `.dyf` and `.dyn` file formats.

|Package version|Target Dynamo version|Target Revit version|Support status|
|---|---|---|---|
|2021.2.27|Dynamo 2.3.0|Revit 2020.2.3|✅ Current|
|[2019.5.7](https://dynamopackages.com/download/591b1d834f57b8e070000005/2019.5.7)|Dynamo 1.3.3|Revit 2017|⛔ Discontinued|

If you are looking for the older versions of the package, please visit the [Dynamo packages website](https://dynamopackages.com/) or Dynamo package manager.

# Installation
To install this custom Dynamo package simply use the built-in Dynamo package manager.
If you are not comfortable with the package manager, then download the `zip` file with the source code and extract its contents to the following path:   
`%appdata%\Dynamo\Dynamo Revit\2.3\packages\Zhukoven.com\`

# Known issues
Dynamo 2.x breaks some of the Inputs inside the custom nodes that worked in Dynamo 1.x. That's why one may notice that some of the nodes have lost connection wires in Dynamo 2.x.
