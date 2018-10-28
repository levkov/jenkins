## Jenkins


Coralogix provides integration with Jenkins using Logstash, so you can send your logs from anywhere and parse them according to your needs.  

### Table of contents

1. Prerequisites
2. Usage
3. Installation
4. Configuration

### Prerequisites
Have Logstash installed, for more information on how to install: https://www.elastic.co/guide/en/logstash/current/installing-logstash.html

### Usage

**Private Key** – A unique ID which represents your company, this Id will be sent to your mail once you register to Coralogix.

**Application Name** – Used to separate your environment, e.g. SuperApp-test/SuperApp-prod.

**SubSystem Name** – Your application probably has multiple subsystems, for example: Backend servers, Middleware, Frontend servers etc. in order to help you examine the data you need, inserting the subsystem parameter is vital.

