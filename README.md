Annotations for the MSTestExtensions package (extensions for MSTest).

This is useful because tests based on the BaseTest class will assert with extensions methods on the inherited IAssertion object instead of the "normal" static methods of the Assert class. These extensions methods have a similar signature but are not covered by the standard Resharper annotations.

These external annotations are (for the most part) copied from the standard annotations for the Microsoft.VisualStudio.QualityTools.UnitTestFramework assembly.
