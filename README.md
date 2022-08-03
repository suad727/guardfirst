# guardfirst
A Call Center with Amazon Connect

The Data Streaming CloudFormation Template accelerates the creation of the data streams of call log data to query in Athena and visualize in QuickSight. 

The Lambda Function Package generates the http content, dashboard list and dashboard & session embed urls for our portal page.
It initially returns HTML content with javascript function that makes an API Gateway calls to get dashboard list and embed urls.
