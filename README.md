# STM32_LwIP_EC20
Transplant LwIP for dial-up Internet access of 4G module

MCU使用：stm32f407ZGT6 1024KB FLASH ，192KB RAM 
外部晶振12MHz，串口1和串口2，串口2接EC20，
等一段时间就会出现： 
our_ipaddr = 10.86.104.208 his_ipaddr = 10.64.64.64 netmask = 255.255.255.25 代表移植成功
