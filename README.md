# ECE227 Graph Networking Final Project
### Overview
In this project we looked to analyze the following graph networks: Airport routes, Links to other subreddits in subreddit posts, and young adult migration patterns.

### Datasets
The datasets can be found here:
- Airport routes: https://www.kaggle.com/datasets/alenreuel/airport-network
- Subreddit links: https://snap.stanford.edu/data/soc-RedditHyperlinks.html
- Young adult migration: https://www.kaggle.com/datasets/sujaykapadnis/young-adult-migration-patterns?select=od.csv

### Setup Instructions
1. Open VS Code and run ```git clone https://github.com/graph-networking-project/network-analysis.git``` in the terminal to clone the repository on your own computer. Run ```cd network-analysis``` to move into the repository folder.
2. Create a new ```data``` folder in the home directory of the repository. Download the datasets from the above links and move them into the new ```data``` folder. Rename the reddit and migrations files accordingly: ```soc-redditHyperlinks-body.tsv``` to ```reddit_links.tsv``` and ```od.csv``` to ```migration_network.csv```.
3. Run ```conda create -n my_env python=3.10``` to create a new conda environment and avoid previous libary dependencies. Then activate the envornment with ```conda activate my_env```.
4. Install the additional libraries in the new environment: ```conda install networkx matplotlib pandas numpy```.
5. Open the .ipynb files and click Run All at the top of the file.
