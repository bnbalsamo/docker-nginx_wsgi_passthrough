A minimal nginx container that will dynamically create an nginx configuration file on startup configured to route traffic to a filesystem socket.

Primarily for use as the serving container in a kubernetes pod, paired with a uwsgi/gunicorn application opening a socket on a shared volume.
