# API Deployment

## Managing Django Settings: Issues
- Different environments:Each environment can have its own specific settings
- Sensitive data:you have SECRET_KEY in each Django project. On top of this there can be DB passwords and tokens for third-party APIs like Amazon or Twitter. This data cannot be stored in VCS.
- Sharing settings between team members
- Django settings are a Python code

# SH
## What Is SSH?
### Secure Shell Protocol, is a remote administration protocol that allows users to access, control, and modify their remote servers over the interne
## How Does SSH Work?
### ssh {user}@{host}
-  {user} represents the account you want to access
-  {host} refers to the computer you want to access
