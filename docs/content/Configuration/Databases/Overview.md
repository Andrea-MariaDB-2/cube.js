---
title: Connecting to the Databasesss
permalink: /config/databases/overview
category: Configuration
menuOrder: 1
---

Choose a platform to get started with below:

<!-- prettier-ignore-start -->
[[info | ]]
| If you'd like to connect to a database which is not yet supported,
| you can create a Cube.js-compliant driver package.
| [Here's a simple step-by-step guide][gh-cubejs-driver-guide].
<!-- prettier-ignore-end -->

<div class="gettingStartedGrid">
  <div class="ant-row">
    <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
      <a href="postgres">
        <div class="gettingStartedItemContent">
          <div class="gettingStartedItemImage">
            <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/postgres.svg" alt="Postgres" />
          </div>
          <div class="gettingStartedItemLink">Postgres</div>
        </div>
      </a>
    </div>
    <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
      <div class="gettingStartedItemContent">
        <a href="mysql">
          <div class="gettingStartedItemImage">
            <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/mysql.svg" alt="MySQL" />
          </div>
          <div class="gettingStartedItemLink">MySQL</div>
        </a>
      </div>
    </div>
    <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
      <div class="gettingStartedItemContent">
        <a href="aws-redshift">
          <div class="gettingStartedItemImage">
            <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/redshift.svg" alt="AWS Redshift" />
          </div>
          <div class="gettingStartedItemLink">AWS Redshift</div>
        </a>
      </div>
    </div>
    <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
      <a href="clickhouse">
        <div class="gettingStartedItemContent">
          <div class="gettingStartedItemImage">
            <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/clickhouse.svg" alt="ClickHouse" />
          </div>
          <div class="gettingStartedItemLink">ClickHouse</div>
        </div>
      </a>
    </div>
    <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
      <div class="gettingStartedItemContent">
        <a href="hive-sparksql">
          <div class="gettingStartedItemImage">
            <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/hive.svg" alt="Hive/SparkSQL" />
          </div>
          <div class="gettingStartedItemLink">Hive/SparkSQL</div>
        </a>
      </div>
    </div>
    <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
      <div class="gettingStartedItemContent">
        <a href="oracle">
          <div class="gettingStartedItemImage">
            <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/oracle.svg" alt="Oracle" />
          </div>
          <div class="gettingStartedItemLink">Oracle</div>
        </a>
      </div>
    </div>
  </div>
  <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
    <a href="mssql">
      <div class="gettingStartedItemContent">
        <div class="gettingStartedItemImage">
          <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/mssql.svg" alt="MS SQL" />
        </div>
        <div class="gettingStartedItemLink">MS SQL</div>
      </div>
    </a>
  </div>
  <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
    <div class="gettingStartedItemContent">
      <a href="aws-athena">
        <div class="gettingStartedItemImage">
          <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/athena.svg" alt="AWS Athena" />
        </div>
        <div class="gettingStartedItemLink">AWS Athena</div>
      </a>
    </div>
  </div>
  <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
    <div class="gettingStartedItemContent">
      <a href="google-bigquery">
        <div class="gettingStartedItemImage">
          <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/bigquery.svg" alt="Google BigQuery" />
        </div>
        <div class="gettingStartedItemLink">Google BigQuery</div>
      </a>
    </div>
  </div>
<div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
    <a href="mongodb">
      <div class="gettingStartedItemContent">
        <div class="gettingStartedItemImage">
          <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/mongodb.svg" alt="MongoDB" />
        </div>
        <div class="gettingStartedItemLink">MongoDB</div>
      </div>
    </a>
  </div>
  <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
    <div class="gettingStartedItemContent">
      <a href="snowflake">
        <div class="gettingStartedItemImage">
          <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/snowflake.svg" alt="Snowflake" />
        </div>
        <div class="gettingStartedItemLink">Snowflake</div>
      </a>
    </div>
  </div>
  <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
    <div class="gettingStartedItemContent">
      <a href="presto">
        <div class="gettingStartedItemImage">
          <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/presto.svg" alt="Presto" />
        </div>
        <div class="gettingStartedItemLink">Presto</div>
      </a>
    </div>
  </div>
  <div class="gettingStartedItem originalWidth ant-col ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-xl-8">
    <div class="gettingStartedItemContent">
      <a href="druid">
        <div class="gettingStartedItemImage">
          <img src="https://raw.githubusercontent.com/cube-js/cube.js/master/packages/cubejs-playground/src/img/db/druid.svg" alt="Druid" />
        </div>
        <div class="gettingStartedItemLink">Druid</div>
      </a>
    </div>
  </div>
</div>

[gh-cubejs-driver-guide]:
  https://github.com/cube-js/cube.js/blob/master/CONTRIBUTING.md#implementing-driver
