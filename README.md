# nrf51_ble_automation_io
BLE automation IO service for NRF51, using Nordic SDK as base.

# How to use
First install the COIoT nrf51-sdk, then put this repo as a subdirectory of nrf51-sdk at
`nrf51-sdk/lib/ble_automation_io`.

The service interface is pretty-much self-explanatory, using meson, use mesonconf to set
the SDK libble_aio option to true, then include ble_automation_io.h directly.

See the switch example for an usage of it.
