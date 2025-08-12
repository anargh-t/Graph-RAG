# Graph-RAG

Graph-RAG is a project demonstrating retrieval-augmented generation (RAG) techniques using knowledge graphs and large language models (LLMs). This repository contains Jupyter notebooks that explore how to build, query, and leverage knowledge graphs for enhanced information retrieval and reasoning with LLMs.

## Contents

- **GraphRAG_using_Llama_3_1.ipynb**  
  Demonstrates how to implement Graph-RAG using the Llama 3.1 model. The notebook likely covers:
  - Integrating knowledge graphs with the Llama 3.1 LLM for RAG
  - Sample workflows for querying and augmenting responses with graph-based data

- **Knowledge_Graph_using_LangChain.ipynb**  
  Explains how to build and utilize a knowledge graph with [LangChain](https://github.com/hwchase17/langchain). The notebook may include:
  - Creating a knowledge graph from textual data
  - Querying the graph and connecting results to LLM prompts

## Getting Started

### Prerequisites

- Python 3.8+
- [Jupyter Notebook](https://jupyter.org/install)
- Recommended: Create and activate a virtual environment

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/anargh-t/Graph-RAG.git
   cd Graph-RAG
   ```

2. Install dependencies (if requirements.txt is provided):
   ```bash
   pip install -r requirements.txt
   ```
   Or, manually install:
   ```bash
   pip install jupyter langchain
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the desired notebook to explore the examples.

## Usage

- Run the notebooks cell by cell.
- Modify parameters or code as needed to adapt to your own data or models.
- Review output cells for results and explanations.

## Project Structure

```
Graph-RAG/
│
├── GraphRAG_using_Llama_3_1.ipynb
├── Knowledge_Graph_using_LangChain.ipynb
└── README.md
```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for new features, bug fixes, or suggestions.

## License

[MIT License](LICENSE)

---

*This project is for educational and research purposes. For any questions, please contact the repository maintainer.*
