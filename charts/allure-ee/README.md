# Allure Enterprise Edition

for disable startup probes add this code to `config.yaml`:
```yaml
report:
  probes:
    startup:
      enabled: false
gateway:
  probes:
    startup:
      enabled: false
uaa:
  probes:
    startup:
      enabled: false
```