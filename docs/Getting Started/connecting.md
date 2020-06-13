# Connecting

The Extremum API is accessed by making HTTP requests to a specific endpoint URLs, including API version. Every endpoint can be accessed only via secure protocol (SSL-enabled HTTPS, port 443).

Any connection to Extremum API requires a valid access token created by one of auth methods supported by #endpoint:Xs6PyTfzDS5z3Xotw endpoint. Successful authentication produces the token, which should be provided with every API call in `Authorization` header (see #trait:mtuRWugPb2nFH9XtA).