# Permissions & Postgresql

## Permissions in REST framework are always defined as a list of permission classes
### If any permission check fails, an exceptions.PermissionDenied or exceptions.NotAuthenticated exception will be raised, and the main body of the view will not run.


##  permission checks fail, either a "403 Forbidden" or a "401 Unauthorized" response will be returned, according to the following rules:
- The request was successfully authenticated, but permission was denied. — An HTTP 403 Forbidden response will be returned
- The request was not successfully authenticated, and the highest priority authentication class does not use WWW-Authenticate headers. — An HTTP 403 Forbidden response will be returned.
- The request was not successfully authenticated, and the highest priority authentication class does use WWW-Authenticate headers. — An HTTP 401 Unauthorized response, with an appropriate WWW-Authenticate header will be returned.


