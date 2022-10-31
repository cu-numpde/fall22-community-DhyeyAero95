# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: MORIS (Multi-Physics Optimization Research and Innovation Systems)

MORIS is a shape/topology optimization tool for multiphysics problems. Its primary applications
include various structural and fluid interaction problems. It consists of five module primarily which
includes HMR, XTK, GEN, FEM and OPT. HMR generates background mesh for the problem, XTK decomposes and
triangulates the mesh at the interface of multi-phase problems, GEN is a geometry engine, FEM is a finite
element module and OPT is an optimization module. Currently, optimization is based on level-set field
formulation with extendded finite element formulation. MORIS also offers various workflows depending on the 
type of problem. Various examples have been demonstrated for each workflow. Some of the workflows include 
HMR-XTK-FEM workflow, STK-FEM workflow, STK-XTK workflow. Each workflow is suited for different types of problems. 

### Stats

| Description | Your answer |
|---------|-----------|
| https://github.com/kkmaute/moris |    |
| file:///home/bhavsar/codes/moris/build_dbg/share/doc/html/index.html |    |
| 2019 |   |
| 5 | `git shortlog -se --since=2021-10-01` may be useful |
| 7 |   |
| 2 | 
| Weekly meeting and slack | e.g., GitHub/GitLab issues, mailing list, Slack, etc.  |
| Typical number of emails/comments per week? |   |
| 2 |  |
| Typical commit size | `git log --shortstat` may be useful |
| pull requests | e.g., pull requests, patches on mailing lists   |
| no | yes/no |
| Does the project use continuous integration? | yes/no |
| Are any legal/licensing steps required to contribute? | no or explain below |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [ ] I have installed the software
- [yes ] I have run at least one example
- [ ] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

I am notsure what continuous integration means. I am also not sure about typical commit size as it varies
based on what every individual is contributing. 

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
