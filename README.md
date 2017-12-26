# webUIAutoTest
1. webUI自动化测试用例demo。
2. 依赖的工具：
   selenide工具--该工具为selenium加一层封装，使测试人员更专注测试内容而不是元素定位和判断的代码实现；
   testng；
   maven。
3. 测试执行
   mvn -f pom.xml clean test  -DxmlFileName=testNG.xml；
   testNG.xml为配置文件，可以配置不同浏览器、不同用例；配置文件可以编写很多个，以适应多个执行端的需求

