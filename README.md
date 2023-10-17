## Create project
```bash
npx create-next-app@latest
```

## Generate secure secret code with cmd
```bash
openssl genrsa 2048
```

## Upstash:clear all data command
```bash
flushall
```

## Important tech includes:
- [Next-Auth with Google Auth](https://console.cloud.google.com/)
```bash
# Redirect Callback URL
http://localhost:3000/api/auth/callback/google
# Authorize JavaScript origins
:http://localhost:3000
:http://localhost
```
- [Pusher websocket](https://pusher.com/) for real time chat
- [Upstash](https://upstash.com/) (Redis services which treat as db)
- Typescript
- Zod (validator)
- middleware for route protection

## Deployment
https://vercel.com/
