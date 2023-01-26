# Use Prisma ORM for Deno

Referenced GitHub Link  
https://github.com/denoland/examples/tree/main/with-prisma

## Some commands were replaced by the following and executed

### Before

```
deno run -A npm:prisma generate --data-prxoxy
```

### After

```
deno run -A --unstable npm:prisma generate --data-proxy
```

## Prisma Cloud screen after prisma/seed.ts execution

![Prisma Cloud Screen](https://user-images.githubusercontent.com/43814578/214876932-f90c5899-96cf-4cfc-a421-738c3ef7656c.png "Prisma Cloud Screen")