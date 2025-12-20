# ⚡ AMP-Optimized-BOD
- 🤝 Welcome to the AMP-Optimized-BOD repository! This collection of Alteryx macros is tailored to optimize and streamline workflows by leveraging the AMP (Alteryx Multi-Processing) engine while targeting the Block Until Done (BOD) processes.

## 🧰 Included Macros
- 📥 Input Group
- 📤 Output Group

### 📥 Input Group (Standard Macro)

**📝 Description:**
- Input Group is an Alteryx Standard Macro designed to assign a selected group, modifying both the data and metadata within the stream.

### 📤 Output Group (Standard Macro)

**📝 Description:**
- Output Group, another Alteryx Standard Macro, functions by filtering in a chosen group from a data stream that contains multiple different groups.
- These two macros complement each other in workflow design.
- The Input Group assigns a group, facilitating data modification, and metadata alteration. Subsequently, the Output Group filters the chosen group, enabling efficient control over data streams containing multiple groups.

## 🔀 Workflow Synergy
- The synergy between these macros is instrumental.
- By using the Input Group to designate groups and employing operations like union and classic Block Until Done (BOD), the workflow ensures the proper order of operations.
- When creating multiple groups with the Input Group and segmenting the data stream with BOD, the Output Group becomes pivotal. It filters the data stream, allowing precise control over the output order, even amidst multiple disparate data streams.

## 🚀 Getting Started
- Explore the macros provided in this repository to harness the power of AMP optimization in Alteryx workflows. Utilize the Input Group and Output Group macros to efficiently assign, filter, and control data streams, enhancing the speed and order of data processing operations.

## 🤝 Contributions and Collaboration
- Contributions, suggestions, and enhancements from the community are welcome! Let's collaborate to further refine and expand the capabilities of these macros for optimized Alteryx workflows.
- Feel free to explore, experiment, and contribute to the AMP-Optimized-BOD repository to enhance Alteryx workflows with AMP optimization.

---

*Note: The description provided here is a high-level overview. Refer to individual macro documentation for detailed usage instructions.*
