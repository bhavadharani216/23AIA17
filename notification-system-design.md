# Notification System Design


## Satge 2
```
If the data volume is increased, it may face some storage issue and data collapse, also missing data are also will happens
use a data as effecient and protective.
```

## Stage 3

```
SELECT * FROM notifications
WHERE studentID= 1042  AND isRead = false
ORDER BY createdAt DESC
GROUP BY notificationType;
 ```

## Stage 4

```
Use a data Base that able to contain a 5,000,000 . Use a effective methods to push notifications to students .
```

## Stage 5 

```
Before sending mail , ensure that , there is a 5,000,000 students mail id is correct and also ensure that everyone email id is present.
```
