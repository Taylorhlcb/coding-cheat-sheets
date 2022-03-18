curl -X POST -H 'Content-Type: application/x-www-form-urlencoded' \
https://login.microsoftonline.com/752ae952-b3ab-4c21-8a32-59e6ddba4c7c/oauth2/v2.0/token \
-d 'client_id=5dd09a49-e11e-4e7e-855e-109a2ea7f01e' \
-d 'grant_type=client_credentials' \
-d 'scope=2ff814a6-3304-4ab8-85cb-cd0e6f879c1d%2F.default' \
-d 'client_secret=aaaaa