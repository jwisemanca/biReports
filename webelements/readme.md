<table width=100% border=0>
<tr ><td colspan=2><h1>webElements</h1></td></tr>
<tr><td>&nbsp;A Custom Function Library for Crystal Reports</td></tr>
</table>

## Description

This GitHub repository is for the <b>free / open source</b> webElements Custom Function library for Crystal Reports on SAP BI / BusinessObjects Enterprise 4.3 / Crystal Reports Server 2020. This library allows a report developer to add web controls to a Crystal Report when running in the DHTML Viewer.
<br>

![wepic](/webelements/admin/ppsm.jpg)

### webElements Can be Used by Report Developers To:

1. Embed different types of web controls into a SAP BI Crystal Report to create custom prompt interfaces.
1. Create dashboard-style reports with more interactivity.
1. Develop interfaces / forms for write-backs to the database, using target reports based on a stored procedure.
1. Create workflows to pass filtered & selected data to another report.
1. Create reports with hierarchical section navigation. (See the picture further below.)
1. Customize, hide, or suppress the Crystal Reports viewer toolbar. e.g. Suppress the refresh button or limit export options.
1. Add an auto-refresh capability for dashboard reports.
1. Develop reports which can create an email utilizing report data.
1. Prevent drill-down on group-level objects and subreports.
<br>

![wepic](/webelements/admin/weembcontn.png)

### webElements Has the Following Advantages:

1. It’s free and open source.
1. No additional web pages are required…only the .rpt file.
2. Existing reports do not need to be altered. A "wrapper" report can be created to interact with reports in an iFrame.
1. No additional personnel are required…just an expert report developer.
1. No additional tools (i.e. software packages) are required.
1. No HTML programming knowledge is required.
2. Can be customized by expert report developers familiar with Custom Functions.
<br>

![wepic](/webelements/admin/weemail.png)

### webElements 4.3 vs Older Versions:

1. Can use an HTTP post, instead of OpenDocument reporting, for much faster performance. Note that this is experimental / beta.
2. Can have multiple independent 'forms' on each report.
3. Has an option to create e-mails based on report data.
4. Has new functions including a multi-select sortable table control with values based on report data.
5. Has more options to customize the viewer, including limiting export options.

Please see the sample reports for examples of the above.

![wepic](/webelements/admin/weupdate.png)

## Notes

1. This is currently an early release / test version for CR 2020 & SAP BI 4.3 and the last update is April 24 2024.  
1. Please thoroughly test on a development environment before adding to any production reports.
1. The recommended experience level is expert report developer.
1. [The latest version of webElements can be downloaded here, including some samples.](https://github.com/jwisemanca/biReports/raw/master/webelements/webElements433Release240424.zip)
1. Pass-through HTML needs to be activated in the SAP BI / BOBJ Enterprise environment. The steps to do this are [here](/webelements/admin/passthroughhtml.md).
1. A User Guide (which is being updated) is available [here.](/webelements/webElements%20User%20Guide%20433.pdf)
2. See the [Getting Started section here](https://github.com/jwisemanca/biReports/blob/master/webelements/admin/GettingStarted.md). 
<br>

<b>Need help?</b> Connect with me, [Jamie Wiseman, on LinkedIn](https://www.linkedin.com/in/jamie-wiseman-41bb769b).
<br>
<br>

![wepic](/webelements/admin/wem231015.png)
<br><br>
<b>Looking for an older version?</b> The last version (for BI 4.1) from the SAP HANA Academy is [here.](https://github.com/saphanaacademy/biReports/tree/master/webelements) This version should also work with 4.2 but has not been tested extensively.

![wepic](/webelements/admin/db.jpg)
