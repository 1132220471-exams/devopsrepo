# DevOps Concepts and Demonstration

## Definitions

**DevOps**  
A way of working where development and operations teams collaborate to deliver software faster and more reliably.

**CI (Continuous Integration)**  
Practice of merging code changes frequently into a shared repository, where automated tests run to catch issues early.

**CD (Continuous Delivery/Deployment)**  
Ensures that integrated code can be automatically delivered to production (or at least to a staging environment) without manual steps.

**Containerization**  
Packaging an application and all its dependencies into a lightweight unit (a container) so it runs consistently across environments.

**Rollback**  
Returning a system to a previous stable state if a new release causes problems.

---

## Connecting Concepts to This Assignment

- By writing automation in `script.sh`, I practiced **DevOps principles of automation**.  
- Using Git and GitHub demonstrates **CI/CD readiness**: commits and branches can be integrated and tested.  
- If I made a mistake, I could use Git to **rollback** to a previous commit.  
- Creating the `exam` project structure shows **container-like isolation** — everything is packaged together and reproducible.  
- Overall, the workflow (create → test → commit → push) is a mini example of how **DevOps pipelines** work.


Steps Followed to Complete This Assignment :- 

Created the Exam Directory 

Made a folder named exam in my home directory: mkdir exam

Created script.sh :- nano script.sh

Made the Script Executable :- chmod +x script.sh

Executed Script and Saved Output :- ./script.sh > script.log

Initialized Git Repository :- git init
git remote add origin https://github.com/1132220471-exams/devopsrepo.git

Created Feature Branch :- git checkout -b feature

Added and Committed Files :- git add Readme.md script.sh script.log
git commit -m "Add definitions, script, and output log"

Pushed to GitHub :- git push -u origin feature

