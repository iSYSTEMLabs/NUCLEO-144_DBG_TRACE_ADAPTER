# Nucleo-144

ST Nucleo-144 adapter, exposing standard Coresight 20 connector

# Standalone mode
This example is based on NUCLEO-L4R5ZI

![NUCLEO-144_DBG_TRACE_ADAPTER](https://user-images.githubusercontent.com/83697037/146952844-df571071-6905-4791-a58a-c9f36350dc4a.jpg)


1. Place a jumper JP2 on NUCLEO-L4R5ZI - you might need to solder pins and then place a jumper
2. Remove all the jumpers from JP6 on NUCLEO-L4R5ZI
3. Plug on NUCLEO-144_DBG_TRACE_ADAPTER
4. connect CN5 on NUCLEO-L4R5Z and P3 on NUCLEO-144_DBG_TRACE_ADAPTER with wires
5. Plug 5V to P2 on NUCLEO-L4R5Z
6. Plug Coresight 20 to P1 on NUCLEO-L4R5Z
7. Turn ON SW1
8. Happy debugging and tracing

