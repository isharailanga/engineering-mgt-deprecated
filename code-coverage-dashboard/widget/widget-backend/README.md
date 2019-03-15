# code-coverage-widget-backend

This is to generate an backend service which will act as the backend of the Code coverage dashboard widget. 

The widget will call the endpoints mentioned in this service and the service is responsible for database operations.

To build the widget-backend service run below command from 
engineering-mgt/code-coverage-dashboard/widget/**widget-backend**
```
mvn clean install
```
Place the resulted target/**Code-Coverage-Service-1.0.0.jar** in <SP_HOME>/libs
