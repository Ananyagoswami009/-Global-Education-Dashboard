# Global Education Dashboard

## Overview

The **Global Education Dashboard** provides valuable insights into global education accessibility. This interactive Tableau dashboard visualizes trends in school enrollment, government spending on education, and the distribution of educational institutions across the globe. By using maps and charts, it highlights regions with low educational access and guides policymakers, NGOs, and organizations in targeting interventions in underserved areas. 

The dashboard also helps in:
- **Identifying Regional Trends**: Discovering regions where educational access is limited.
- **Supporting Policymakers**: Aiding decision-makers in determining resource allocation.
- **Guiding Infrastructure Development**: Helping plan interventions in underserved areas to improve education equity.
- **Visualizing Educational Reach**: Exploring enrollment rates and overall educational coverage globally.

---

## Features

- **Global School Enrollment**: Visual representation of school enrollment rates across countries.
- **Government Education Spending**: Visualization of how much governments are spending on education.
- **Institutional Distribution**: Maps showing the distribution of educational institutions across the globe.
- **Interactive Filtering**: Filters to explore specific regions, countries, or indicators such as education spending or enrollment rates.
- **Insights for Policymakers and NGOs**: Provides guidance on where to target interventions for improving educational access.

---

## Dataset

The dataset used for this dashboard is named **`world_education_data.csv`**, which contains global education-related data. The dataset includes information on enrollment rates, government spending on education, and the distribution of educational institutions across countries.

### Dataset Columns:
- **Country**: The country name.
- **Region**: The region to which the country belongs (e.g., Africa, Asia, Europe).
- **School Enrollment Rate (%)**: The percentage of children enrolled in primary or secondary school.
- **Government Education Spending (%)**: The percentage of a country's GDP allocated to education.
- **Number of Educational Institutions**: The number of educational institutions in each country.
- **Literacy Rate (%)**: The literacy rate for the population aged 15 and above.
- **GDP per Capita**: The Gross Domestic Product per capita of the country.
- **Population**: The total population of the country.

**Note:** The dataset is structured to allow easy comparison and filtering of key education metrics across countries and regions.

### Example Data:

| Country     | Region    | School Enrollment Rate (%) | Government Education Spending (%) | Number of Educational Institutions | Literacy Rate (%) | GDP per Capita | Population |
|-------------|-----------|----------------------------|----------------------------------|----------------------------------|-------------------|----------------|------------|
| United States | North America | 98.0                       | 5.0                              | 130,000                           | 99.0              | 60,000         | 331,000,000|
| India       | Asia      | 85.0                       | 3.5                              | 1,200,000                         | 74.0              | 1,800          | 1,380,000,000|
| Brazil      | South America | 92.0                       | 6.0                              | 150,000                           | 94.0              | 10,000         | 213,000,000|
| Nigeria     | Africa    | 70.0                       | 2.5                              | 300,000                           | 59.0              | 2,500          | 211,000,000|

---

## Requirements

To use the **Global Education Dashboard**, you will need the following:

- **Tableau Desktop** or **Tableau Public**: To view and interact with the dashboard.
- **CSV Dataset**: `world_education_data.csv` (included in the repository).
- **Web Browser**: To interact with Tableau Public, if shared online.

---

## Installation

### Steps to Set Up the Project Locally:

1. **Download Tableau Desktop**:
   - Visit [Tableau's official website](https://www.tableau.com/products/desktop) to download and install Tableau Desktop.

2. **Clone the Repository**:
   - Clone the repository to your local machine by using the following command:
     ```bash
     git clone https://github.com/yourusername/global-education-dashboard.git
     ```

3. **Open the Tableau Workbook**:
   - Open the `.twb` or `.twbx` file in Tableau Desktop to view and interact with the dashboard.

4. **Load the Dataset**:
   - Ensure the `world_education_data.csv` dataset is loaded correctly into Tableau, or replace the data source if required.

---

## Usage

Once the project is set up, you can:

- **Explore School Enrollment**: View enrollment rates across countries and regions.
- **Analyze Government Spending**: Visualize the education spending in various countries.
- **Examine Institutional Distribution**: See the geographical distribution of educational institutions.
- **Filter Data**: Use the interactive filters to view data specific to certain regions, countries, or metrics.
- **Insights for Decision Makers**: Identify areas with low educational access and explore where to focus resources.

---

## Screenshots

![Dashboard Screenshot](https://github.com/Ananyagoswami009/-Global-Education-Dashboard/blob/main/world%20dashboard.png)  
*Example screenshot of the Global Education Dashboard.*

---

## Contribution

We welcome contributions to improve this dashboard and make it even more useful. If you have ideas for new features, improvements, or bug fixes, feel free to fork the repository and submit a pull request.

To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Tableau**: For providing the platform to create the dashboard.
- **Dataset**: Education-related data sourced from various global organizations, educational reports, and research bodies.
