# How to handle a mouse click to obtain dashboard item's data in the WinForms Dashboard Viewer


The following example demonstrates how to get client data corresponding to a particular visual element using DashboardViewer's API.<br>In this example, the <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardWinDashboardViewer_DashboardItemClicktopic">DashboardViewer.DashboardItemClick</a> event is handled to obtain client data for the <a href="http://documentation.devexpress.com/#Dashboard/CustomDocument15263">Card</a> dashboard item and display this data in a <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument8117">Chart control</a>. We obtain axis points placed on the <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardCommonDashboardDataAxisNamesMembersTopicAll">"Sparkline" axis</a> for the clicked card, determine corresponding actual/target values, and save these values to a data table. This table is used as a data source for the Chart control. 

![](https://github.com/BrianDX/how-to-obtain-a-dashboard-items-client-data-in-the-winforms-viewer-t140553/blob/18.1.3%2B/images/winforms-dashboard-obtain-client-data-click.png)

See Also:<br><a href="https://www.devexpress.com/Support/Center/p/T359303">T359303: How to get data from a clicked dashboard item (WinForms)</a.




