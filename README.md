# cloudfront
How to use and create cloudfront

## Behavior
```
0
/_next/static/*
mjts3omagkf
将 HTTP 重定向到 HTTPS
Managed-CachingOptimized
-
-
1
/assets/*
mjts3omagkf
将 HTTP 重定向到 HTTPS
Managed-CachingOptimized
-
-
2
/_next/data/*
mjts3omagkf
将 HTTP 重定向到 HTTPS
Managed-CachingOptimized
-
-
3
默认 (*)
mjts3omagkf
将 HTTP 重定向到 HTTPS
Managed-CachingDisabled
Managed-AllViewerExceptHostHeader
Managed-CORS-with-preflight-and-SecurityHeadersPolicy

```
