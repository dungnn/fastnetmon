Roadmap of FastNetMon project

- Build binary packages for all popular platforms
- Add open source filtering solution based on netmap-ipfw
- Implement flow spec management for signaling to uplink (raw support, only protocols and src/dst ports)
- Implement attack analyzer for detection of packets which belongs to attack 
- Implement complete flow spec support for netmap-ipfw for thorough full wire-speed packet filtration
- Implement solution for SYN flood mitigation based on syn-proxy ideas (prototype you could find [here](https://github.com/FastVPSEestiOu/fastnetmon/tree/master/syn_umbrella)) 
- Implement application level flood monitoring (http, dns, https)
- Implement web interface
- Implement API
