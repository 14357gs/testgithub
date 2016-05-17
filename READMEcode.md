<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title></title>
    </head>
    <body>
        <h1>THIS IS A CUSTOMER PAGE.</h1>
	    <br />
	        <br />
		    ENTER CUSTOMER NAME:
		        <input type="text" ng-model="Cname"/>
			    <br />
			        <br />
				    ENTER CUSTOMER MOBILE:
				        <input type="text" ng-model="CMobile" />
					    <br />
					        <br />
						    <input type="button" value="Get Customer Details" ng-click="GetDetails()" />
						        <br />
        <br />
	Customer Address : {{Address}
	</body>
	</html>
