# Environment

The environment attestor records the OS, hostname, username, and all environment variables set
of witness at execution time.  There is currently no way to block visibility of specific environment variables
so take care to not leak secrets stored in environment variables.
