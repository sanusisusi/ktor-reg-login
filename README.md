# ktor-restapi

Connected postgres database (dbs:users) using ktorm framework.
Implemented /register endpoint : post request : encrypted password via bCrypt library.
Implemented /login endpoint : post request : added validation, decrypted password via bCrypt library.
Implemented /me protected endpoint: get request: utilized JWT.
