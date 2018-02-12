# amd64
Intel-/AMD-based, 64-bit architecture builds

## Files
- **CORE:** A generic config for any Intel-/AMD-based 64-bit arch
- **STOTCH_CORE:** Similar to CORE, but with some things stripped out for personal builds
- **STOTCH_SM_SYS-5015A-EHF-D525_CORE:** Similar to STOTCH_CORE, but specific to the 5015A-EHF-D525 platform and stripped down to only necessities
- **STOTCH_FIREWALL_ATOM_D525_INTEL_1GBE:** My own custom Intel Atom D525 firewall with Intel 1Gbe interfaces
- **SM_SYS-5015A-EHF-D525:** Config for Supermicro 5015A-EHF-D525 servers
- **SM_X7SPE-HF-D525:** Config for Supermicro X7SPE-HF-D525 motherboards

### STOTCH_FIREWALL_ATOM_D525_INTEL_1GBE

This is a custom firewall build that is based on the Supermicro
5015A-EHF-D525 SoC box. In this build I use SD cards attached to SATA
for storage and have an Intel PRO/1000 expansion card for the
Internet-facing NIC and for the main private network uplink.

### STOTCH_SM_SYS-5015A-EHF-D525_CORE

Be careful if you choose to use this. A lot of devices that people might expect to be present in the build are not, like mouse and other input devices that are not necesary for my servers.
