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

# 本工程fork 自https://github.com/chiastic-security/phoenix-for-cloudera/tree/4.8-HBase-1.2-cdh5.8
因为官方没有提供 phoenix-4.8-HBase-1.2-cdh5.7.0版本，所以从大神的code 修改，获得phoenix-4.8-HBase-1.2-cdh5.7.0版本。

# 使用方法
直接phoenix-4.8-HBase-1.2-cdh5.7.0的分支clone 到本机，然后使用 mvn clean package -DskipTests 编译即可，看个人网络环境需要的时间不一样。

    mvn clean package -DskipTests
也可以直接在release版本中下载使用。  
如果需要或者有问题，请联系作者 fuwenjiang@163.com



