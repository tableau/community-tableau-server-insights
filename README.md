TS Background Tasks# Tableau Server Insights

[![Community Supported](https://img.shields.io/badge/Support%20Level-Community%20Supported-457387.svg)](https://www.tableau.com/support-levels-it-and-developer-tools)


## What is this?

Getting real, useful data out of Tableau Server is difficult-more difficult than it should be. The PostgreSQL repository database that powers Server is a maze of confusing tables and cryptic, often incomplete, data. Using these data sources, the hard work of learning the underlying table structures and assembling a coherent data set that can answer real questions has been done for you. Point these at your Tableau Server repository database, and you can jump right into asking questions!

## Setup and Running Samples

### Prerequisites

* Using these data sources requires that you have already [opened up access](https://help.tableau.com/current/server/en-us/perf_collect_server_repo.htm) to your PostgreSQL repository.
* You must have the appropriate version of Tableau Desktop to open these files, according to the compatibility chart below.

### Compatibility

Use this chart to determine what version of each data source you need, based on the version of Tableau Server that you are running. Click the link to go to the appropriate .twb file.

<table border=0 cellpadding=0 cellspacing=0 width=1033980 style='border-collapse:
 collapse;table-layout:fixed;width:775485pt'>
 <col width=148 style='mso-width-source:userset;mso-width-alt:5412;width:111pt'>
 <col width=68 span=10 style='mso-width-source:userset;mso-width-alt:2486;
 width:51pt'>
 <col width=64 span=16143 style='width:48pt'>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl66 width=148 style='height:15.0pt;width:111pt'></td>
  <td class=xl67 width=150 style='width:51pt'>10.2 - 2018.3</td>
  <td class=xl67 width=150 style='width:51pt'>2019.1 - 2020.3</td>
  <td class=xl67 width=150 style='width:51pt'>2020.4+</td>
 </tr>
 
<tr height=20 style='height:15.0pt'>
  <td height=20 class=xl66 style='height:15.0pt'>ts_background_tasks</td>
  <td class=xl68><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_background_tasks/ts_background_tasks_01.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>01.02</span></a></td>
  <td class=xl68><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_background_tasks/ts_background_tasks_02.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>02.02</span></a></td>
  <td class=xl68><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_background_tasks/ts_background_tasks_03.01.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>03.01</span></a></td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl66 style='height:15.0pt'>ts_content</td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_content/ts_content_01.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>01.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_content/ts_content_02.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>02.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_content/ts_content_03.01.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>03.01</span></a></td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl66 style='height:15.0pt'>ts_data_connections</td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_data_connections/ts_data_connections_01.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>01.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_data_connections/ts_data_connections_02.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>02.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_data_connections/ts_data_connections_03.01.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>03.01</span></a></td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl66 style='height:15.0pt'>ts_events</td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_events/ts_events_01.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>01.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_events/ts_events_02.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>02.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_events/ts_events_03.01.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>03.01</span></a></td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl66 style='height:15.0pt'>ts_users</td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_users/ts_users_01.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>01.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_users/ts_users_02.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>02.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_users/ts_users_03.01.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>03.01</span></a></td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl66 style='height:15.0pt'>ts_web_requests</td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_web_requests/ts_web_requests_01.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>01.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_web_requests/ts_web_requests_02.02.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>02.02</span></a></td>
  <td class=xl68 style='border-top:none'><a
  href="https://raw.githubusercontent.com/tableau/community-tableau-server-insights/master/datasources/ts_web_requests/ts_web_requests_03.01.twb"
  target="_parent"><span style='font-family:Arial, sans-serif;mso-font-charset:
  0'>03.01</span></a></td>
 </tr>
 <![endif]>
</table>


### Open in Tableau Desktop

1. Open a version of Tableau Desktop compatible with the version you wish to use. You should pick the highest file version possible, while still being lower than your Tableau Server version.

2. Set the Tableau Server parameter for the name of your Tableau Server instance. This is used to build hyperlinks for use in URL actions.

3. Set the Timezone parameter for your local time. This is used to set date time fields with the (local) suffix to your local time (all other times are in UCT).

4. Extract the data, if you wish. Here are recommendations for whether and how each data source should be extracted:

|    Data   Source          |    Extract                                 |    Retention                               |
|---------------------------|--------------------------------------------|--------------------------------------------|
|    TS Content             |    Full Extract                            |    All items that currently exist       |
|    TS Events              |    Incremental Extract (on Event Id field) |    180 days, but configurable using **wgserver.audit_history_expiration_days** |
|    TS Background Tasks    |    Live / Incremental Extract (On Increment Date field)                                   |    30 days, but configurable using **purge.jobs.retention_days** |
|    TS Users               |    Full Extract                            |    All users that currently exist   |
|    TS Web Requests        |    Incremental Extract (on Id field)       |    7 days, but configurable using **tsm maintenance cleanup --http-requests-table-retention**   |
|    TS Data Connections    |    Live                                    |    All data connections that currently exist   |

5. If row-level security is required, edit the User Filter calculation as appropriate, and add the field to a data source filter for the value of "true".

### Publish to Tableau Server

1. Publish your data source to Tableau Server by right-clicking it in the Data pane, and selecting "Publish to Server".

2. Set the permissions as appropriate. If you intend the data to be seen by admins-only, you will want to restrict permissions. If you've set up row-level security with the idea to share it with your users, you should allow View and Connect rights.

3. Ensure that the Authentication type is set to embedded password.

4. Add a description for the data source.

5. If you've extracted the data, pick a schedule on which it will be refreshed.

6. Click Publish. Now your data about Tableau Server is also hosted on Tableau Server! How meta. Go start asking questions, champ.

## Contributions

Submissions are cool! To contribute, first sign our CLA that can be found [here](https://tableau.github.io/contributing.html). To submit a contribution, please fork the repository then submit a pull request to the `submissions` branch. We will run through standard tests, but expect you be mindful of performance impacts or cardinality changes that may be introduced.

## Code Style

We have standards, for sure. At some point we'll probably even document them. In the meantime, try to follow some of the conventions used elsewhere in these data sources.

## Documentation

Documentation for these data sources exists in the first page of the workbook they are a part of. Fields are documented with comments.

## Issues

Feel free to ask questions or let us know of problems you see to one of these three places:

1. The [Tableau Community site](https://community.tableau.com/community/forums/server-administration)
2. Create an [Issue](https://github.com/tableau/community-tableau-server-insights/issues) here on GitHub
3. Join us on Tableau's [DataDev](https://tableau-datadev.slack.com/archives/C016Y0C85GU) Slack workspace
