# kapi-tree

kapi-tree is a web-based visualization tool that uses the **Cytoscape.js** library to display the hierarchical structure of a family trees of an organization. It parses data from a Google Sheets CSV and arranges nodes based on pledge class and family lineage.

## Live Webpage

Check out the live webpage [here](https://dtsivkovski.github.io/kapi-tree/).

## Libraries and Tools Utilized

- **Cytoscape.js**: A graph theory library for visualization and analysis.
- **Cytoscape Elk Layout**: A Cytoscape.js extension that uses the Elk layout algorithm to arrange nodes in a hierarchical structure.
- **PapaParse**: A fast CSV parser to load and parse data from Google Sheets.
- **Google Sheets**: Used as the data source to fetch chapter member information.

## How It Works

1. **Data Source**: Data is fetched from a public Google Sheet in CSV format using **PapaParse**.
2. **Cytoscape.js**: Nodes and edges are created based on the relationships in the data (e.g., parent-child relationships).
3. **Elk Layout**: The **Elk** layout algorithm is used to arrange nodes in a hierarchical structure.

## Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/kapi-tree.git
   cd kapi-tree
   ```

2. Open the `index.html` file in your browser.
