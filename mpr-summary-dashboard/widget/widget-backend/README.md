This is to generate an intermediate service which will act as the backend of the MPR-Summary dashboard widget. 

The widget will call the endpoints mentioned in this service and the service is responsible for invoking appropriate endpoints from the Ballerina service.

To build the widget-backend intermediate service run below command from 
engineering-mgt/mpr-summary-dashboard/widget/**widget-backend**
```
mvn clean install
```
