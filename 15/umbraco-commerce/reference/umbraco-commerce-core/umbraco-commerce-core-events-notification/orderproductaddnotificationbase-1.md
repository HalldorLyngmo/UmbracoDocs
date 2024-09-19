---
title: OrderProductAddNotificationBase<TEntity>
description: API reference for OrderProductAddNotificationBase<TEntity> in Umbraco Commerce
---
## OrderProductAddNotificationBase&lt;TEntity&gt;

```csharp
public abstract class OrderProductAddNotificationBase<TEntity> : OrderNotificationEventBase<TEntity>
    where TEntity : OrderReadOnly
```

**Inheritance**

* Class [OrderNotificationEventBase&lt;TOrder&gt;](ordernotificationeventbase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderProductAddNotificationBase&lt;TEntity&gt; (1 of 2)

```csharp
public OrderProductAddNotificationBase(TEntity order, string productReference, decimal qty, 
    IDictionary<string, string> properties, string bundleId, string parentBundleId)
```

---

#### OrderProductAddNotificationBase&lt;TEntity&gt; (2 of 2)

```csharp
public OrderProductAddNotificationBase(TEntity order, string productReference, 
    string productVariantReference, decimal qty, IDictionary<string, string> properties, 
    string bundleId, string parentBundleId)
```


### Properties

#### BundleId

```csharp
public string BundleId { get; }
```


---

#### ParentBundleId

```csharp
public string ParentBundleId { get; }
```


---

#### ProductReference

```csharp
public string ProductReference { get; }
```


---

#### ProductVariantReference

```csharp
public string ProductVariantReference { get; }
```


---

#### Properties

```csharp
public IDictionary<string, string> Properties { get; }
```


---

#### Quantity

```csharp
public decimal Quantity { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->