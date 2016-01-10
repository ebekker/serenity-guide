# Making Roles Multi-Tenant

So far, we have made users page work in multi-tenant style. Seems like we did too many changes to make it work. But remember that we are trying to turn a system that is not designed to be multi-tenant into such one.

Let's apply similar principles to Roles table.

Again, a user in one tenant shouldn't see or modify roles in other tenants and work in isolation.
