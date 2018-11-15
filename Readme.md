<!-- default file list -->
*Files to look at*:

* **[CureClusterer.cs](./CS/CustomClustererSample/CureClusterer.cs) (VB: [CureClusterer.vb](./VB/CustomClustererSample/CureClusterer.vb))**
* [Form1.cs](./CS/CustomClustererSample/Form1.cs) (VB: [Form1.vb](./VB/CustomClustererSample/Form1.vb))
* [Tree.cs](./CS/CustomClustererSample/Tree.cs) (VB: [Tree.vb](./VB/CustomClustererSample/Tree.vb))
<!-- default file list end -->
# How to implement a custom clusterer


This example demonstrates how to implement a custom clusterer.


<h3>Description</h3>

To do this, design a class implementing&nbsp;the&nbsp;<strong>IClusterer&nbsp;</strong>interface.&nbsp;<br />The&nbsp;owner's O<strong>nClustered</strong>&nbsp;method should be called to notify the owner adapter that clustering is finished.<br />Note that for a newly created collection of cluster representatives, the owner is specified as parameter of the constructor.

<br/>


