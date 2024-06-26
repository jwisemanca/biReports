<table width=100% border=0>
<tr ><td colspan=2><h1>webElements</h1></td></tr>
<tr><td>&nbsp;A Custom Function Library for Crystal Reports</td></tr>
</table>

## Getting Started

### Simplified Development Process:

1. Pass-through HTML is activated on the server where you want to run the customized reports.
1. The Custom Functions are installed into the CR Server or BusinessObjects Repository using the webElements433 master sample report. There are further instructions included on this report.
1. The library is then installed from the CR Server or BusinessObjects Repository onto a development report. There are further instructions included on the webElements433 master report.
1. Sample formulas for the individual controls can be copied from the webElements433 master sample report onto the new development report to be customized. Most formulas on the master report have descriptions on the functions.
1. A formula for a submit method (e.g. a button or link) to a named target report is copied to the development report.
1. A "builder" formula is added to the development report which ties in all of the controls and builds the necessary code. See the "weBuilder" formulas on the master report.
1. The development report is saved to the server environment to be tested in the DHTML viewer.

### Installation and Usage of the Sample Reports

1. Pass-through HTML needs to be activated in the SAP BI / BOBJ Enterprise environment. The steps to do this are [here](/webelements/admin/passthroughhtml.md).
1. [Go to the main webElements ReadMe page to download the sample reports file.](https://github.com/jwisemanca/biReports/edit/master/webelements/readme.md)
2. Add all of the sample reports to a development folder in your CR Server or BusinessObjects system.
3. Open the CR Server or BusinessObjects Launchpad and navigate to the new sample reports folder.
4. Open the "webElements Jump Page" report. If you are using the Fiori viewer click on the lime-green link to open in the DHTML viewer.
5. Open any of the sample reports using the jump page links.

![wepic](/webelements/admin/wesrjp2.png)

