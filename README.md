# SimpleMongoToSql


A simple tool to get your Mongo Collections into a sql database.

Basically this tool works like this:

1) export mongo database to json using mongo tools programatically getting executed 
2) convert the json to xml
3) make an xsd to describe your data
4) use SSIS to transform the xml data into a Sql destination


The C# console project handles items 1 - 3.

Included is 

sample mongo database
visual studio project  MongoToXML
SSIS project to consume the xml files
shell of a sql server database

