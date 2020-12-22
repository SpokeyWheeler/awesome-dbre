# Awesome DBRE
A curated list of awesome free and open-source tools for and knowledge about database reliability engineering

## Automation



## Version Control for Databases (AKA Schema Migration)

[activerecord migrations](https://guides.rubyonrails.org/active_record_migrations.html) ruby on rails (Open Source) 

[db](https://github.com/infostreams/db) (Open Source, mysql)

[dbdeploy](http://dbdeploy.com/software/) (Open Source)

[diffkit](http://www.diffkit.org/) (Open Source, jdbc)

[flyway](https://flywaydb.org/) (Open Source, jdbc)

[liquibase](http://www.liquibase.org/) (Open Source, jdbc)

[mybatis](http://mybatis.org/migrations/index.html) (Open Source, jdbc)

[sqitch](https://sqitch.org/) platform agnostic, no orm, no framework! (Open Source)

## Anonymisation

[anonimatron](https://realrolfje.github.io/anonimatron/) (Open Source, jdbc)

[anonymize-it](https://github.com/elastic/anonymize-it) supports faker (Open Source, elasticsearch)

[arx](https://arx.deidentifier.org/) (Open Source, file, csv)

[data anonymization](http://sunitparekh.github.io/data-anonymization/#) (Open Source, activerecord)

[fogger](https://github.com/TheSoftwareHouse/fogger) supports faker (Open Source, pecl)

[jailer](https://github.com/Wisser/Jailer) data subsetting (Open Source, jdbc)

## Monitoring

[cortex](https://github.com/cortexproject/cortex) clustered prometheus (Open Source)

[grafana](https://grafana.com/) dashboards and graphing (Open Source)

[graphite](https://graphiteapp.org/) time series database for metrics with graphing (Open Source)

[icinga](https://icinga.com/) push monitoring (Open Source)

[influxdb](https://www.influxdata.com/) time series database for metrics (Open Source)

[metrictank](https://github.com/grafana/metrictank) clustered graphite (Open Source)

[netdata](https://www.netdata.cloud/) out of the box monitoring and storage of hundreds of high resolution metrics 😍 (Open Source)

[prometheus](https://prometheus.io/) pull monitoring time series database for metrics (Open Source)

[timescaledb](https://www.timescale.com/) postgresql backend for time series data (Open Source)

[zabbix](https://www.zabbix.com/) push monitoring (Open Source)

## Logging

[elk](https://www.elastic.co/) elasticsearch, logstash, kibana (Open Source)

[fluentd](https://www.fluentd.org/) (Open Source)

[graylog](https://www.graylog.org/) (Open Source)

[logalyze](http://www.logalyze.com/) security-focused log analysis (Free)

[loki](https://github.com/grafana/loki) logging using Prometheus-like tagging model (Open Source)

[nxlog](https://nxlog.co/products/nxlog-community-edition) (Open Source)

[pgbadger](http://pgbadger.darold.net/) high-speed postgresql log analysis

[pgcluu](http://pgcluu.darold.net/) postgresql cluster utilization

## Testing

[dbunit](http://www.dbunit.org/) set a database to a known state for testing (Open Source, jdbc)

[dbfit](http://dbfit.github.io/dbfit/index.html) unit tests for databases using the Fitnesse framework (Open Source, jdbc, .net)

[dbbench](https://github.com/sj14/dbbench) simple load testing using scripts (Open Source, go)

[faker](https://github.com/joke2k/faker) generate fake data (Open Source, python)

[inspec](https://www.inspec.io/) compliance testing (Open Source, ruby)

[supermarket](https://supermarket.chef.io/tools?type=compliance_profile) pre-built inspec profiles (Open Source)

## Security

[devsec](https://github.com/dev-sec) hardening framework (Open Source)

[logalyze](http://www.logalyze.com/) security-focused log analysis (Free)

[ossim](https://cybersecurity.att.com/products/ossim) SIEM (Open Source)

[otx](https://cybersecurity.att.com/open-threat-exchange) open threat exchange (Open Source)

## SQL Clients

[dbeaver](https://dbeaver.io/) (Open Source, java)

[dbvis](https://www.dbvis.com/) (Free, java)

[omnidb](https://omnidb.org/en/) (Open Source, java)

[sql workbench/j](http://www.sql-workbench.eu/) (Open Source, java)

[squirrelsql](http://www.squirrelsql.org/) (Open Source, java)

## ORM / REST

[gorm](https://gorm.io/) ORM (Open Source, go)

[hibernate](https://hibernate.org/orm/) ORM (Open Source, java)

[prisma](https://www.prisma.io/) ORM (Open Source, javascript)

[sandman2](https://github.com/jeffknupp/sandman2) zero-code REST API for any database 😱 (Open Source)

[sequel](https://github.com/jeremyevans/sequel) ORM (Open Source, ruby)

[sqlalchemy](https://www.sqlalchemy.org/) ORM (Open Source, python)

## Management Utilities

[percona toolkit](https://www.percona.com/software/database-tools/percona-toolkit) (Open Source, mysql, mongodb)

[don't do these things in postgresql](https://www.depesz.com/2020/01/28/dont-do-these-things-in-postgresql/) (Open Source, postgresql)

[autodoc](https://github.com/cbbrowne/autodoc) schema documenter (Open Source, postgresql)

## Articles, Posts, and E-books

[The Google SRE Book](https://landing.google.com/sre/sre-book/toc/)

[The DBRE Book](https://books.google.ie/books?id=L4o7DwAAQBAJ&printsec=frontcover&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false)

[An introduction to database reliability engineering](https://softwareengineeringdaily.com/2018/10/16/an-introduction-to-database-reliability/)

[Laine Campbell's Velocity 2016 conference slides](http://velocity.oreilly.com.cn/2016/ppts/DatabaseReliabilityEngineering.pdf)

[Criteo - How we went from just a bunch of engineers to data reliability engineering](https://labs.criteo.com/2018/06/from-just-a-bunch-of-engineers-to-data-reliability-engineering/)

[The Newbie DBA](https://newbiedba.wordpress.com/category/database-reliability-engineering/)

## Podcasts

[Database Reliability Engineering](https://softwareengineeringdaily.com/2018/06/20/database-reliability-engineering-with-laine-campbell/)

[Parse and Ops](https://softwareengineeringdaily.com/2017/03/01/parse-and-operations-with-charity-majors/)

## Videos

[Surge 2015: DBRE, Modernizing the DBA Role](https://www.youtube.com/watch?v=lsiI8AIzLrE)

[Kendra Little's Whiteboard on DBRE](https://littlekendra.com/2019/12/18/database-reliability-engineering-22-minute-video/)

[Database Chaos with Tammy Butow](https://softwareengineeringdaily.com/2018/04/10/database-chaos-with-tammy-butow/)

## Shameful Self-Promotion 😳

[What is your MVP?](https://medium.com/@william.wheeler_87363/dbre-what-is-your-mvp-fb8b5f79a19c)

[The monitoring of monitoring](https://medium.com/@william.wheeler_87363/dbre-the-monitoring-of-monitoring-be006788bf23)
