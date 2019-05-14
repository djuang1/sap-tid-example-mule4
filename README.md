# SAP Transaction ID example for Mule 4.x

This is an example project showing how to leverage the TID within a Mule project. A TID is needed for tracking and monitoring transactions that are sent to SAP. If you want to find out the status of an IDOC submitted to SAP, you can search for the TID and get back the IDOC number. The out-of-the-box function, INBOUND_IDOCS_FOR_TID, allows you to easily query for the IDOC number by passing in the TID 
