# awesome-test-tool
- 收集和整理各种测试工具，自动化测试工具，自动化测试框架，觉得有帮助记得star下。
- 欢迎提交各类测试工具到本项目。


### 通用测试框架
- [JUnit](https://junit.org): 最著名的xUnit类的单元测试框架，但是不仅仅可以做单元测试。
- [TestNG](https://testng.org/): 更强大的Java测试框架，灵活可扩展，支持注解和多线程。
- [pytest](https://docs.pytest.org): 最强大的Python测试框架，可定制性高，插件丰富。
- [unittest](https://docs.python.org/3/library/unittest.html): Python官方内置的测试框架。
- [RobotFramework](https://robotframework.org/): 基于关键字驱动的测试框架，开源，易用。
- [Cucumber](https://cucumber.io/): 开源的BDD自动化测试框架，支持Ruby和Java
- [Behave](https://github.com/behave/behave): 基于Python的BDD自动化测试框架
- [Gauge](https://gauge.org/index.html): 轻量级的跨平台测试自动化工具，可以以业务语言编写测试用例。

### 用例生成
- [graphwalker](https://github.com/GraphWalker): 基于模型的测试用例生成框架
- [PICT](https://docs.microsoft.com/en-us/previous-versions/software-testing/cc150619(v=msdn.10)): 微软公司开发的pairwise testing的用例生成工具

### 用例和bug管理
- [TestLink](http://www.testlink.org/): 开源测试用例管理，测试计划，测试执行，测试报告。
- [ZenTao](https://www.zentao.net/): 禅道，国产开源工具，记录bug，用例管理，项目管理。
- [Redmine](http://www.redmine.org/): 用Ruby开发的基于web的项目管理软件
- [jira](https://www.atlassian.com/software/jira): 缺陷跟踪、客户服务、需求收集、流程审批、任务跟踪、项目跟踪和敏捷管理。

### 自动化工具
- [Selenium](https://www.seleniumhq.org/): 业界最有影响力的Web自动化测试工具。
- [Cypress](https://www.cypress.io/): 基于js的web自动化测试工具。
- [atalon](https://www.katalon.com/): API，Web，移动端的自动化测试工具。
- [Ranorex](https://www.ranorex.com/): 商业GUI自动化测试工具，支持桌面，Web，移动端。
- [QTP/UFT](https://en.wikipedia.org/wiki/HP_QuickTest_Professional) 商业GUI桌面，Web的自动化测试工具。
- [AutoIT](https://www.autoitscript.com/site/): 用类Basic脚本编写Windows桌面GUI自动化的工具。
- [Appium](http://appium.io/): 支持android和ios的移动端自动化测试工具.
- [STF](https://openstf.io/): STF(smartphone test farm) 移动设备管理工具，通过浏览器控制和管理移动设备。
- [Macaca](https://macacajs.github.io/zh/): 面向多端的自动化测试工具，由阿里巴巴开源。
- [Airtest](http://airtest.netease.com/): UI自动化测试工具，支持App和游戏，网易开源。
- [SoloPi](https://github.com/alipay/SoloPi): Soloπ是一个无线化、非侵入式的Android自动化工具，公测版拥有录制回放、性能测试、一机多控三项主要功能，能为测试开发人员节省宝贵时间。

### 性能测试
- [Apache Bench](http://httpd.apache.org/docs/2.4/programs/ab.html): HTTP性能测试工具
- [LoadRunner](https://ssl.www8.hp.com/sg/en/ad/load-runner/load-runner.html): HP的商业性能测试工具
- [JMeter](https://jmeter.apache.org/)：基于Java的性能测试工具，开源。
- [locust](https://www.locust.io/)：基于Python的性能测试工具
- [Tsung](http://tsung.erlang-projects.org/): 基于Erlang的性能测试工具，支持海量的并发，但是由于懂Erlang的人少，故业界用得也少。
- [Siege](https://www.joedog.org/): Siege是一个多线程HTTP负载测试和基准测试工具
- [wrk](https://github.com/wg/wrk): 一款现代HTTP基准测试工具。
- [htop](https://hisham.hm/htop/): 实时统计Linux系统资源占用率
- [iftop](https://en.wikipedia.org/wiki/Iftop): 实时统计Linux网络流量
- [nload](https://linux.die.net/man/1/nload): Linux网速实时监控
- [webpagetest](https://github.com/WPO-Foundation/webpagetest):测量和分析网页性能工具,支持开发者下载源文件搭建私人的内部测试站点
- [PageSpeed Insights](https://developers.google.cn/speed/pagespeed/insights/):专注于改进网页性能的开发者工具,google出品。

### 代码质量
- [jacoco](https://www.eclemma.org/jacoco/): 开源的Java代码覆盖率工具
- [SonarQube](https://www.sonarqube.org/): 代码质量和安全的扫描工具
- [CodePulse](http://code-pulse.com/): 实时代码覆盖率工具

### 网络工具
- [Fiddler](https://www.telerik.com/fiddler): Fiddler是一个HTTP调试抓包工具。它通过代理的方式获取程序http通讯的数据，可以用其检测网页和服务器的交互情况。
- [Tcpdump](https://linux.die.net/man/8/tcpdump)：网络抓包工具。
- [Wireshark](https://www.wireshark.org/)：有界面的网络包分析工具，支持Windows, Linux, Mac OS.
- [GoReplay](https://goreplay.org/): 网络监控工具，可以做流量回放，压力测试，流量分析
- [TcpCopy](https://github.com/session-replay-tools/tcpcopy): 流量回放工具。
- [Charles](https://www.charlesproxy.com/)：抓包，弱网模拟，接口测试。
- [TC](https://linux.die.net/man/8/tc) Linux上控制网络流量的工具
- [WANem](http://wanem.sourceforge.net/): 广域网网络模拟器
- [网络损伤模拟仪](): 硬件网络损伤仿真仪器，用于模拟广域网的各种弱网条件，例如丢包，延迟，低带宽等。

### 接口测试
- [Postman](https://www.getpostman.com/): Postman is the complete toolchain for API developers, used by more than 5 million developers and 30,000 companies worldwide.
- [SoapUI](https://www.soapui.org/): 最流行的API测试工具。
- [JMeter](https://jmeter.apache.org/): 工业级的压力测试工具，也有人拿它做接口测试
- [Fiddler](https://www.telerik.com/fiddler): 是一个HTTP调试抓包工具。它通过代理的方式获取程序http通讯的数据，可以用其检测网页和服务器的交互情况。
- [Hitchhiker](https://github.com/brookshi/Hitchhiker): 是一款开源的支持多人协作的 Restful Api 测试工具，支持自动化测试, 数据对比，压力测试，支持脚本定制请求，可以轻松部署到本地，和你的team成员一起协作测试Api。
- [Rest-Assured](https://github.com/rest-assured/rest-assured): 测试 RESTful Web Services 的 Java 类库
- [Pact](https://github.com/pact-foundation/pact-specification): 消费者驱动契约测试的一种实现，可以用来在消费者的代码里mock响应，在提供方的代码中验证交互。

### 测试报告
- [ExtentReports](http://extentreports.com/): 一个优雅，互动，灵活细致的测试报告框架。
- [Allure](http://allure.qatools.ru/): 测试报告框架
- [reportportal](): AI-powered Test Automation Dashboard
- [cucumber-reporting](https://github.com/damianszczepanik/cucumber-reporting): HTML reports for Cucumber
- [ReportNG](https://reportng.uncommons.org/): An HTML/XML Reporting Plug-in for TestNG

### Mock
- [Moco](https://github.com/dreamhead/moco): 基于Java的Mock开源框架
- [mockserver](https://github.com/jamesdbloom/mockserver): 基于Java的Mock开源框架，可以通过client或者restful API远程控制mockserver的返回。
- [Mockito](https://site.mockito.org/): 用于Java单元测试的Mock测试框架
- [PowerMock](https://github.com/powermock/powermock/): 基于Mockito扩展的Java单元测试Mock框架
- [Whistle](https://github.com/avwo/whistle/)：是基于 Node 实现的跨平台抓包调试代理工具，可以录制请求和响应，然后作为mock server回放。


### 流量回放
- [vm-sandbox-repeater](https://github.com/alibaba/jvm-sandbox-repeater): 阿里开源的基于JVM-Sandbox的流量录制回放工具，提供入口请求（HTTP/Dubbo/Java）流量回放、子调用（Java/Dubbo）返回值Mock能力。

### 测试库
