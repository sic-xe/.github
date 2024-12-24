# [SIC/XE](https://sic-xe.github.io/)

This organization provides documentation and a few example projects for the
[Simplified Instructional Computer](https://wikipedia.org/wiki/Simplified_Instructional_Computer)
(SIC) hypothetical computer system.

The aim of the organization is to help students learn about the SIC architecture
and consequently systems programming in general.

## Project structure

The main resource is the website: [sic-xe.github.io](https://sic-xe.github.io/).
It contains extensive documentation about the architecture, including its
history, design, addressing modes, registers, assembly sintax etc.

Besides that the organization includes repositories with various resources:

- **[SICer](https://github.com/sic-xe/sicer)**: An example implementation of
an assembler and simulator for SIC/XE, written in Go.
The assembler generates object files from assembly source code and the simulator
allows running the generated code, either normally or instruction by instruction
(e.g. for debugging), and inspecting register states and memory contents.
- **[Examples](https://github.com/sic-xe/examples)**: A collection of example
assembly programs for SIC/XE along with their object code.
These can be directly assembled with the assembler, run with the simulator or
just used to debug your custom implementation of the assembler, since you can
compare the assembler's output with the provided assembled object code.
- **[sic-xe.github.io](https://github.com/sic-xe/sic-xe.github.io)**: The source
code of the website.
<!-- - **[FPGA](https://github.com/sic-xe/fpga)**: An implementation of the SIC/XE
architecture on a RealDigital Blackboard FPGA development board. -->

There are also a few other currently private (WIP) repositories, which you can
look forward to in the future, mainly a SIC/XE assembler and simulator, written
in Rust, and a SIC/XE hardware implementation on an FPGA.

The project (organization) as a whole is a work in progress, so it's constantly
changing and improving.

## Licensing

The repositories are licensed under various licenses, depending on the type of
the files.
In general all of the files are licensed under open source licenses and can be
freely reused, as long as major changes are shared back and attribution is given
to this organization.

As long as you don't resell the code, I won't go after you in any case, so feel
free to do what you want with it.

Licensing per repository is as follows:

- **[SICer](https://github.com/sic-xe/sicer)**:
[GNU GPLv3](https://github.com/sic-xe/sicer/blob/main/LICENSE)
([TLDR](https://choosealicense.com/licenses/gpl-3.0/))
- **[Examples](https://github.com/sic-xe/examples)**:
[The Unlicense](https://github.com/sic-xe/examples/blob/main/LICENSE)
([TLDR](https://choosealicense.com/licenses/unlicense/))
- **[sic-xe.github.io](https://github.com/sic-xe/sic-xe.github.io)**:
[CC-BY-SA-4.0](https://github.com/sic-xe/sic-xe.github.io/blob/main/LICENSE)
([TLDR](https://choosealicense.com/licenses/cc-by-sa-4.0/))
<!-- - **[FPGA](https://github.com/sic-xe/fpga)**:
[CERN-OHL-S-2.0](https://github.com/sic-xe/fpga/blob/main/LICENSE)
([TLDR](https://choosealicense.com/licenses/cern-ohl-s-2.0/)) -->

## Other useful SIC/XE projects and resources

Here's a few SIC/XE projects and resources not connected to this organization,
which I found useful:

- [SicTools](https://github.com/jurem/SicTools): System software and tools for
the SIC/XE hypothetical computer
- [VSCode SIC Assembly](https://github.com/jakoberzar/vscode-sic-assembly): A
VSCode extension for syntax highlighting and code completion for SIC assembly
