**Track**: Software Development  
**Focus**: Command Line + GitHub Workflow  
**Time**: 60 minutes  
---

##  Objective

Use only the **terminal** to automate setup and interact with GitHub.

---

## Task

### Part A: Write a Setup Script (7 marks)

Inside a folder named `automation_scripts/`, create a file called `setup.sh`. The script must:

1. Create a folder called `project_folder/`  
2. Inside it, create two folders: `src/` and `docs/`  
3. Create a JavaScript file inside `src/` called `index.js` with this line:
   ```bash
   echo "console.log('Project started');" > project_folder/src/index.js
   ```
4. Print this after setup is complete:
   ```bash
   echo "✅ Folder structure created successfully!"
   ```

Run your script using:
```bash
bash automation_scripts/setup.sh
```
5. Push your work to github.
