# MMMMobileAlerts

Documentation about the protocols of ELV Mobile Alerts sensors plus a node MQTT gateway

# Mobile Alerts

This document tries to describe every detail of the Mobile Alerts sensors, which are sold by [ELV](https://www.elv.de/ip-wettersensoren-system.html) in Germany, but are also available at the common suspects (Amazon, etc). Be careful buying at Amazon: certain sensors mention Mobile Alerts, but seem to be designed for the US. They are _not_ compatible with the ELV Mobile Alerts ones!

Mobile Alerts is covering mostly climate sensors, but also contains moisture and door/window sensors plus a sound detector, which acts as a gateway for smoke sensors.

The [Mobile Alerts](http://www.mobile-alerts.eu) are a version of the [LaCrosse Alerts Mobile](http://www.lacrossetechnology.com/alerts/) system made for the European market.

## Detailed Infomation

- [Mobile Alerts ELV vs LaCrosse](MobileAlertsELVvsLaCrosse.markdown) - Difference between ELV and LaCrosse sensors
- [Mobile Alerts Devices](MobileAlertsDevices.markdown) - List of all devices with technical infos
- [Mobile Alerts Sensor QR Code](MobileAlertsSensorQRCode.markdown) - QR Code format found on sensors
- [Mobile Alerts Website](MobileAlertsGatewayWebsite.markdown) - All data send into the cloud is available via a web-interface.
- [Mobile Alerts Gateway](MobileAlertsGateway.markdown) - Serial number format, LED function
  * [Mobile Alerts Gateway Web Interface](MobileAlertsGatewayWebInterface.markdown) - Web interface of the Gateway
  * [Mobile Alerts Gateway UDP Protocol](MobileAlertsGatewayUDPInterface.markdown) - Find/Configure a Gateway
  * [Mobile Alerts Gateway REST API](MobileAlertsGatewayRESTAPI.markdown) - Public limited REST API
  * [Mobile Alerts Gateway Application API](MobileAlertsGatewayApplicationAPI.markdown) - API used by iOS application to read all data from the cloud
  * [Mobile Alerts Gateway Upload into Cloud](MobileAlertsGatewayBinaryUpload.markdown) - binary protocol used by the Gateway to upload sensor data into the Cloud


# Tradução pt-br

# MMMMobileAlerts

Documentação sobre os protocolos dos sensores ELV Mobile Alerts mais um gateway MQTT de Node

# Alertas móveis

Este documento tenta descrever cada detalhe dos sensores mobile alerts, que são vendidos por [ELV](https://www.elv.de/ip-wettersensoren-system.html) na Alemanha, mas também estão disponíveis(Amazon, etc). Tenha cuidado com a compra na Amazon: certos sensores mencionam alertas móveis, mas parecem ter sido projetados para os EUA. Eles são _not_ compatíveis com os alertas móveis ELV!

Os alertas móveis cobrem principalmente sensores climáticos, mas também contém sensores de umidade e porta/janela, além de um detector de som, que atua como um portal para sensores de fumaça.

Os [Alertas Móveis](http://www.mobile-alerts.eu) são uma versão do sistema [LaCrosse Alerts Mobile](http://www.lacrossetechnology.com/alerts/) feito para o mercado europeu.

## Infomação detalhada

- [Alertas móveis ELV vs LaCrosse](MobileAlertsELVvsLaCrosse.markdown) - Diferença entre sensores ELV e LaCrosse
- [Dispositivos de alerta móvel](MobileAlertsDevices.markdown) - Lista de todos os dispositivos com informações técnicas
- [Sensor de alertas móveis QR Code](MobileAlertsSensorQRCode.markdown) - Formato QR Code encontrado nos sensores
- [Mobile Alerts Website](MobileAlertsGatewayWebsite.markdown) - Todos os dados enviados para a nuvem estão disponíveis através de uma interface web.
- [Mobile Alerts Gateway](MobileAlertsGateway.markdown) - Formato de número de série, função LED
  * [Mobile Alerts Gateway Web Interface](MobileAlertsGatewayWebInterface.markdown) - Interface web do Gateway
  * [Mobile Alerts Gateway UDP Protocol](MobileAlertsGatewayUDPInterface.markdown) - Encontrar/Configurar um Gateway
  * [Alertas móveis Gateway REST API](MobileAlertsGatewayRESTAPI.markdown) - API REST limitado público
  * [Mobile Alerts Gateway Application API](MobileAlertsGatewayApplicationAPI.markdown) - API usada pelo aplicativo iOS para ler todos os dados da nuvem
  * [Alertas móveis Gateway Upload in Cloud](MobileAlertsGatewayBinaryUpload.markdown) - protocolo binário usado pelo Gateway para carregar dados de sensores na Nuvem
