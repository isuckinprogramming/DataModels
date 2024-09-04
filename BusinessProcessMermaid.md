


Business Process 

Customers contacts the shop for Lodging and Catering services,or other purposes that is not part of the bussiness process or an unexpected variable.


::: mermaid
graph TD;
    customer-contact-->lodging[lodging];
    customer-contact-->unexpected-variables[others];
    lodging-->1-lodging-process[Check Availability of rooms]
    1-lodging-process-->2-lodging-process[Reserve Quantity of Rooms]
    2-lodging-process-->3-lodging-process[Specify date,time,contact number, and duration of lodging]
    3-lodging-process --> |Avail| 4-lodging-process[Catering Services]
    3-lodging-process --> |Do not Avail| 5-lodging-process[Payment]
    4-lodging-process --> 5-lodging-process
    5-lodging-process --> 6-lodging-process[Online Payment Options]
    5-lodging-process --> 7-lodging-process[Cash]
    6-lodging-process --> 8-lodging-process[G Cash]
    6-lodging-process --> 9-lodging-process[PayMaya]
    6-lodging-process --> 10-lodging-process[Other Options]
:::

Not sure if payment happens before or after the purchase process is finish. 