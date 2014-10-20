secure-socket.io-nginx-mvp
==========================

secured stream between the user and nodejs logic

an nginx.conf routing the incoming ws on port 80 to the node process running on it's own port. If the TLS will work by terminating at nginx, then that would be nice if I didn't need ot worry about it at the node end, but socket.io must work with it that way
