![Descripción](https://img.shields.io/badge/Descripción-blue?style=for-the-badge)

Una colección de ejercicios de práctica de programación de redes en C, que cubre desde los conceptos básicos de sockets hasta la implementación de protocolos simples. Cada módulo es autónomo y contiene su propio Makefile y un ejercicio con objetivos claros.

![Módulos y Funcionalides](https://img.shields.io/badge/"Módulos y Funcionalidades"-blue?style=for-the-badge)

| Módulo       | Descripción                                                                 |
|:------------:|------------------------------------------------------------------------------|
| **01_ping**  | Implementa un cliente y servidor que intercambian mensajes “PING”/“PONG”     |
| **02_echo**  | Servidor TCP concurrente que devuelve al cliente cualquier línea recibida    |
| **03_udp_chat** | Chat simple entre varios clientes usando sockets UDP                      |
| **04_file_transfer** | Transferencia de ficheros entre cliente y servidor con control de flujo |
| **05_http**  | Mini servidor HTTP que atiende peticiones GET y sirve archivos estáticos     |
| **06_dns**   | Consulta manual a un servidor DNS usando UDP                                |


![Estructura](https://img.shields.io/badge/Estructura-orange?style=for-the-badge)

```text
12.Netpractice-main/
├── 01_ping/              
│   ├── client.c          # Cliente PING/PONG
│   ├── server.c          # Servidor PING/PONG
│   └── Makefile
├── 02_echo/              
│   ├── server.c          # Servidor TCP concurrente (fork)
│   ├── client.c          # Cliente de pruebas
│   └── Makefile
├── 03_udp_chat/          
│   ├── server.c          # Servidor UDP de chat
│   ├── client.c          # Cliente UDP
│   └── Makefile
├── 04_file_transfer/     
│   ├── server.c          # Envía/recibe ficheros
│   ├── client.c          
│   └── Makefile
├── 05_http/              
│   ├── http_server.c     # Mínimo servidor HTTP
│   └── Makefile
├── 06_dns/               
│   ├── dns_client.c      # Consulta DNS manual
│   └── Makefile
└── README.md             # Este documento
```

![Compilación](https://img.shields.io/badge/Compilación-yellow?style=for-the-badge)

  cd 02_echo
  make            # genera el ejecutable (por ejemplo: server y client)
  make clean      # elimina objetos (*.o)
  make fclean     # elimina ejecutables y objetos

Para compilar todos los módulos de una sola vez:

  make all        # (desde la raíz) invoca make en cada subcarpeta
  
![Autor](https://img.shields.io/badge/Autor-red?style=for-the-badge)

- Roberto del Olmo Lima
- [![GitHub](https://img.shields.io/badge/GitHub-Profile-informational?style=for-the-badge&logo=github&logoColor=white&color=181717)](https://github.com/legrol)
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roberto-del-olmo-731746245)
