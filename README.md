# NiFi Pastebin monitoring flow

This repository contains flow (<a href="https://github.com/data-hunters/nifi-pastebin-monitoring-flow/blob/main/Pastebin_Monitoring_Flow.xml" target="_blank">Pastebin_Monitoring_Flow.xml</a>) which was created for NiFi presentation purposes. Its main goal is to monitor newly added content on Pastebin.com and send notification on Slack when sample conditions are met. Step by step instruction - how to build it from scratch has been described in one of our articles: <a href="https://blog.datahunters.ai/2021/09/use-of-nifi-for-osint-automation-purposes-part-ii" target="_blank">Use of NiFi for OSINT automation purposes (part II)</a>.

## Importing flow
To import flow, you have to click on "Upload template" icon (toolbox on the left side), then click on magnifier to select file with the flow and finally "Upload" button.

![Toolbox with "Upload template" button](https://github.com/data-hunters/nifi-pastebin-monitoring-flow/blob/main/assets/upload_template.png?raw=true)

When it's uploaded, drag and drop "Template" icon:

![Template](https://github.com/data-hunters/nifi-pastebin-monitoring-flow/blob/main/assets/import_template.png?raw=true)

select "Pastebin monitoring flow" and click "Add" button.
Now, you should see the following flow:

![Pastebin monitoring flow](https://github.com/data-hunters/nifi-pastebin-monitoring-flow/blob/main/assets/imported_flow.png?raw=true)

As you can see, two processors (`PutSlack`) have warnings. You have to configure `Webhook URL` for each of them. If you don't know how, read "Slack notification" section in <a href="https://blog.datahunters.ai/2021/09/use-of-nifi-for-osint-automation-purposes-part-ii" target="_blank">our article</a>.
<br/>
<br/>

[![DataHunters](http://datahunters.ai/assets/images/logo_full_small.png)](http://datahunters.ai)
