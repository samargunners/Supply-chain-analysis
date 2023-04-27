# Supply Chain Analysis

This project is a data analysis of a supply chain dataset using Python and Plotly. It helps to uncover insights such as sales by product type, total revenue by shipping carrier, average lead time and manufacturing costs, and defect rates by product type and transportation mode.

## Installation and Setup

1. Clone the repository:
git clone https://github.com/samargunners/supply-chain-analysis.git

2. Change the working directory:
cd supply-chain-analysis

3. Create a virtual environment:
python3 -m venv venv

4. Activate the virtual environment:

- On macOS and Linux:

  ```
  source venv/bin/activate
  ```

- On Windows:

  ```
  .\venv\Scripts\activate
  ```

5. Install the required packages:
pip install -r requirements.txt

Now, the project is set up, and you can run the scripts or notebooks.

## Visualizations

Various visualizations are created using Plotly to help explore and analyze the data. The visualizations include:

- Pie charts to display sales by product type and cost distribution by transportation mode
- Bar charts to show sales, revenue, manufacturing costs, and defect rates by product type
- Line charts to visualize revenue and stock levels by SKU (Stock Keeping Unit)
- Bar charts to show order quantities by SKU and shipping costs by carrier

## Questions & Answers

Throughout the analysis, several key questions are addressed, such as:

- Which product types generate the most revenue and sales?
- How do different shipping carriers compare in terms of total revenue generated?
- What are the average lead times and manufacturing costs for each product type?
- How do stock levels and order quantities vary across different SKUs?
- What are the shipping costs associated with each carrier?
- How do defect rates vary by product type and transportation mode?

## Conclusion

Based on the results obtained from the data analysis, we can draw the following conclusions:

### Product Categories:
The analysis of the dataset shows that haircare products have a higher defect rate compared to other product types. This suggests that there may be specific issues related to the production or handling of haircare products that need to be addressed to reduce the defect rate.
### Transportation Modes: 
The examination of defect rates by transportation mode reveals that some modes contribute to higher defect rates than others. By identifying the transportation modes with the highest defect rates, we can focus on improving the logistics and handling processes for these modes to minimize defects during transportation.

To further improve the supply chain efficiency and reduce the defect rates, it is recommended to:

1. Investigate the specific reasons behind the high defect rate in haircare products. This can involve a detailed examination of the production process, raw materials, packaging, and storage conditions.
2. Assess the transportation modes with higher defect rates and identify areas of improvement, such as better handling practices, packaging, and route optimizations.
3. Regularly monitor and analyze the defect rates and other relevant supply chain metrics to ensure continuous improvement and early identification of potential issues.

By addressing the identified issues and implementing the suggested improvements, the company can minimize product defects, reduce costs, and enhance customer satisfaction.
