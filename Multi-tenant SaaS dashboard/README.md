# MULTI-TENANT SAAS DASHBOARD
## SCENARIO:
A SaaS company offers analytics dashboards. Each company (tenant) can only see their own data. There is a shared API but data must be completely isolated between tenants.


## GOAL:
Design a multi-tenant architecture with strong data isolation.

### DIAGRAM INCLUDES:
-	How tenants sign up and log in
-	How the API knows which tenant is making a request
-	How data is isolated (can tenant A ever see tenant B’s data?)
-	Whether you chose shared database or separate databases, and why
