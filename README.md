# COMP3104 – Group 34 (DevOps Assignment)

## Members
- 101511990 – Bramjot Singh (https://github.com/bramjot14)
- 101471907 – Kathan (https://github.com/Shadvengeror)
- 101122624 – Steven Nguyen (https://github.com/DistinctDynamo)
- 101485895 – Laurence Liang (https://github.com/101485895)

## Project
Each member adds three files: `StudentID_gb.txt`, `StudentID_devops.txt`, `StudentID_sdlc.txt`.  
Work is done **locally**, pushed to a personal branch, then merged via PR.

## Branch Strategy
- `main` = stable (no direct pushes).  
- Personal branch: `STUDENTID-First_Last`.  
- Regularly `merge origin/main` (or rebase) before PR.

## CI/CD
GitHub Actions run on PRs to `main` (basic checks).  
Merge only when checks pass.

## Steps
1) Create/update your 3 files.  
2) Commit locally → push your branch.  
3) Open PR (`base: main`, `compare: your-branch`).  
4) Resolve conflicts **locally**, push; then merge.
