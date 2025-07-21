# KruskalWebFormApp

🚀 **KruskalWebFormApp** is an interactive and intuitive **C# Windows Forms application** that visualizes **Kruskal's Algorithm** for computing the **Minimum Spanning Tree (MST)** of a **weighted graph**. Users can dynamically create, manipulate, import, and export graph structures with a focus on real-world visual clarity and usability.

---

## 🧠 Key Features

- 🖱️ **Interactive Node Placement**  
  Click anywhere on the canvas to place custom-positioned nodes.

- 🔄 **Draggable Nodes**  
  Move existing nodes around the canvas by clicking and dragging for better layout management.

- 📊 **Weighted Graph Support**  
  Add edges between nodes with custom weights, allowing for accurate MST computation.

- 📥 **Excel Import Support**  
  Import nodes and edges from an Excel file — perfect for large data sets or structured inputs.

- 🗺️ **Map Integration**  
  Import map images (e.g., city layouts) and place nodes directly over real-world areas. Great for geography-based MST problems.

- 🧮 **Kruskal's Algorithm Visualization**  
  Automatically calculate and visually render the MST using Kruskal's algorithm.

- ❌ **Rejected Edge Hiding**  
  After MST computation, non-MST edges are hidden to focus on the final spanning tree. A **Show All** button allows toggling them back.

- 🧭 **Map Toggle Option**  
  Easily switch the background map on/off for clearer graph visualization.

- 🖼️ **Export Graph as Image**  
  Export the current canvas view (including graph and map, if enabled) as an image file for reports, documentation, or presentations.

---

## 📸 Screenshot

![App Screenshot](screenshots/kruskal_app.png)

---

## ⚙️ Tech Stack

- **Language:** C#  
- **Framework:** .NET (Windows Forms)  
- **Graphics:** GDI+  
- **IDE:** Visual Studio  
- **Data Import:** Excel (via `OpenFileDialog`)  
- **Image Export:** Bitmap rendering

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ABasit92/KruskalWebFormApp.git
