# agent-js-jasmine
Agent for integration Jasmine + Protractor with ReportPortal.     
[ReportPortal](http://reportportal.io/)<br>
[ReportPortal on GitHub](https://github.com/reportportal)

### How to use<br>
1. Clone repository with agent using <br>```git clone```<br><br>
2. Install dependencies <br>```npm install```<br><br>
3. Put your tests in the root folder.<br><br>
4. Open conf.example.js and make changes:<br>
* Input your ```token```. You can find it in your ReportPortal profile.
* Input ```YOUR PROJECT NAME```, ```YOUR LAUNCH NAME```.
* Input path to your tests  ```specs: ['spec.js']```
5. Run tests  ```protractor conf.example.js```
6. Open ReportPortal, your project and launch. You should see report about tests results.


		
