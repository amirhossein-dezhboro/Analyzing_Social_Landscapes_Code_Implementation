# Analyzing Social Landscapes: Visualizing the Key Elements of Social Media Dynamics

[![DOI](https://zenodo.org/badge/996174407.svg)](https://doi.org/10.5281/zenodo.15933759)

**Authors:** Amirhossein Dezhboro, Pouria Babvey, Carlo Lipizzi, Jose Emmanuel Ramirez-Marquez  
**Affiliation:** Stevens Institute of Technology  
**Publication:** Journal of LaTeX Class Files, Vol. 14, No. 8, 2025  
**DOI:** [10.5281/zenodo.15933759](https://doi.org/10.5281/zenodo.15933759)

## Abstract

This repository contains the complete implementation for the paper "Analyzing Social Landscapes: Visualizing the Key Elements of Social Media Dynamics." We introduce a methodology to analyze social structure through social landscapes using two comprehensive approaches: Galaxy visualizations for content analysis and Discourse Trajectory Inference (DTI) for mapping socio-political spectrums. This represents the first adaptation of pseudo-time analysis from bioinformatics to social media research.

## Keywords

social media analysis, discourse trajectory inference, galaxy visualization, social landscapes, network analysis, computational social science, pseudo-time analysis, node2vec, D3.js, content-aware visualization


## Features

- **Galaxy Visualization**: D3.js-based interactive visualizations for analyzing conversation networks
- **Discourse Trajectory Inference (DTI)**: First adaptation of pseudo-time analysis from bioinformatics to social media analysis
- **Content-Aware Analysis**: NLP integration for sentiment, topic, and stance detection
- **Leanness Metric**: Novel quality measure for conversation assessment

## Repository Structure

```
├── DiscourseTrajectoryMapping.ipynb  # DTI implementation
├── index.html                        # Galaxy visualization interface
├── index.js                          # Main JavaScript logic
├── inspector.css                     # Styling for visualizations
├── ngraph006.json                    # Sample network data
├── package.json                      # Dependencies
├── runtime.js                        # Runtime configuration
├── subgraph_3.json                   # Sample subgraph data
├── subgraph_4.json                   # Sample subgraph data
└── subgraph_5.json                   # Sample subgraph data
```

## Installation and Usage

### Requirements

- Python 3.7+
- Jupyter Notebook
- Node.js (for D3.js visualizations)
- Required Python packages (see `requirements.txt`)

### Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/amirhossein-dezhboro/Analyzing_Social_Landscapes_Paper.git
   cd Analyzing_Social_Landscapes_Paper
   ```

2. **Galaxy Visualization**:
   ```bash
   # Open index.html in a web browser
   # Or serve with a local server:
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Discourse Trajectory Inference**:
   ```bash
   # Install required packages
   pip install -r requirements.txt
   
   # Run the Jupyter notebook
   jupyter notebook DiscourseTrajectoryMapping.ipynb
   ```

## Data Requirements

Due to privacy considerations and platform terms of service restrictions, the original Twitter dataset cannot be shared. However, the code is designed to work with standard social media data formats.

### Expected Data Format

Your data should include:
- **For Galaxy Analysis**: Tweet networks with reply relationships
- **For DTI Analysis**: User following networks and hashtag usage data

### Data Collection Guidelines

1. Use Twitter API v2 or similar platforms
2. Ensure compliance with platform terms of service
3. Follow ethical guidelines for social media research
4. Consider user privacy and data protection regulations

## Methodology

### Galaxy Visualization
- Creates conversation networks from tweet threads
- Applies force-directed layout for visualization
- Supports content-aware analysis (sentiment, topic, stance)
- Implements leanness metric for quality assessment

### Discourse Trajectory Inference (DTI)
- Adapts pseudo-time analysis from bioinformatics
- Maps users along continuous ideological spectrums
- Combines content similarity and network structure
- Uses Node2Vec embeddings and UMAP dimensionality reduction

## Key Contributions

1. **12 Key Elements Framework**: Comprehensive taxonomy for social landscape analysis
2. **Galaxy-DTI Integration**: Novel dual approach combining content and network analysis
3. **First DTI Application**: Pioneering use of pseudo-time analysis in social media research
4. **Leanness Metric**: Quality measure specifically designed for conversation networks

## Citation

If you use this code in your research, please cite:

```bibtex
@article{dezhboro2025analyzing,
  title={Analyzing Social Landscapes: Visualizing the Key Elements of Social Media Dynamics},
  author={Dezhboro, Amirhossein and Babvey, Pouria and Lipizzi, Carlo and Ramirez-Marquez, Jose Emmanuel},
  journal={TBD}
}

@software{dezhboro2025code,
  author = {Dezhboro, Amirhossein and Babvey, Pouria and Lipizzi, Carlo and Ramirez-Marquez, Jose Emmanuel},
  title = {Analyzing Social Landscapes: Code Implementation},
  url = {https://github.com/amirhossein-dezhboro/Analyzing_Social_Landscapes_Paper},
  doi = {10.5281/zenodo.15933760},
  year = {2025}
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- **Amirhossein Dezhboro** - Stevens Institute of Technology - [ORCID](https://orcid.org/0000-0002-7141-5743)
- **Pouria Babvey** - Stevens Institute of Technology - [ORCID](https://orcid.org/0000-0003-1719-3235)
- **Carlo Lipizzi** - Stevens Institute of Technology - [ORCID](https://orcid.org/0000-0001-7888-3382)
- **Jose Emmanuel Ramirez-Marquez** - Stevens Institute of Technology - [ORCID](https://orcid.org/0000-0002-0965-1446)

## Acknowledgments

- Stevens Institute of Technology, School of Engineering and Science
- The research community for feedback and collaboration

## Contact

For questions or collaboration inquiries, please contact:
- Amirhossein Dezhboro: adezhbor@stevens.edu

## Related Work

For more details on the methodology and applications, see our comprehensive paper:
> A. Dezhboro, P. Babvey, C. Lipizzi, and J. E. Ramirez-Marquez, "Analyzing Social Landscapes: Visualizing the Key Elements of Social Media Dynamics," TBD
