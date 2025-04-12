---
name: API bug report
about: Create a report to help us improve
title: '[Bug] Short and clear title, e.g., GET /users returns 500'
labels: 'bug,api'
assignees: ''

---

🐞**Describe the bug**  
A clear and concise description of the issue. Explain what went wrong and why you believe it's a bug.

🔁**To Reproduce**  
Please list the steps to reliably reproduce the issue:
1. Page `/users`
2. Use the parameter `page=1`
3. Receive a 500 Internal Server Error

## 📬 Request Details  
**Endpoint**: `/users`  
**Method**: `GET`  
**Headers**:  
**Request body**:
```
{
    "uid" = "123"
}
```

## ✅ Expected outcomes
A brief description of what you expected to happen instead.
e.g., "Expected a 200 response with a list of users."

## 📎Screenshots
If applicable, add screenshots to help explain your problem.

## 🧪 Environment
- API version: v1.3.0
- Client / Tool: e.g., Postman, curl, Java SDK
- Timestamp (if applicable): 2025-04-12 15:30 GMT+8

## Additional context
Add any other context about the problem here.
