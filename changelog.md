## 2024.2_v1.2.3
* Adjust PS reference clock frequency to remove rounding errors
* Removed ME-XU8-5EV-1I-D12E, ME-XU8-7EV-1E-D11E and ME-XU8-7EG-2I-D11E product models
* Remove component declarations for components provided by the unisim library
* Add variable to disable PL DDR IP core instantiation

## 2024.1_v1.1.3
* Add CLK_USR IOBUFDS instance to top level VHDL
* Refactor documentation
* Allow setting of a custom Vivado project directory
* Connected the System Management Wizard interrupt to the PS
* Add gigabit transceivers to pinout file
* Added ME-XU8-7EG-2I-D11E product model

## 2022.1_v1.1.2
* Add I2C FPGA interface
* Doc: New document number
* Changed restriction names for PL memory
* Doc: Added eMMC troubleshoot section
* Disabled PullUps for eMMC IOs
* Fixed temperature limits
* Doc: Corrected links due to new Xilinx website
* Doc: Adjust base_dir with subfolder "reference_design" in description
* Added I2C_SCL_FPGA, I2C_SDA_FPGA and I2C_MIPI_SEL pins to reference design
* Added missing ST1 user LED pins

## 2020.2_v1.1.1
* Doc: Fix incompatible project name suggestion including a '+'
* Doc: Refer to system instead of application for creating boot image and program flash
* Doc: Updates in troubleshoot section and workarounds
* Doc: Minor optimizations
* Doc: Corrections in QSPI programming guide with MCT
* Doc: Improve MCT instructions

## 2020.1_v1.1.0
* Removed VCU as it will be included in the Enclustra Video Application Note
* Doc: Reworded ECC RAM section
* Removed archive containing all binaries (complete*.zip) from release binaries
* Doc: Fixed out of order step-by-step Vivado/Vitis instructions
* Disabled USB reset in PS
* Added Petalinux BSP to release binaries
* Versioning now includes Xilinx tool version

## 2020.1_v1.0.0
* First release
