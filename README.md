Siddhi-store-redis
======================================

The **siddhi-store-redis extension** is an extension for siddhi redis event table implementation. This extension can be 
used to persist events to a
redis cloud instance of version 4.x.x.

Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-store-redis">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-store-redis/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-store-redis/issues">Issue tracker</a>

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://wso2-extensions.github.io/siddhi-store-redis/api/1.0.9">1.0.9</a>.

## Prerequisites
 
Redis Server instance should be started and ready to connect via redis java API.

## How to use 

**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension in the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support. 
* This extension can be used to connect into Redis cluster or a single redis node(Tested on Redis 5.0).
* This extension is shipped by default with WSO2 Stream Processor, if you wish to use an alternative version of this 
extension you can replace the component <a target="_blank" href="https://github
.com/wso2-extensions/siddhi-store-redis/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` 
directory.
* This extension depends on Jedis, redis client. Please download redis client jar (2.9.0) and place in `<STREAM_PROCESSOR_HOME>/lib` directory.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency along with other Siddhi dependencies to your project.

```
     <dependency>
        <groupId>org.wso2.extension.siddhi.store.redis</groupId>
        <artifactId>siddhi-store-redis</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ | 
| master  | [![Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-store-redis/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-store-redis/) |

---

## Features

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-store-redis/api/1.0.9/#redis-store">redis</a> *<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#store">(Store)</a>*<br><div style="padding-left: 1em;"><p>This extension assigns data source and connection instructions to event tables. It also implements read write operations on connected datasource</p></div>

## How to Contribute
 
  * Please report issues at <a target="_blank" href="https://github
  .com/wso2-extensions/siddhi-store-redis/issues">GitHub
   Issue Tracker</a>.
  
  * Send your contributions as pull requests to <a target="_blank" href="https://github
  .com/wso2-extensions/siddhi-store-redis/tree/master">master branch</a>. 
 
## Contact us 

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>. 
 
 * Siddhi developers can be contacted via the mailing lists:
 
    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)
    
    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)
 
## Support 

* We are committed to ensuring support for this extension in production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology. 

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>. 
