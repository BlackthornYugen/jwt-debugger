## JWT.io

<img src="../media/jwt.jsteelkw.dev.png?raw=true"/>

Fork of jwt.io that just focuses on the debugger. Forked from [//github.com/jsonwebtoken/jsonwebtoken.github.io](//github.com/jsonwebtoken/jsonwebtoken.github.io)

## Notes

Add CSP to csp.map:

```
jwt default-src 'self' ; style-src 'self' 'unsafe-inline' ; font-src 'self' https://fonts.gstatic.com;
```

TODO: remove inline styles so I don't need unsafe inline in the CSP.