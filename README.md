# VLSI Design Project 1

Hello everyone, this is the private repository for our project.
As suggested, we have to complete this project collaboratively. I have made a repo for collaborative and convenient work. Keep in mind that this will be useful for placements.

## Directory Structure

```
Team_num18
    ├── 📁 Charlib
    ├── 📁 Layout
    ├── 📁 LEF
    ├── 📁 LIB
    ├── 📁 Verilog
    ├── 📁 Spice_Netlist
    ├── 📁 Reports
    ├── Combinational_Lib.docx
    ├── Sequential_Lib.docx
    ├── Course_Project_1.pdf
    └── README.md
```
## Guidelines
- You can commit at your choice. Please commit at least after completing the file or at the end of the day.
- The directory structure is standard, as given in the PDF. Add your personal files and build files to the gitignore.
- I will use Markdown for the reporting, then later we convert it into LaTeX using Pandoc software.
- You can change others' files because it's git :) Or you can create issues and assign a task to others.

## Project

- [x] inv: Inverter
- [x] dfxtn:	Delay flop, single output Q, negedge clk
- [x] nand3b:	3-input NAND, first input inverted

## Flow of working

### 1. Create issue
- Create a new issue that is not present in the repository. 
- Add labels, Milestones, Relations, etc.
- Assign this to yourself or any teammate.

### 2. Create branch
- Create a branch in the development section and pull it into the local repo.
- Switch to that branch and start working on it.

### 3. Merge
- Use `git push` on that branch.
- After completing the issue, go to pull requests and create one.
- You can delete the parent branch or leave it as it is.
- Start working on the next issue.

## Deliverables

- [x] Project Plan and assignment
- [x] Report Skeleton
- [x] Spice Netlist
  - [x] inv
  - [x] dfxtn
  - [x] nand3b
- [x] Verilog code
  - [x] inv
  - [x] dfxtn
  - [x] nand3b
- [x] Draw the layout
  - [x] inv
  - [x] dfxtn
  - [x] nand3b
- [x] Export the LEF
  - [x] inv
  - [x] dfxtn
  - [x] nand3b
- [x] Export the LIB
  - [x] inv
  - [x] dfxtn
  - [x] nand3b
- [ ] Report Writing

## FAQs

1. I can't access
  - Port 22 is blocked by IIT Bombay. So update the port in SSH using AI, or use a personal hotspot, or you can use HTTPS.
  - If there is still a problem. Request the project owner.

2. Command for md to pdf
```bash 
pandoc temp.md --template=template.tex -o output.pdf --pdf-engine=lualatex --filter pandoc-crossref --lua-filter=inline.lua 
```
