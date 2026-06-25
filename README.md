# VSD-Internship-4KB-SRAM-Design-using-OpenRAM-and-SKY130
<details>
<summary> 
<h2> overview </h2> 
</summary>
 📖This repository documents an internship project focused on the research, design, and analysis of a 1024×32 SRAM (32 Kbits / 4 KB) using the OpenRAM memory compiler and the SKY130 Process Design Kit (PDK). The project explores SRAM architecture, 6T SRAM cell operation, peripheral circuits, compiler configuration, and verification methodologies while targeting 1.8 V operation and an access time below 2.5 ns.

The internship also investigates how AI tools such as ChatGPT and Codex can support VLSI design workflows by assisting with repository analysis, tool setup, debugging, script understanding, and technical documentation. The work progresses from studying SRAM fundamentals to exploring OpenRAM-based SRAM generation, technology integration, characterization, simulation, timing analysis, and design verification using open-source tools. 
</details>

## Table of Content
* [Week 1](#week-1)
* [Week 2](#week-2)






## Week 1
Week 1 focused on researching SRAM design fundamentals and studying the reference OpenRAM-SKY130 repository for a 1024×32 (4 KB) SRAM. The objective was to understand the SRAM architecture, 6T bitcell operation, OpenRAM flow, SKY130 PDK integration, required input files, generated outputs, and common debugging methods. AI tools were used to analyze the repository, break the workflow into smaller learning tasks, and generate prompts for exploring the design flow. 
Based on this study, 
A compact IEEE-format report was prepared summarizing the SRAM architecture, OpenRAM-based design methodology, expected outputs, and debugging strategy.

## SRAM Specifications
|Parameter  |Value  |
|-----------|-------|
|Memory Size|1024x32| 
|Total Bits |32768 bits|
|Storage    |4KB|
|Technology |SKY130|
|Supply Voltage|1.8V|
|Compiler|OpenRAM|
|Access Time Target|<2.5ns|

<img width="593" height="457" alt="image" src="https://github.com/user-attachments/assets/b362129c-e551-48b2-bacd-f84e0bae362a" />

## 6T SRAM Cell
Include transistor-level discussion.
### Hold Mode
WL = 0
Access transistors OFF
Cross-coupled inverters store data
### Read Mode
BL and BLB precharged
WL enabled
Stored value discharges one bitline
### Write Mode
Write driver forces BL/BLB
WL enabled
Cell state flips


