
# 🔐 STRIDE Threat Model: Dynamic Event Scheduler

| Threat | Description                         | Mitigation                            |
|--------|-------------------------------------|---------------------------------------|
| **S**poofing | Unauthorized user logins        | JWT token validation                 |
| **T**ampering | Altering event data             | Input validation and DB constraints   |
| **R**epudiation | Users denying changes          | Maintain event logs with user IDs    |
| **I**nformation Disclosure | Sensitive data leaks             | Use HTTPS and encrypted JWTs         |
| **D**enial of Service | API endpoint overuse         | Implement rate limiting              |
| **E**levation of Privilege | Unauthorized admin access      | Role-based permission checks         |
