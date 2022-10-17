# Developer Salary Guide

- Advanced logging via Solarwinds Papertrail cloud logging service: https://my.papertrailapp.com/systems/developersalaryguide/events
 The system logs created by this solution are also filterable, searchable, and retained for a time period which is appropriate for any technical support research to resolve a report should a user face any issues. 

- System Monitoring: The monitoring solution, Dead Man’s Snitch by Collective Idea, checks the status of the application each hour to ensure you are aware of any unplanned outages or cloud service failure. The monitor will trigger alerts to your support team until the application is back up and running with successful tests. 

- Hosted on a Free Dyno thanks to [Heroku](https://www.heroku.com/)  
  - **Note:** This app is deployed on a free Heroku dyno. Free dynos will sleep after a half hour of inactivity (if they don’t receive any traffic). This causes a delay of a few seconds for the first request upon waking. Subsequent requests will perform normally.
