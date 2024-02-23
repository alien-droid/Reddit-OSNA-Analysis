This project is to provide an analysis and visualize a social media graph corresponding to Reddit.

The src/ folder contains files as follows :
 - parser.ipynb 
 - graph_viz.ipynb
 - config.json
 - user_activity.json

The project was written in **Python3** (Version: 3.10.14)

To run this project, please follow the below instructions:
    1. We have used jupyter notebook for development, if not available kindly install using pip (pip install notebook).
    2. To run the project, we need to install the necessary libraries mentioned in the 'requirements.txt'. For ease, you can run using "pip install -r requirements.txt"
    3. The first part of the project is reading and parsing Reddit Data, which is provided in the 'parser.ipynb' which requires Reddit Dev Credentials specified in the 'config.json'.
    4. The 'parser.ipynb' at the end generates a JSON file (used for intermittent storage) (can take about 6-7 minutes), further used for graph visualization. We have provided a sample JSON for usage.
    5. The 'graph_viz.ipynb' file is used for graph visualization. The 'Pyvis library is utilized for visualization and it generates a separate HTML file named 'nx.html' which displays the network graph (takes 1-2 minutes to render the graph). The file also contains the network measures such as closeness centrality, degree distribution as well as page rank.

**Libraries Used:**
NetowrkX, PyVis, PRAW, matplotlib.

This project is part of the Course - OSNA (CS 579)
    
