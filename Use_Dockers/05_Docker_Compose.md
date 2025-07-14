# 🧩 Docker Compose

```yaml
version: '3.8'
services:
  app:
    image: node:18
    volumes:
      - .:/app
    working_dir: /app
    command: ["node", "index.js"]
```
