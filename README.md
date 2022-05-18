# ESP8266-01_RTOS_AT_Bin_V2.2.1

## Feature
Updated SDK version to 3.4.43 Updated AT version to 2.2.1.0

#### Support MQTT AT Commands

#### Support HTTP AT Commands
• AT+HTTPCLIENT: Send HTTP Client Request
• AT+HTTPGETSIZE: Get HTTP Resource Size
• AT+HTTPCPOST: Post HTTP data of specified length

#### Support Web server AT Commands
• AT+WEBSERVER: Enable/disable Wi-Fi connection configuration via web server.

#### Download AT Firmware Guide

--flash_mode dout --flash_freq 80m --flash_size 1MB 

0x8000 partition_table/partition-table.bin 
0x9000 ota_data_initial.bin 
0x0 bootloader/bootloader.bin 
0x20000 esp-at.bin 
0x18000 at_customize.bin 
0x1A000 customized_partitions/client_cert.bin 
0x1B000 customized_partitions/client_key.bin 
0x1C000 customized_partitions/client_ca.bin 
0x1D000 customized_partitions/mqtt_cert.bin 
0x1E000 customized_partitions/mqtt_key.bin 
0x1F000 customized_partitions/mqtt_ca.bin 
0x19000 customized_partitions/factory_param.bin


