# GMAP2025
Supporting materials for the paper "Bridging the Rift: A Critical Perspective on the Divergence in Group Recommender Systems" submitted to GMAP@UMAP2025

The repository contains:
- JSONs with processed data on the surveyed papers in the **graphsDef** folder. In the JSON structure, papers are represented as **nodes** with basic identification information including, whether the approach belong to the profile or results aggregation family, or none of those. Inter-paper relationship is represented as **edges** of a given type and importance.
- **Visualizations** of the processed data via force-directed layout (.html files). We separately depict "is a baseline", "sharing baselines", and "sharing datasets" relations.

Note that due to CORS policy, the website needs to run through some webserver. The easiest solution is to run a local webserver (from the websites' homepage run "python  -m http.server 8000") and then access the visualizations from a browser as e.g. "http://localhost:8000/basic_graph_baselines.html". Alternatively, one can upload the content of the repository to some webserver.
