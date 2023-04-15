# RSim

## Purpose

I would like to develop a compiler/simulator for RTL code (VHDL and Verilog).

The purpose is to provide a tool for people starting to develop hardware without
having to pay mandatory licenses to the two big professional simulators from
Cadence© and Synopsys©.

The tool does not aim to be complete or to work under any condition, but to be
capable of handling the most common situations. Little by little, then, I will
try to reduce the limitations found.

When developing hardware it is also necessary to be able to test the design
made: for this reason the compiler/simulator will try to support SystemVerilog
and UVM so that it can handle a verification environment. Again, the principle
will remain the same: useless, in my opinion, to launch into full support of
the standard, it is better to make the tool work and then compensate little by
little for the limitations found.

## Next steps

1. Read VHDL code
  1.1. Extract comments
  1.2. Detect packages / entities / architectures
  1.3. Translate signals
  1.4. Translate process

## Issues found
