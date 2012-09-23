Gradebook Audit Report
------------------------

The Audit Report is a customisation of the standard Grader report but also contains a grade history report, based on the Ad-hoc Database Queries report from the Open University.

HOW TO INSTALL
--------------

1. Download all files and copy them into a folder called 'audit' in your Moodle's ./grade/report folder.
2. Copy audit.gif to your theme's ./pix/t folder.
3. From the Settings block, select on Site administration->Notifications to complete the installation.

The Audit report and grade edit pages will need to be styled. Here is some basic styling, which you can add to your theme's 'grade.css' file:

.path-grade-report-audit table#user-grades td.cell span.gradepass {background-color: #C2EBBD;}
.path-grade-report-audit table#user-grades td.cell span.gradefail {background-color: #EBC4BD;}
.path-grade-report-audit table#user-grades td.clickable {cursor: pointer;}
.path-grade-report-audit .auditreportoverlay {background-color:#EEEEEE;border:1px solid black;padding:10px;}
.path-grade-report-audit form {text-align: left;}
.path-grade-report-audit .moving {background-color: #E8EEF7;}
.path-grade-report-audit .gradetreebox {width:70%;padding-bottom:15px;}
.path-grade-report .buttons {text-align:center;}
.path-grade-report-audit .idnumber {margin-left: 15px;}
.path-grade-report-audit .movetarget {position: relative;width: 80px;height: 16px;}
.path-grade-report-audit ul#grade_tree {width: auto;}
.path-grade-report-audit ul#grade_tree li {list-style: none;}
.path-grade-report-audit ul#grade_tree li.category {margin-bottom: 6px;}
.path-grade-report-audit .iconsmall {margin-left: 4px;}