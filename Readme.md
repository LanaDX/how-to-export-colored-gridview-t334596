# How to export colored GridView


<strong>UPDATED:</strong><br><br>Starting with version v2015 vol 2 (v15.2), this functionality is available out of the box. Use <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcGridViewSettings_FormatConditionstopic">GridViewSettings.FormatConditions</a> rules to define conditional formatting in Browse Mode and keep the applied appearance in the Exported Document. Please refer to the <a href="https://community.devexpress.com/blogs/aspnet/archive/2015/11/10/asp-net-grid-view-data-range-filter-adaptivity-and-more-coming-soon-in-v15-2.aspx">ASP.NET Grid View - Data Range Filter, Adaptivity and More (Coming soon in v15.2)</a> blog post and the <a href="http://demos.devexpress.com/MVCxGridViewDemos/Exporting/ExportWithFormatConditions">Export with Format Conditions</a> demo for more information.<br>If you have version v15.2+ available, consider using the built-in functionality instead of the approach detailed below.<br><br>If you need to apply custom appearance in the Exported Document only or define fine tuned complex appearance (for instance, based on some runtime calculated values, custom business rules, etc.), use the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcMVCxGridViewExportSettings_RenderBricktopic">GridViewSettings.SettingsExport.RenderBrick</a> event in the <strong>WYSIWYG</strong> export mode.<br><br><strong>See Also:</strong><br><a href="https://www.devexpress.com/Support/Center/p/E4098">E4098: How to export a colored grid when the Data Aware export mode is used</a>

<br/>


