## uptimeKuma 

### 保活变量
```
STREAMLIT_APP_URL=https://python-xray-argo-yutian81.streamlit.app
```

### POST
- 地址
```
https://api.github.com/repos/yutian81/Keepalive/dispatches
```

- header
```
{
  "Authorization": "Bearer <pat token>",
  "Accept": "application/vnd.github+json"
}
```

- body
```
{
  "event_type": "streamlit",
  "client_payload": {
    "status": "{{ status }}"
  }
}
```
