# Prompt

- Go to the GitHub repository of Digital System Design (DSD)
  - Study VHDL and GHDL
- Go to the GHDL folder
  - Install GHDL and GTKWave
  - Run the Half Adder example
  - Run another example such as D Flip-Flop or 4-to-1 Multiplexer
  - Document the results on your GitHub repository
- Option 1: EDA Playground
- Option 2: Icarus Verilog
- Option 3: SmartSim on Raspberry Pi

## Half Adder Example
``` 
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
```

![Half Adder in GTKWave](assets/HA.png)


## 4 to 1 Multiplexer Example

``` 
$ ghdl -a mux.vhdl
$ ghdl -a mux_tb.vhdl
$ ghdl -e mux_tb
$ ghdl -r mux_tb --vcd=ha.vcd
```

![4 to 1 Multiplexer in GTKWave](assets/multip.png)
