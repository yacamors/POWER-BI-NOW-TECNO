Data Analysis Repository
This repository contains data analysis projects and scripts primarily focused on extracting insights from business datasets. Below, you'll find details on how to export datasets from an Excel database, along with transformations applied using Power Query Editor.

Exporting Data from Excel Database
The datasets were extracted from an Excel database where key measures were defined as follows:

Margen = SUM(Tabla1[Utilidad]) / SUM(Tabla1[Ingresos])
Total ingresos = SUM('Tabla Datos'[Ingresos])
Utilidad = Tabla1[Ingresos] - Tabla1[Gastos]
These measures were calculated to analyze profitability and revenue across different business segments within the dataset.

Transformations in Power Query Editor
In the Power Query Editor, several transformations were applied to enhance data usability:

Periodos Query:

Divided the period query to better manage time-based data.
Added two columns: one for Q1 (where 'Q' was replaced by 'T' denoting quarters) and another for the year.
Region Column:

Split into countries and continents for more granular geographical analysis.
These transformations were crucial for structuring the data to support deeper analytical insights and to facilitate reporting on a quarterly and yearly basis across various regions.

Usage
You can utilize these scripts and datasets to:

Perform further analysis on profitability margins and revenue trends.
Explore geographical patterns in sales and operational performance.
Customize and extend analyses as per specific business needs.

For any questions or collaboration opportunities, please reach out via [ycamors@gmail.com; https://www.linkedin.com/public-profile/settings?trk=d_flagship3_profile_self_view_public_profile
Joined l].

Happy analyzing!
