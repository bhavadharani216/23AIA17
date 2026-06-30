# Notification System Design



```
Stage 3
```
SELECT * FROM notifications
WHERE studentID= 1042  AND isRead = false
ORDER BY createdAt DESC
GROUP BY notificationType;
 
 
