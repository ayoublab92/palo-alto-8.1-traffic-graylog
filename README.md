# palo-alto-8.1-traffic-graylog

This is a content pack for Graylog that analyzes traffic from PanOS 8.1

Syslog listens on 10001 UDP, just create your log forwarder and point it to your server.

This comes with:
- Input for firewall (10001 - UDP)
- All extractors attacted to input
- Dashboard showing firewall traffic over last 1 day
- Traffic stream
