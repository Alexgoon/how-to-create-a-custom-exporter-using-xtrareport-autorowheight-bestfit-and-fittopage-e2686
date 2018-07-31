# How to create a custom exporter using XtraReport (AutoRowHeight, BestFit and FitToPage)

*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs#L43-L56) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
* [Error.aspx](./CS/WebSite/Error.aspx) (VB: [Error.aspx](./VB/WebSite/Error.aspx))
* [Error.aspx.cs](./CS/WebSite/Error.aspx.cs) (VB: [Error.aspx.vb](./VB/WebSite/Error.aspx.vb))
* **[PivotReportGenerator.cs](./CS/WebSite/App_Code/PivotReportGenerator.cs)** **(VB: [PivotReportGenerator.vb](./VB/WebSite/App_Code/PivotReportGenerator.vb))**


<p>This is an ASP version of the <a href="https://www.devexpress.com/Support/Center/p/E2231">How to create a custom exporter for the PivotGridControl by using the XtraReport suite</a> example that implements following suggestions:<br /><a href="https://www.devexpress.com/Support/Center/p/S130430">S130430: Support word wrap when printing and exporting</a><br /><a href="https://www.devexpress.com/Support/Center/p/S91257">S91257: Utilize a Line color when printing</a><br /><a href="https://www.devexpress.com/Support/Center/p/AS9011">AS9011: Print row headers on every page on export/printing</a><br />and the <a href="https://www.devexpress.com/Support/Center/p/S18650">S18650: Add an event that allows to provide custom size for field values (MeasureFieldValue, or so)</a>  suggestion for printing facilities.</p>

<br/>


