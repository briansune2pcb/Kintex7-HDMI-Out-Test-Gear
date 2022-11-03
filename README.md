# Kintex7-HDMI-Out-Test-Gear

An Test PCB for Kintex 7 FPGA board.

<img src="https://user-images.githubusercontent.com/115007168/199680892-50d72d2f-204a-4ccc-b516-02b106ac398a.png" width="400" />

## T11

```
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_clk[1]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_clk[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d0[1]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d0[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d1[1]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d1[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d2[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d2[1]}]

set_property PACKAGE_PIN AG29  [get_ports {hdmi_clk[1]}]
set_property PACKAGE_PIN AC29 [get_ports {hdmi_d0[1]}]
set_property PACKAGE_PIN AB29 [get_ports {hdmi_d1[1]}]
set_property PACKAGE_PIN Y30 [get_ports {hdmi_d2[1]}]
```

## T10

```
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_clk[1]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_clk[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d0[1]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d0[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d1[1]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d1[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d2[0]}]
set_property IOSTANDARD TMDS_33 [get_ports {hdmi_d2[1]}]

set_property PACKAGE_PIN F20 [get_ports {hdmi_d0[1]}]
set_property PACKAGE_PIN D17 [get_ports {hdmi_d2[1]}]
set_property PACKAGE_PIN E19 [get_ports {hdmi_d1[1]}]
set_property PACKAGE_PIN C20 [get_ports {hdmi_clk[1]}]
```
