Challenge
---------

Below is a small technical challenge to be submitted back to the recruitment team.

As we value your time, try not spend more than 2 hours on this task - even if you haven't finished simply submit what you have.

Please provide a small readme file detailing anything we may need to know.

Development
-----------

- Choose from any of the following languages: NodeJS, Java or Python. 
- You may use any frameworks you wish to meet the requirements

Task
----

We would like you to do the following:

- Take the 3 files located within the **input** folder and treat them as your data store - each one representing a separate DB table.
- Create an HTTP endpoint to return the desired output details in the **output.json** file.



Additional
----------

All done?  Have some time left?

We have the following new requirements:

- Update your HTTP endpoint (or add a new one) to accept a query parameter called **filter**
- The **filter** parameter can contain a comma separated list of field names and the output will only show those fields 
requested
- Note: dataItemID and dataTypeID are always returned.

E.g.

    ?filter=name,child   
    
would match the output shown in **additional.json**