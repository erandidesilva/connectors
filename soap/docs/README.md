# Soap Connector

This is the Soap connector for ballerina And the action is being invoked in a ballerina main function.
In the main function we have the salesforce soap api login and get the response body and from that can
extract the sessionId.

## send
   The send action helps to Get the Soap Body from a soap Envelope.

###### Prerequisites

1. Create a salesforce account by visiting [Salesforce](https://developer.salesforce.com/)
2. Obtain the following parameters:
    * Username.
    * Password.
    * Security Token(You will get this to your registered email address when you create a developer
    account in salesforce)

**IMPORTANT:** This password and security token can be used to make API requests on your own account's behalf.
Do not share those with anyone.

###### Invoke the actions
- Place the soap directory into {BALLERINA_HOME}/samples.
- To run the following commands to execute the relevant action.

  1. send:
  `bin$ ./ballerina run ../samples/soap/src/soapConnector.bal <username> <password+securityToken>`