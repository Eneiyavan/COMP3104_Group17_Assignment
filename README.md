# COMP3104_Group17_Assignment

## Group Members
- **Leader:** Eneiyavan Sivaganean (101584721) - [GitHub](https://github.com/Eneiyavan)
- **Member 2:** Fabiha Ishaque (101445115) - [GitHub](https://github.com/fabihaishaque)
- **Member 3:** Jamal Alhariri (STUDENT ID) - [GitHub](https://github.com/JamalAlhariri)
- **Member 4:** Kamran Omar (101564373) - [GitHub](https://github.com/kamranomars-sudo)
- **Member 5:** Nousheen Perween (STUDENT ID) - [GitHub](https://github.com/Nousheen83)

## Project Description
This repository hosts the group assignment for the COMP3104 DevOps course at George Brown Polytechnic. It focuses on collaborative Git workflows, a per-developer branching strategy, pull requests, merge conflict resolution and continuous integration with GitHub Actions.
 
Each member created three text files about George Brown College, the DevOps course and the importance of DevOps in the software development lifecycle, and made at least 10 commits on their own branch.
 

## Repository Structure
- `README.md`: project documentation, updated by all members
- `.github/workflows/ci.yml`: GitHub Actions CI workflow
- `.github/PULL_REQUEST_TEMPLATE.md`: pull request template
- `STUDENTID_gb.txt`, `STUDENTID_devops.txt`, `STUDENTID_sdlc.txt`: files created by each member

## Setup Instructions
1. Clone the repository:
```bash
   git clone https://github.com/Eneiyavan/COMP3104_Group17_Assignment.git
   cd COMP3104_Group17_Assignment
```
2. Create your own branch using the format `STUDENTID-Name`:
```bash
   git checkout -b STUDENTID-Name
   git push -u origin STUDENTID-Name
```
3. Add your three files, commit regularly with clear messages, and push your branch.
4. Pull the latest changes often:
```bash
   git pull origin master
```
5. Open a pull request from your branch to `master` and resolve any conflicts before merging.

## CI/CD Pipeline
The project uses GitHub Actions for continuous integration. The workflow is defined in `.github/workflows/ci.yml` and runs on every push. It runs on an `ubuntu-latest` runner, checks out the repository code and prints status messages to confirm the pipeline is working. The results can be viewed in the **Actions** tab of the repository.
 
## Branching Strategy
This project uses a per-developer branching strategy. Each member works on their own branch named `STUDENTID-Name`, and no one commits directly to `master`. Changes are merged into `master` through pull requests, which protects the main branch, lets members work independently and allows peer review. The pull request template in `.github/PULL_REQUEST_TEMPLATE.md` is used for every PR.