---
title: OrderStatusChangingNotification
description: API reference for OrderStatusChangingNotification in Umbraco Commerce
---
## OrderStatusChangingNotification

```csharp
public class OrderStatusChangingNotification : OrderStatusChangeNotificationBase<Order>
```

**Inheritance**

* Class [OrderStatusChangeNotificationBase&lt;TEntity&gt;](orderstatuschangenotificationbase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderStatusChangingNotification

```csharp
public OrderStatusChangingNotification(Order order, ChangingValue<Guid?> orderStatusId, 
    ChangingValue<OrderStatusCode> orderStatusCode)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->