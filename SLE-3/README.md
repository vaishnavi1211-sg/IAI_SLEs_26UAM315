SLE-3: Architectural Design using Full C4 Model
BFS & DFS Graph Search System
Name: Vaishnavi Sudhir Ghodake
PRN: 26UAM315
Division: A
Course: 02AML204 – Introduction to Artificial Intelligence  
1. Project Description
This SLE-3 presents the architecture of the BFS & DFS Graph Search System using the complete C4 Model.
The system continues the BFS and DFS implementation and empirical performance analysis completed in SLE-2. It takes a graph, start node, and goal node as input, performs BFS or DFS, and records the search path, nodes expanded, and execution time. Py-Spy is used for profiling the search execution.
2. C4 Model Levels
This submission includes all four required C4 levels:
Level 1 – System Context
Shows the BFS & DFS Graph Search System, the user, and the external performance/profiling tool.
Diagram: Level_1_Context_Diagram.png
Level 2 – Container
Shows the main logical building blocks of the system:
1. Input Module
2. Search Engine
3. Result & Metrics Module
4. Performance & Profiling Module
5. Output
Diagram: Level_2_Container_Diagram.png
Level 3 – Component
Focuses on the Search Engine container and shows its logical components:
- Search Controller
- BFS Search Component
- DFS Search Component
- Search State Manager
- Goal Test Component
Diagram: Level_3_Component_Diagram.png
Level 4 – Code
Maps the architecture to the actual Python files used in SLE-2:
- bfs_dfs.py – graph definition and BFS/DFS search functions
- benchmark.py – best, average, and worst-case benchmarking
- profile_search.py – repeated search execution for Py-Spy profiling
- profile.svg – generated profiling output
- readme.md and contribution.md – project documentation and contribution record
Diagram: Level_4_Code_Overview.png
3. Design Decisions
- BFS and DFS are separated because BFS uses a queue (FIFO), while DFS uses a stack (LIFO).
- Visited-node tracking avoids repeated exploration.
- The same graph and test conditions are used for a fair comparison.
- Benchmarking and profiling are separated from the core search logic.
4. AI Contribution
ChatGPT was used to understand the C4 model, organize the existing BFS/DFS work into the four architectural levels, draft explanations, and assist with diagram/report preparation.
The student reviewed the SLE-2 implementation, selected the architecture, verified the code structure, and prepared the final submission.
5. Submission Files
- Level_1_Context_Diagram.png
- Level_2_Container_Diagram.png
- Level_3_Component_Diagram.png
- Level_4_Code_Overview.png
- SLE3_26UAM315_Vaishnavi_Ghodake_FINAL_VERIFIED.docx
6. Conclusion
The complete C4 model provides a clear view of the BFS & DFS Graph Search System from user interaction to containers, internal components, and Python code. The architecture connects directly to the work completed in SLE-2.
