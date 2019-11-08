Guide: 

http://guides.grails.org/grails-file-download-excel/guide/index.html

How to run tests:

./gradlew -Dgeb.env=chrome -Ddownload.folder=/Users/sdelamo/Downloads integrationTest

Dependencies:

* [Spreadsheet builder](http://spreadsheet.dsl.builders) [Github](https://github.com/dsl-builders/spreadsheet), [MVNrepository](https://mvnrepository.com/artifact/builders.dsl/spreadsheet-builder-poi)
* [Asset Pipeline](http://www.asset-pipeline.com)[Github](https://github.com/bertramdev/asset-pipeline), [MVNrepository](https://mvnrepository.com/artifact/com.bertramlabs.plugins/asset-pipeline-core)

It also configures Selenium versions with Chrome and Gecko:

http://chromedriver.chromium.org

https://github.com/mozilla/geckodriver/releases