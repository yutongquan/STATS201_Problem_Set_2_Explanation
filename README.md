# New Visualization on Blockchain Decentralization: 2D Histogram Contour Plots
## Project information
- **Author**: Yutong Quan, Political Economy (Economics), Class of 2024, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 (Machine Learning for Explanation Section) for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: First, I would like to express my deepest gratitude to Prof. Luyao Zhang for her generous and inspiring instrutions on machine learning methods for data explanation. Then, I am also thankful to Prof. Luyao Zhang, Xinshi Ma, and Yulin Liu for their innovative research on [Blockchain Decentralization](https://arxiv.org/abs/2205.04256) and the data source they provided. 
- **Project Summary**: Based on the research on [Blockchain Decentralization](https://arxiv.org/abs/2205.04256) by Luyao Zhang, Xinshi Ma, and Yulin Liu, this project aims to generate a new visualization for the tokens' decentralization index of "AAVE", "COMP", and "LUSD". We used the Python Plotly to generate 2D Histogram Contour plots for the 30-day moving average of each token to show the dencity of the decentralization index.

## Table of Contents
- [data](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/tree/main/data)
- [code](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/tree/main/code)
- [spotlight](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/tree/main/spotlight)

## Data
- Data Source: https://github.com/SciEcon/SoK_Blockchain_Decentralization/tree/main/Data_TokenIndex
- [Queried Data](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/tree/main/data/Queried_Data)
- [Processed Data](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/tree/main/data/Processed_Data)

## Code
- [Query Data](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/blob/main/code/Query_Data.ipynb)
- [Process Data](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/blob/main/code/Process_Data.ipynb)
- [Analyze Data](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/blob/main/code/Analyze_Data.ipynb)

## Spotlight

![AAVE](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/blob/main/spotlight/figure%201.png)

*Figure No.1. Source: [SoK: Blockchain Decentralization](https://github.com/SciEcon/SoK_Blockchain_Decentralization/), created by [Plotly](https://plotly.com/python/)*

Figure No.1 represents the dencity of AAVE token's 30-day moving average of the decentralization index. X-axis shows the dates from Oct, 2020 to Jan, 2023. Y-axis shows the 30-day moving average of decentralization index. The legend shows that the average has a higher density when the color is close to yellow and it has the lower density when the color is close to purple. We can learn from the figure that on Nov.14, 2021, when the SMA30 = 250, it has the highest density of 62.

![COMP](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/blob/main/spotlight/figure%202.png)

*Figure No.2. Source: [SoK: Blockchain Decentralization](https://github.com/SciEcon/SoK_Blockchain_Decentralization/), created by [Plotly](https://plotly.com/python/)*

Figure No.2 represents the dencity of the COMP token's 30-day moving average of the decentralization index. X-axis shows the dates from Jan, 2020 to Jan, 2023. Y-axis shows the 30-day moving average of decentralization index. The legend shows that the average has a higher density when the color is close to yellow and it has the lower density when the color is close to purple. We can learn from the figure that on Mar.30, 2022, when the SMA30 = 75, it has the highest density of 106.

![LUSD](https://github.com/yutongquan/STATS201_Problem_Set_2_Explanation/blob/main/spotlight/figure%203.png)

*Figure No.3. Source: [SoK: Blockchain Decentralization](https://github.com/SciEcon/SoK_Blockchain_Decentralization/), created by [Plotly](https://plotly.com/python/)*

Figure No.3 represents the dencity of the LUSD token's 30-day moving average of the decentralization index. X-axis shows the dates from Jan, 2020 to Jan, 2023. Y-axis shows the 30-day moving average of decentralization index. The legend shows that the average has a higher density when the color is close to yellow and it has the lower density when the color is close to purple. We can learn from the figure that on Aug.16, 2021, when the SMA30 = 50, it has the highest density of 76.

## References

### Data Source
[SoK_Blockchain_Decentralization/Data_TokenIndex](https://github.com/SciEcon/SoK_Blockchain_Decentralization/tree/main/Data_TokenIndex)
### Code Source
[SoK_Blockchain_Decentralization/code/Top_DeFi_Decentralization_Visualizations.ipynb](https://github.com/SciEcon/SoK_Blockchain_Decentralization/blob/main/code/Top_DeFi_Decentralization_Visualizations.ipynb)
### Articles
[SoK: Blockchain Decentralization](https://arxiv.org/abs/2205.04256)
### Literature
Zhang, Luyao, Xinshi Ma, and Yulin Liu. 2022. “SoK: Blockchain Decentralization.” ArXiv:2205.04256 [Cs, Econ, Q-Fin], May. https://arxiv.org/abs/2205.04256.
