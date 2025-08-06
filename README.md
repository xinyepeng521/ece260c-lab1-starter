# ece260c-lab1-complete

## Overview
This lab focuses on Design Space Exploration (DSE) in digital circuit design, covering synthesis, technology mapping, timing/power analysis, and full physical implementation validation. It consists of three main sections:

- **Section I**: Logic synthesis and technology mapping using Yosys, generating gate - level netlists and analyzing their structures.
- **Section II**: Automated DSE via scripting to explore the impact of different parameter configurations on design performance (frequency) and area.
- **Section III**: Full Placement and Routing (P&R) validation of the optimal design selected from DSE, comparing differences between synthesis and physical implementation stages.

## Prerequisites

### Software Environment
- Docker (with GUI enabled, refer to the Software Setup Guide)
- Git
- Python 3.x (with `matplotlib` library installed)
- OpenROAD, Yosys, OpenSTA (included in the Docker container)

### Container Version Note
Due to version mismatch between OpenROAD and OpenROAD - flow - scripts, the recommended container is: `ghcr.io/udxs/ece260c - sources:main` (no `orfs_copy` command, use `cp -r` instead).

## Installation Steps

### Clone the Repository
If GitHub Classroom is unavailable, clone the lab repository directly:
```bash
git clone https://github.com/UDXS/ece260c - lab1 - starter.git
cd ece260c - lab1 - starter