# KruskalWebFormApp

🚀 **KruskalWebFormApp** is a powerful and interactive **C# Windows Forms application** designed to visually demonstrate **Kruskal's Algorithm** for finding the **Minimum Spanning Tree (MST)** of a graph. It provides an intuitive canvas where users can dynamically add, modify, and visualize nodes and edges — either manually or through file imports.

---

## 🧠 Key Features

- 🖱️ **Interactive Node Placement**  
  Add nodes by clicking anywhere on the canvas — fully customizable positioning.

- 🔄 **Draggable Nodes**  
  Move nodes around after placing them by clicking and dragging to adjust the graph layout.

- 📥 **Import from Excel**  
  Load nodes and edges from an Excel file for batch input (helpful for large datasets or real-world graphs).

- 🗺️ **Map Integration**  
  Import a map image (e.g., a city layout) as the canvas background. Nodes can be placed directly over the map to simulate real-world locations.

- 🧮 **Kruskal's Algorithm Visualization**  
  Automatically compute the Minimum Spanning Tree (MST) and highlight it on the graph.

- ❌ **Rejected Edges Display**  
  Once the MST is computed, non-MST (rejected) edges are hidden — with the option to bring them back using the **Show All** toggle.

- 🧭 **Map Toggle Button**  
  Turn the background map view on or off anytime for clearer graph inspection.

---

## 📸 Screenshot

![App Screenshot](screenshots/kruskal_app.png)

---

## 📦 Tech Stack

- **Language:** C#  
- **Framework:** .NET (Windows Forms)  
- **Graphics:** GDI+  
- **IDE:** Visual Studio  
- **Data Support:** Excel Import (via `OpenFileDialog`)

---

## 📂 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ABasit92/KruskalWebFormApp.git
