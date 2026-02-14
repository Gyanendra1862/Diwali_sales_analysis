{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "7b41ac41-6966-47d6-96e9-a4c4e679cd61",
   "metadata": {},
   "source": [
    "#  Diwali Sales Analysis using Python\n",
    "\n",
    "##  Project Overview\n",
    "This project performs Exploratory Data Analysis (EDA) on Diwali sales data to understand customer purchasing behavior during the festive season. The analysis helps identify high-value customers, top-performing product categories, and important business insights for better decision-making.\n",
    "\n",
    "---\n",
    "\n",
    "##  Objectives\n",
    "- Analyze customer demographics and purchasing patterns\n",
    "- Identify high-revenue states and product categories\n",
    "- Perform customer segmentation\n",
    "- Conduct hypothesis testing using statistical analysis\n",
    "- Generate business insights from data\n",
    "\n",
    "---\n",
    "\n",
    "##  Technologies Used\n",
    "- Python\n",
    "- Pandas\n",
    "- NumPy\n",
    "- Matplotlib\n",
    "- Seaborn\n",
    "- SciPy\n",
    "- Jupyter Notebook\n",
    "\n",
    "---\n",
    "\n",
    "##  Key Insights\n",
    "- High-value customers contribute significantly to total revenue.\n",
    "- Customers aged **26–35 years** show strong purchasing behavior.\n",
    "- **Food and Clothing** categories generate maximum sales.\n",
    "- Marital status does not significantly impact spending behavior.\n",
    "\n",
    "---\n",
    "\n",
    "##  Visualizations\n",
    "\n",
    "### Sales by Gender\n",
    "![Sales by Gender](images/gender%20vs%20amount.png)\n",
    "\n",
    "### Orders by State\n",
    "![State Orders](images/state%20vs%20orders.png)\n",
    "\n",
    "### Age Group Distribution\n",
    "![Age Group](images/age_grp%20vs%20count.png)\n",
    "\n",
    "### Product Category Analysis\n",
    "![Product Category](images/product%20category%20vs%20quantity.png)\n",
    "\n",
    "---\n",
    "\n",
    "##  Hypothesis Testing\n",
    "An independent t-test was conducted to evaluate whether marital status affects spending behavior.\n",
    "\n",
    "**Result:**  \n",
    "No statistically significant difference was found between married and unmarried customers.\n",
    "\n",
    "---\n",
    "\n",
    "##  Business Recommendations\n",
    "- Focus marketing strategies on high-value customers.\n",
    "- Increase inventory for top-selling product categories.\n",
    "- Target high-performing states during festive seasons.\n",
    "- Use demographic insights for personalized promotions.\n",
    "\n",
    "---\n",
    "\n",
    "##  Project Structure\n"
   ]
  },
  {
   "cell_type": "raw",
   "id": "57be48d9-f4c5-4511-9384-972b7a99ffa9",
   "metadata": {},
   "source": [
    "Diwali_sales_analysis/\n",
    "│\n",
    "├── Diwali_sales_Analysis.ipynb\n",
    "├── Diwali Sales Data.csv\n",
    "├── images/\n",
    "└── README.md"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "1690cd8c-e2ef-48e6-b4da-fad770d5eb45",
   "metadata": {},
   "source": [
    "\n",
    "---\n",
    "\n",
    "##  Author\n",
    "**Gyanendra Kumar**\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "8a35750b-893b-44ec-bc79-f53526035864",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.14.0"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
