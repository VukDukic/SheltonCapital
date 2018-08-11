# Shelton Capital

## Tasks

### Weekly Sales Activity
#### Resources
* http://www.dmzinteractive.com/blog/10-must-have-sales-management-reports-your-salesforcecom-dashboard
* https://www.adminhero.com/the-hidden-functionality-of-custom-report-types
* https://na59.salesforce.com/00Of4000001GME6/e?retURL=%2F00Of4000001GME6
* https://success.salesforce.com/answers?id=90630000000h2d1AAA
* https://trailhead.salesforce.com/modules/reports_dashboards/units/reports_dashboards_getting_started

## Notes
### 12 January 2018
* 3 territories (East, West, Central)
* Dashboards: Territory + Activity = Activity Dashboard
* Week, Month, Quarter, Year
* add it to the Home page
* email the reports
* Solera, separate account = Advent
* grab data from Advent and populate Salesforce

#### 5 Sales Professionals:
* Ryan Groves, Bill Barnes, Chad Wickliffe, Paul Schemel, and Jeff Medina

* Number of

                                                               i.      Calls made

                                                             ii.      Emails sent

                                                           iii.      In Person Meetings

                                                           iv.      In person meeting w/PM

                                                             v.      Sales Presentation

                                                           vi.      Sales Presentation w/PM

                                                          vii.      Webinars

 

* One bar chart for each activity.  7 reports.

* a monthly summary report by sales person with all 7 activities on each monthly summary report.
#
In our SMA Object only
Create a solution to identify and separate Wells Fargo advisors (any email with wellsfargoadvisors.com and wfadvisors.com) from our results because our reps do not receive credit for Wells Fargo
In our SMA Object only, create a report/dash
Be able to adjust time periods (Time periods include: weekly, quarterly, YTD, in totality from the beginning of time; YoY; PoP (period over period whether that be WoW or MoM)) for the following.

Report on SMA totals by product/strategy (5 total products/strategies)
Further segment/view by territory
Report on SMA percent of total by product/strategy
Further segment/view by territory
Report on Advisors’ SMA total by product
Further segment by territory
Report SMA Advisors’ percentage of overall product total
Rollups (as a firm, then broken down by advisor and this feature is already developed, but needs to be deployed)
                                                               i.      RB

                                                             ii.      Mercer

                                                           iii.      LPL Financial

                                                           iv.      Raymond James

                                                             v.      Wells Fargo


/services/data/v43.0/query
/services/data/v43.0/query?q=SELECT+Id+,+EventType+,+LogDate+,+LogFileLength+,+LogFile+FROM+EventLogFile+ WHERE+EventType+=+'ReportExport'

