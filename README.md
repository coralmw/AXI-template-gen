# Use cases

I often want to add a quick AXI interface to a HDL project, and the Vivado templating is overly tied to the IP flow and still requires some modification.

This project takes a register specification in the form of a YAML document that describes the names, directions, and widths of registers you need, and generates a AXI module to integrate.

# Dependancies

Python3, 
`pip3 install cheetah3 PyYAML`

# Usage

./gen.py -c <YOUR YAML SPEC> -o module.v
