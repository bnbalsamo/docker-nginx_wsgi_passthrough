# ARCHIVED

This repository is archived. I am no longer actively developing/supporting it.

If you are interested in discussing the contents of this repository feel free to contact me
via the contact details provided in the "Author" section below.

---

A minimal nginx container that will dynamically create an nginx configuration file on startup configured to route traffic to a filesystem socket.

Primarily for use as the serving container in a kubernetes pod, paired with a uwsgi/gunicorn application opening a socket on a shared volume.

# Author

Brian Balsamo <Brian@BrianBalsamo.com>
