# Load balancer

Scripts to configure redundant web servers behind a load balancer.

- `0-custom_http_response_header`: installs Nginx and adds an `X-Served-By` header containing the server's hostname.
