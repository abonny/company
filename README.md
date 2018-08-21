# Company

Training App

Logback had a file appender and no console appender
Tried to connect to non-existant mysql database
Had to delete src/main/java/io/rscale/training/company/DataSourceConfig.java

Had to create a mysql instance and bind to app
cf set-env company SPRING_PROFILES_ACTIVE dev
