# Digital Logic Circuits: D Latch and NAND-Master Slave Flip Flop

Welcome to the Ngspice circuits repository, where we explore two fundamental digital logic circuits: the D Latch and the NAND-Master Slave Flip Flop.

## D Latch

### Overview

A **D latch** is a simple sequential logic circuit used to store one bit of data. It's composed of two cross-coupled NAND gates and an inverter. The primary purpose of a D latch is to "latch" or hold a value at its output based on the current input.

### Components

The D Latch circuit consists of the following components:

- **Tri-State Inverters:** These inverters allow control over input/output states.
- **CMOS Inverter:** This inverter provides the inversion function.

![unnamed](https://github.com/Hrishikesh-S-Nair/D-latch-and-NAND-MS-FF/assets/125496407/c01f3ec8-fe40-4870-b5fd-4c1233fd573e)


### Functionality

The D Latch has two stable states: **SET** and **RESET**. The state of the latch is determined by its input (D). The circuit operates as follows:

1. When the clock signal is high, the output follows the input (D).
2. When the clock signal is low, the output retains its previous state.

## NAND-Master Slave Flip Flop

### Overview

The **NAND-Master Slave Flip Flop** is a sequential logic circuit constructed using NAND gates and inverters. It serves as a building block for more complex circuits, offering memory and storage capabilities.

### Components

The NAND-Master Slave Flip Flop circuit comprises the following components:

- **NAND Gates:** Eight NAND gates are used to construct the flip flop.
- **Inverter:** An inverter is employed to achieve inversion.

![unnamed-1](https://github.com/Hrishikesh-S-Nair/D-latch-and-NAND-MS-FF/assets/125496407/065dfcdc-fbba-44c3-97ff-c358c0139b22)

### Operation

The flip flop operates in two stages: **master** and **slave**. It provides a mechanism for data storage and clocked signal propagation:

1. **Master Stage:** The state of the flip flop is determined by the inputs and clock signal in the master stage.
2. **Slave Stage:** The flip flop stores the master stage's output and transmits it to the output in the slave stage when the clock signal transitions.

## Usage

Clone or download this repository to explore the complete Ngspice code and simulations for both the D Latch and the NAND-Master Slave Flip Flop circuits. Additionally, you can modify and experiment with the circuits to deepen your understanding of digital logic.

## License

This project is licensed under the [MIT License](LICENSE).

