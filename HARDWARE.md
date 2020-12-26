# MCU

Not sure yet.

#### EFM32
- Cheap
- Decent MCU
- Not sure if it can drive the J1850 interface directly
- No USB High-Speed, only Full-Speed

#### STM32
- Cheap
- Popular
- Not *that* great
- Not sure if it can drive the J1850 interface directly
- Some models have USB High-Speed, but are more expensive

#### LPC1500
- Expensive
- Able to drive the J1850 interface directly
- No USB High-Speed, only Full-Speed
- Used in [allpro](http://www.obddiag.net/allpro.html)

#### LPC4300
- Very expensive
- Big package
- Able to drive the J1850 interface directly
- USB High-Speed (multiple controllers available)
- Two cores available (one M4 and one M0)
- Can be GreatFet, FaceDancer, etc. compatible (hacker friendly)
- Internal memory
- LCD support available (future?)
- Ethernet support available (future?)

#### EPC5 (not a MCU :stuck_out_tongue:)
- Expensive (though, not necessarily very expensive)
- Able to drive the J1850 interface directly
- USB Full-Speed, or High-Speed with a PHY (expensive configuration)
- Possible to implement CAN in gateware, though there isn't a free implementation yet
- Can run Linux
- Very hackable
- Very customizable
- **Possibility** to support other interfaces that get added to OBD-II in the future without hardware changes
- BGA, which is not very nice for folks assembling boards


# CAN Transceiver

**TCAN4551** (w/ option to upgrade to TCAN4550)

TCAN4550 is basically a TCAN4551 with time-out watchdog support.

The MCP2517FD was considered but decided against due to the much lower voltage
range in the CAN terminals and better behavior when unpowered.
