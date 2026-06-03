# Hardware-Accelerated-RISC-V-Processor-on-PYNQ-FPGA-Platform
## Project Overview

This project aims to design and implement a **Hardware Accelerated RISC-V Processor** on the **PYNQ-Z2 FPGA platform**. The system combines a RISC-V softcore processor with a custom hardware accelerator to demonstrate the concept of **hardware-software co-design**. Computationally intensive tasks are offloaded to dedicated FPGA hardware, improving performance compared to software-only execution.

---

## Objectives

- Design and implement a RISC-V softcore processor on FPGA.

- Integrate memory and communication interfaces.

- Develop a hardware accelerator for computation-intensive tasks.

- Demonstrate hardware-software co-design using FPGA technology.

- Analyze system performance through simulation and synthesis results.

---

## System Architecture

<img width="460" height="272" alt="image" src="https://github.com/user-attachments/assets/0ea3c2c4-6fc9-41ce-b11c-5081bd998ce3" />


---

## Hardware Platform

- **Board:** PYNQ-Z2 FPGA

- **SoC:** Xilinx Zynq-7000

- **Processor Core:** PicoRV32 (RV32I)

- **Memory:** BRAM / DDR3

- **Communication Interface:** AXI

---

## Development Tools

- Vivado Design Suite

- Verilog HDL

- PYNQ Framework

- Juypter Notebook

- Vivado Simulator


---

## Project Workflow

1. Study RISC-V architecture and instruction set.

2. Implement and simulate the RISC-V processor.

3. Design memory and communication modules.

4. Develop the hardware accelerator.

5. Integrate processor and accelerator using AXI.

6. Verify functionality through simulation.

7. Perform FPGA synthesis and implementation.

8. Analyze performance and resource utilization.

---

## Functional Requirements

- Execute basic RISC-V instructions.

- Perform memory read and write operations.

- Transfer tasks to the hardware accelerator.

- Verify functionality through simulation.

- Generate FPGA bitstream for implementation.

---

## Results

- Successful RISC-V processor simulation.

- Verification of processor-memory communication.

- FPGA synthesis and implementation flow validation.

- Demonstration of hardware-software co-design architecture.

- Resource utilization within FPGA limits.

---

## Future Scope

- Physical deployment on PYNQ-Z2 FPGA board.

- Advanced hardware accelerators for DSP and AI applications.

- Custom RISC-V instruction extensions.

- Performance optimization and benchmarking.

- Multi-core RISC-V architecture exploration.

---

## References

### PicoRV32

https://github.com/YosysHQ/picorv32

### PYNQ Framework

https://github.com/Xilinx/PYNQ

### RISC-V International

https://riscv.org

---

## Author

**Tanushri**  

B.E. Electronics and Communication Engineering  

Final Year Project

---

## License

This project is developed for academic and research purposes.
