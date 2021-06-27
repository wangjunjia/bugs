# iOS 日期相关 bug

- 不支持 连接符（-）连接的日期格式
```
let dateString = '2000-12-12 12:00:00'

// error ❌
let err = new Date(dateString)
// okay ✅
let date = new Date(dateString.replace(/-/g, '/'))

```
