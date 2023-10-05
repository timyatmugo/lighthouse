# lighthouse
I have read Lighthouse and understand how Lighthouse could help a web project.

Setup and Run the demo

```
npm install
sh run.sh
```

## There are a few interesting projects listed in the lighthouse repo.
[https://github.com/GoogleChrome/lighthouse#related-projects](https://github.com/GoogleChrome/lighthouse#related-projects)

### [Lighthouse-Batch](https://github.com/mikestead/lighthouse-batch)
- Allow batch generation, helpful to work with cronjob tasks.
- Provide a summary report in JSON format, which we can use as API.
  - [Summary/API](https://timyatmugo.github.io/lighthouse/report/lighthouse/summary.json)
- Generate individual reports with different formats. (JSON, HTML)
  - [Report](https://timyatmugo.github.io/lighthouse/report/lighthouse/www_mugo_ca_.report.html)
  - [JSON](https://timyatmugo.github.io/lighthouse/report/lighthouse/www_mugo_ca_.report.json)


 
### [Lighthouse-CI](https://github.com/GoogleChrome/lighthouse-ci) 
- A dashboard of historical report scores
- Generate lighthouse report via CI. 
- We don't use CI, but we can probably use a script to trigger manually. 

## [Auto-lighthouse](https://github.com/TGiles/auto-lighthouse)
- a crawling version of the Lighthouse 

## An additional helpful feature of headless chromium
- Generate PDF, screenshot, etc. 
  Ref: [https://developer.chrome.com/blog/headless-chrome/#puppeteer](https://developer.chrome.com/blog/headless-chrome/#puppeteer)
- Automated frontend test. 
  Ref: [https://developer.chrome.com/blog/headless-chrome/#using-selenium-webdriver-and-chromedriver](https://developer.chrome.com/blog/headless-chrome/#using-selenium-webdriver-and-chromedriver)
