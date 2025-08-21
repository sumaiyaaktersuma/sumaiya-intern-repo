# 📊 Agile Workflows & Kanban – Reflection (Focus Bear Windows App Roadmap)

## 🔍 Research & Learn

**How does a Kanban board work, and how does it help manage workflow?**  
A Kanban board is a visual workflow management tool that shows tasks as cards moving through columns. Each column represents a stage in the process (e.g., backlog, in progress, testing, done). At Focus Bear, the Windows app roadmap uses Kanban boards in GitHub Projects to track development priorities, testing, and QA cycles.

**What do the different columns on the board represent?**  
From the roadmap views:  
- **Priority Columns** – “Super Low Priority,” “Very Low Priority,” “Untriaged (Low/Medium/High Priority).” These help decide what to focus on first.  
![priority-coloum](image-4.png)
- **Planning Columns** – “Next 2 weeks,” “Next Release,” “Q3 2025,” “Q4 2025.” These represent scheduling of tasks.  
- **Execution Columns** – “Clarification Needed,” “In Progress,” “Blocked.” Used for active task management.  
- **QA Columns** – “Ready for QA,” “QA in Progress,” “For Dev QA,” “QA Failed,” “QA Passed/Done.” These support systematic quality testing and feedback.  

**How do tasks move through the board, and who updates them?**  
Tasks begin in a planning or priority column, move into *In Progress* once development starts, and flow into QA columns before being marked *Done*. Developers usually move items through dev stages, while QA testers update the QA-related columns after running checks.

**What are the benefits of limiting Work in Progress (WIP)?**  
- Keeps team members focused on fewer items at once.  
- Prevents half-finished tasks from piling up.  
- Highlights bottlenecks (e.g., if many items are stuck in *Blocked* or *QA Failed*).  
- Improves throughput and quality of completed tasks.  


## 📝 Reflection

**How does Kanban help manage priorities and avoid overload?**  
By categorising tasks into *Priority* columns and *Timeline* columns, the team can focus on high-value tasks while postponing low-priority ones. This avoids overwhelming the roadmap and ensures critical issues are resolved first. WIP limits also keep the active workload under control.

**How can you improve your workflow using Kanban principles?**  
I can streamline my workflow by: 
1. Immediately updating task status following modifications to ensure the board shows actual progress.  
2. Examining *Blocked* or *Clarification Needed* jobs on a regular basis to avoid delays.  
3. Methodically displaying testing progress using the QA columns.  
4. For clarity, it is suggested that duplicate QA columns (*Ready for QA*) be combined.  

## 🛠️ Task

**Observation from Focus Bear’s Kanban board:**  
- Multiple board views (Priority, Timeline, Execution, and QA) are used to organise tasks.  
- Three distinct viewpoints are highlighted by each view: one for ongoing development, one for QA cycles, and one for long-term planning.  
- QA flow is very detailed, ensuring clear tracking from *Ready for QA* → *QA in Progress* → *QA Passed/Done*.
  

**Action Taken:**  
I reviewed an item under *QA Passed/Done* (e.g., **“Always blocked URLs – show the oops I actually need it”**) and noted how it moved from development through QA successfully.  
![QA](image-5.png)

**Improvement Idea:**  
Simplify overlapping columns (e.g., two *Ready for QA* columns) to reduce confusion, and consider adding an *“In Review”* column before *QA Passed/Done* to capture peer review or final sign-off.