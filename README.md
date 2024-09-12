# AutoServerRestart for EXILED

![downloads](https://img.shields.io/github/downloads/Vretu-Dev/AutoSR/total)

### Features:
- Restart after X time
- Broadcast before 30 seconds to restart
- Configurable command to be executed

Minimum Exiled Version: 8.9.8

### Config:

```yaml
AutoSR:
  is_enabled: true
  debug: false
  # Time after server will be restarted in seconds
  seconds_until_restart: 1800
  # Command to be executed eg: 'softrestart','restart','roundrestart'.
  command: 'softrestart'
  # Broadcast to be displayed.
  broadcast_message: 'Server will be restarted within 30 seconds'
```
