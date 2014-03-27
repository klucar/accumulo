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

Test Concurrent Read/Write
==========================

Can run this test with pre-existing splits; use the following command to create the table with
100 pre-existing splits:

> `$ hadoop jar ../../../lib/accumulo.jar \   
'org.apache.accumulo.server.test.TestIngest$CreateTable' 0 5000000 100`
