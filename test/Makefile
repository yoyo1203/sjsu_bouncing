# Tell cocotb we are using Verilog
TOPLEVEL_LANG = verilog

# Which simulator to use (Vivado's xsim in your case)
SIM = xsim

# Top-level module name in your Verilog design
TOPLEVEL = project

# Python testbench module (filename without .py)
MODULE   = test

# Verilog sources to compile
VERILOG_SOURCES = $(PWD)/project.v $(PWD)/hvsync_generator.v

# Include cocotb's standard rules
include $(shell cocotb-config --makefiles)/Makefile.sim
