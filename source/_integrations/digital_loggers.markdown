---
title: Digital Loggers
description: Connect and control your Digital Loggers devices using the Belkin WeMo integration
ha_category:
  - Binary Sensor
  - Fan
  - Hub
  - Light
  - Switch
ha_domain: digital_loggers
ha_codeowners:
  - '@esev'
ha_integration_type: integration
ha_config_flow: true
ha_platforms:
  - binary_sensor
  - fan
  - light
  - sensor
  - switch
ha_iot_class: Local Push
ha_ssdp: true
ha_homekit: true
ha_supporting_domain: wemo
ha_supporting_integration: Belkin WeMo
ha_release: pre 0.7
---

{% include integrations/supported_brand.md %}
