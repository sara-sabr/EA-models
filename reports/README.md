## EA-models/reports directory

The EA-models/reports directory contains the HTML code of the Archi-generated reports for CommonSandbox.archimate and ReleaseCandidate.archimate. The reports are rendered as GitHub Pages and only the content in master is viewable:
* [CommonSandbox Report]("https://sara-sabr.github.io/EA-models/reports/CommonSandbox Report/index.html");
* [ReleaseCandidate Report]('https://sara-sabr.github.io/EA-models/reports/CommonSandbox Report/index.html').

The workflow for regenerating of these reports is the same as for any other contribution:

* [branch off](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) from master before regenerating;
* always create a pull request, even if the assignee is yourself;

## Refreshing a report from Archi

Asuming that a new branched was checked out and the desired file was open, e.g. CommonSandbox.archimate:

  ![1. Go to File->Report->HTML](/Documents/Services/Projects/ESDC-EA-SAS/1_file_report_html.png)
  ![2. Select the directory of the report in your local working copy of the repo](/Documents/Services/Projects/ESDC-EA-SAS/2_go_to_reports_commonsandbox.png)
  ![3. Confirm your intentions](/Documents/Services/Projects/ESDC-EA-SAS/3_confirm_your_intentions_to_overwrite.png)

Commit, push, create pull request and merge as usual.
