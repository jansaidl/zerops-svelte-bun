# Zerop x Svelte with Bun runtime

```yaml`
project:
  name: zerops-bun
services:
  - hostname: svelte
    type: ubuntu@22.04
    ports:
      - port: 3000
        httpSupport: true
    enableSubdomainAccess: true
    buildFromGit: https://github.com/fxck/zerops-svelte-bun
    minContainers: 1
```
