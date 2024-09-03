


Business Process 

Customers contacts the shop for Lodging and Catering services,or other purposes that is not part of the bussiness process or an unexpected variable.


::: mermaid
graph TD;
    customer-contact[Customer places order]-->catering[catering];
    customer-contact-->lodging[lodging];
    customer-contact-->cater-and-lodge[catering and lodging];
    customer-contact-->unexpected-variables[others];
    catering-->1-catering-process[specify details]
    1-catering-process-->2-catering-process[Date and Time] 
    2-catering-process-->3-catering-process[Order Quantity and Items]
    3-catering-process-->4-catering-process[Quantity of Customers]
    4-catering-process-->5-catering-process[others]
    lodging-->1-lodging-process[Check Availability of rooms]
    1-lodging-process-->2-lodging-process[Reserve Quantity of Rooms]
    2-lodging-process-->3-lodging-process[Specify date,time, and duration of lodging]

:::