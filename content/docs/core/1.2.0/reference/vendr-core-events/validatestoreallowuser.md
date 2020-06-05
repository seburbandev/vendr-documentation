---
title: ValidateStoreAllowUser
description: API reference for ValidateStoreAllowUser in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateStoreAllowUser

```csharp
public class ValidateStoreAllowUser : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateStoreAllowUser

```csharp
public ValidateStoreAllowUser(StoreReadOnly store, string userId)
```


### Properties

#### Store

```csharp
public StoreReadOnly Store { get; }
```


---

#### UserId

```csharp
public string UserId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->