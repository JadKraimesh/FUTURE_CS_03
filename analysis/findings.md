# API Security Findings

## API Tested
ReqRes API  
https://reqres.in

## Summary
The API Security Risk Analysis was performed using read-only GET requests through Postman. The purpose was to inspect authentication behavior, API responses, headers, and endpoint exposure without exploiting or harming any system.

## Findings Table

| No. | Finding | Severity | Business Impact | Recommendation |
|---|---|---|---|---|
| 1 | Authentication enforced on selected endpoints | Informational | API requires authentication before allowing access to protected resources. | Continue enforcing API key or token-based authentication. |
| 2 | Unauthorized requests correctly blocked with HTTP 401 response | Informational | Prevents unauthenticated users from accessing protected endpoints. | Maintain strong authentication validation mechanisms. |
| 3 | Predictable endpoint structure | Low | Attackers may attempt endpoint enumeration. | Apply authorization checks and monitoring across endpoints. |
| 4 | Limited visible rate-limiting evidence | Medium | APIs may be vulnerable to abuse if request throttling is absent. | Implement rate limiting and abnormal traffic monitoring. |
| 5 | Response metadata exposure | Low | Response details may reveal information about API structure. | Reduce unnecessary metadata exposure where possible. |

## Conclusion
The tested API demonstrated positive authentication enforcement by blocking unauthorized requests using HTTP 401 responses and API key requirements. While this reflects good security practice, additional protections such as rate limiting, endpoint monitoring, and metadata minimization would further strengthen API security in a production SaaS environment.
