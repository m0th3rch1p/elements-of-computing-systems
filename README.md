# The Elements of Computing Systems (Nand2Tetris)
Building a Modern Computer from First Principles
_By Noam Nisan & Shimon Shocken_
---

This project is to document my journey of creating a computer system from the ground up as I work through the different sections of **The Elements of Computing Systems** book.

![Computer Systems Diagram](./static/computer-system-diagram.jpg)

## Resources:
- Book: https://mitpress.mit.edu/books/elements-computing-systems-second-edition
- Website: https://www.nand2tetris.org/
- Digital HDL Tool: https://github.com/hneemann/Digital
- Nand2Tetris VS Code Plugin: https://marketplace.visualstudio.com/items?itemName=Throvn.nand2tetris

### Helper Commands
- Running the Hardware Simulator
  - `sh tools/HardwareSimulator.sh`
- Running the Digital HDL project:
  - Clone the repo and build the jar
  - Run jar via IntelliJ or from root of Digital project via `java -jar target/Digital.jar`

## Contents
### Hardware
- [X] [Boolean Logic](./notes/01-boolean-logic.md)
- [ ] [Boolean Arithmetic](./notes/02-boolean-arithmetic.md)
- [ ] [Memory](./notes/03-memory.md)
- [ ] [Machine Language](./notes/04-machine-language.md)
- [ ] [Computer Architecture](./notes/05-computer-architecture.md)
- [ ] [Assembler](./notes/06-assembler.md)

### Software
- [ ] [Virtual Machine I - Processing](./notes/07-virtual-machine-processing.md)
- [ ] [Virtual Machine II - Control](./notes/08-virtual-machine-control.md)
- [ ] [High-Level Language](./notes/09-high-level-language.md)
- [ ] [Compiler I - Syntax Analysis](./notes/10-compiler-syntax-analysis.md)
- [ ] [Compiler II - Code Generation](./notes/11-compiler-code-generation.md)
- [ ] [Operating System](./notes/12-operating-system.md)