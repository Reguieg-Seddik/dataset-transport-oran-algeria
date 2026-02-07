# dataset-transport-oran-algeria
Georeferenced dataset of bus and tram stops and routes for the urban transport network of Oran, Algeria, collected and used for DBSCAN-based clustering and route planning analysis.
# Urban Transport Network Dataset – Oran, Algeria

This repository provides a georeferenced dataset describing the urban public transport network of Oran, Algeria, represented as a graph structure.

The dataset was manually collected, processed, and used for research purposes in the context of urban route planning and network optimization.

## Dataset Description

The dataset is provided in GraphML format and represents the public transport network as a directed graph, where:
- nodes correspond to bus or tram stops,
- edges represent direct connections between consecutive stops along transport lines.

Each node and edge is associated with attributes describing transport lines, stop identifiers, and geographic information.

## File Description

- `grapheBase.graphml`  
  Base transport graph of Oran’s urban network, including bus and tram lines before clustering.  
  The graph contains multiple disconnected cycles corresponding to individual transport lines.

## Data Content

The dataset includes:
- Unique identifiers for transport stops  
- Stop names and line identifiers  
- Geographic coordinates (latitude and longitude)  
- Directed connections between successive stops along each line  

This structure allows the transport network to be directly loaded into graph-processing libraries such as NetworkX.

## Usage

This dataset was used in the following research tasks:
- Modeling the urban transport network as a directed graph  
- Analyzing network connectivity and fragmentation  
- Identifying transfer hubs using a customized DBSCAN clustering approach  
- Performing route planning experiments using Dijkstra’s algorithm  

It supports research in urban mobility, route optimization, clustering-based network analysis, and decision-support systems.

## Associated Publication

This dataset was used in the paper:

**Integrating DBSCAN clustering and Dijkstra’s algorithm for enhanced route planning: a case study of Oran, Algeria**  
Submitted to *RAIRO – Operations Research*.

## Format

- File format: GraphML  
- Compatible with: NetworkX, Gephi, Cytoscape, and other graph analysis tools

## License and Usage

This dataset is provided for academic and research purposes.  
Users are encouraged to cite the associated publication when using this dataset in their work.

## Contact

For questions, clarifications, or additional information, please contact:

**Seddik REGUIEG**  
Docteur en Informatique  
reguieg.seddik@gmail.com
