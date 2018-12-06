netuitive-agent-elasticbeanstalk
================

0.1.0 (2017-01-26)

- Initial version.

0.2.0 (2018-02-27)

- Update to batch size 500.
- Updates to collector configurations.

0.3.0 (2018-11-15)

- Add minimal mode (off by default) option to the NetuitiveDockerCollector
- Add a SimpleCollector config (off by default)
- Exclude device mapper virtual drives from DiskSpaceCollector by default
- Add a BaseCollector config (on by default)

NEXT

- Add a default TCPCollector config
- Add ConsulCollector.conf to project config
- Add pkg concurrent-log-handler to fix locking, I/O errors when multiprocess logging to single file
- Make ConcurrentRotatingFileHandler default log handler in netuitive-agent.conf
- Add Docker Container Uptime feature to the NetuitiveDockerCollector
