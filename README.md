# Install KACE Agent for Rocky Linux
- sudo yum install cups pciutils psmisc
- rpm -ivh ampagent-14.0.91.rhel.64_cnshaskacev1.virtuosgames.com+gFymJ8gn3wa-28nVDGcbGOzGOfQ_xI7ERRebgcfB7184g6Hj5gRLrA.rpm
- cd /opt/quest/kace/bin/
- ./runkbot 1 0

# Start and Stop KACE Agent for Rocky Linux.

## To start the Agent, enter:
-  /opt/quest/kace/bin/AMPTools start
## To stop the Agent, enter:
-  /opt/quest/kace/bin/AMPTools stop

# Manually remove KACE Agent for Rocky Linux.

-  sudo rpm -e ampagent
-  rm -rf /var/quest/kace/
