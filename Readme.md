<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128576483/15.2.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T312237)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
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


