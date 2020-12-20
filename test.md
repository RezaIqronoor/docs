Test

```javascript
import server from 'server-init'

const app = server().initialization()

const host = app.host(8001, () => {
    console.log("Web App hosted no port 8001")
})
```

