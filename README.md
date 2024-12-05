# **MTA Subway and DE-HNN Project**

## **Description**

This project combines two assignments:

1. **MTA Subway Analysis**: Leveraging MTA subway ridership data to analyze patterns, such as top stations and routes by ridership.
2. **DE-HNN Reimplementation**: Reimplementing the DE-HNN (Directed Edge Hypergraph Neural Network) model for chip design congestion modeling.

The project uses datasets and tools to explore graph-based models and deep learning techniques in real-world applications.

---

## **Getting Started**

### **Prerequisites**

Ensure you have Python (>=3.8) installed. Required Python libraries include:

- `torch`
- `torch_geometric`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `scikit-learn`

For a complete list, see the [Requirements](#requirements) section.

---

## **Datasets**

### **MTA Subway Data**

- GitHub Repository: [MTA Subway Project](https://github.com/animeshbchowdhury/mta_subway_station/tree/main)
- Data Files: [MTA Data Files](https://drive.google.com/drive/folders/1fV47SWGv5_AFPR_gRfvK1ra1LfSFCgOw)

### **DE-HNN Data**

- GitHub Repository: [DE-HNN Project](https://github.com/YusuLab/chips)
- Data Files: [Chip Design Dataset](https://drive.google.com/file/d/1Scq35gvCQvIMrmthGs7MUhc8c1VZ8ZwN/view)

Download and place the data files in the data folder before running either notebook.

---

## **Installation**

1. Clone the repository:
   ```
   git clone https://github.com/okinahiru/DSC180A-Q1.git
   cd DSC180A-Q1
   ```
2. Create a virtual environment and activate it:
   ```
   python3 -m venv env
   source env/bin/activate
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## **Results**

### **MTA Subway Analysis**

The MTA Subway Analysis provided a deeper understanding into the intricacies of graph's and their role in machine learning.

Visualizations (saved in `/plots/`):

- Graph of subset of ridership data

---

### **DE-HNN Reimplementation**

The DE-HNN (Directed Edge Hypergraph Neural Network) model reimplementation yielded:

- **Model Performance**:
  - Mean Absolute Error (MAE): 2.63

Visualizations (saved in `/plots/`):

- Graph plots utilized in EDA

---

These results showcased my journey through learning and understanding the intricacies of GNN and the DE-HNN model we will be working from in Q2
