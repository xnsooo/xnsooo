### Version Control & Collaboration
---
- It is essential to use a version control system for **software development** and **other documentation works**.
- Basic solution: **Making copies**
- We need a **systematic management system** for version control and collaboration

### Changes vs Snapshots
---
**Changes**: Storing data as changes to the basic version
**Snapshots**: Storing data as snapshots

### Three Staes in Git
---
**Modified**: Working Directory
**Staged**: Staging Area
**Comitted**: git directory(Repository)

### Git config
---
Git configurations are stored in three levels
1. **System level**: --system option. Affects all uses and repositories on the system
2. **Global(user) level**: --global option. Affects all repositories of a current user
3. **Local level**: --local option. Specific to the current repository
- Each level overrides values in the previous level: system -> global -> local

### Git
---
- **$ git init**: Initializing a repository in an existing directory
- **$ git status**: Checking repository status
- **$ git add [file_name]**: Adding a new file to be staged(tracked)
- **$ git add.**: Adding all files to be staged(tracked)
- **$ git rm -cached [file_name]**: Unstaging a file
- **$ git commit -m "commit message"**: Commit

