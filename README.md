<!--
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to You under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

![logo](http://phoenix.apache.org/images/logo.png)

<b>[Apache Phoenix](http://phoenix.apache.org/)</b> is a SQL skin over HBase delivered as a client-embedded JDBC driver targeting low latency queries over HBase data. Visit the Apache Phoenix website <b>[here](http://phoenix.apache.org/)</b>.

Copyright ©2014 [Apache Software Foundation](http://www.apache.org/). All Rights Reserved.

### update 2017-11-08 by suheng.cloud
* integrate phoenix on spark2.2 + cdh5.11.1
* work around https://issues.apache.org/jira/browse/PHOENIX-4056 & https://issues.apache.org/jira/browse/SPARK-21549
* use mvn clean install -DskipTests=true for dev
* use mvn clean deploy -DskipTests=true for prod
