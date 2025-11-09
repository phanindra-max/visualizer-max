## 🫏 Interactive Data Visualization Repository

This repository contains Python code and interactive visualizations created using **Plotly**, **PyVis**, and **NetworkX**. The project demonstrates various visualization techniques for representing multi-dimensional data, hierarchical relationships, and skill taxonomies.

### ⚡ [View Live Interactive Demos](https://phanindra-max.github.io/visualizer-max/) ⚡

---

## 📊 Visualizations Overview

### 3D Scatter Plot - Job Skills Clustering
An interactive 3D scatter plot that visualizes job skills clusters across three dimensions: **Knowledge**, **Task Ability**, and **Level**. The visualization uses color-coded data points to distinguish between different skill sources (Job Description, Education, Workforce Experience) and variable sizing to represent skill proficiency levels.

**Features:**
- Interactive 3D rotation and zoom
- Color-coded clusters for different job-related categories
- Dynamic sizing based on skill level
- Hover tooltips with detailed information

<img src='3d_scatter_rotation.gif' alt='3D Scatter Plot Animation showing job skills clusters rotating in 3D space'/>

---

### Hierarchical Network Graphs - Skill Taxonomy
Multiple variations of hierarchical network visualizations that map the relationships between **Skills**, **Tasks**, and **Knowledge domains**. These graphs show how different skills relate to each other, what tasks they enable, and what knowledge is required.

**Graph Types:**
1. **Non-overlapping Hierarchical Layout** - Clear separation of node levels with defined hierarchical structure
2. **Condensed Circular Layout** - Compact visualization with fluid node positioning and spring-based physics

**Relationship Types:**
- Skill → Skill (Related to)
- Skill → Task (Performs)
- Skill → Knowledge (Requires)

![Heirarchical Plot non-overlapping](https://github.com/user-attachments/assets/3bbe656c-e019-4c67-b06a-f325ce638a03)
*Non-overlapping hierarchical plot showing clear skill taxonomy levels and relationships*

![Condensed Heirarchical plot](https://github.com/user-attachments/assets/356b60f5-cba9-4762-9ae1-a99721f8871a)
*Condensed circular layout with interactive nodes and dynamic edge rendering*

---

## 🛠️ Technologies Used

- **Plotly** - Interactive 3D scatter plots and data visualization
- **PyVis** - Network graph visualization with physics simulation
- **NetworkX** - Graph data structure and analysis
- **Pandas & NumPy** - Data manipulation and generation

---

## 📝 Note

This project uses randomly generated or mock data points to create quick, compelling visualizations for presentations, research pitches, and demonstration purposes. The visualization techniques can be adapted to real-world datasets.

