# noarch/conf
Architecture indepdendent kernel configs

## Files
- **FIREWALL_CORE:** Personal firewall kernel config
- **FIREWALL_PROF:** Turns on kernel profiling
- **FIREWALL_DEBUG:** Turns on debug kernel debugging

### FIREWALL_CORE

This is a custom firewall build for my particular firewall platforms
which rely on a lot of in-memory activity, solid-state media for
persistence and batch updates to that media.

**CAUTION:** You'll find that certain features that most people have
come to rely on, like soft updates and file system buffers, are disabled
in my config. I use a very unique hardware arrangement, with some
highly customized file modification/creation strategies and most file
systems are read-only. The vast majority of the system activity resides
in RAM the vast majority of the time.
