# supervisord-init
Startup Script for supervisord

This will allow you to control supervisord,
with the additional benefit of killing child processes on shutdown if they get stuck

Install:

1. git clone https://github.com/Arola1982/supervisord-init.git
2. cd supervisord-init
3. mv supervisord /etc/init.d/supervisord
4. chmod o+x /etc/init.d/supervisord

Usage:

/etc/init.d/supervisord { stop|start|restart|status }
