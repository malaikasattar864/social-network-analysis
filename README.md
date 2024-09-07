Introduction: 

This project provides a Social Network Analysis (SNA) within our class, to understand connections between students and professors. The primary goal is to gain insights into the patterns of interactions, identify prominent nodes, and explore the collaborative dynamics that contribute to the overall social structure within our class through Dijkstra’s Algorithm. The motivation behind this project stems from the recognition that beyond traditional academic frameworks, the relationships and interactions within a university class contribute significantly to the overall learning experience. By delving into the social network that naturally evolves within our academic community, we aim to uncover hidden patterns that may influence the flow of information, collaboration, and academic support. 

 

Methodology: 

Data Collection: 

Data Collection Process: The data collection process was executed through a Google Forms survey distributed among our class fellows. The survey aimed to capture the social interactions and connections within the class, encompassing both students and professors. Participants were asked to provide information on their connections, assigning a numerical value (between 1-10) to represent the strength of their relationships. 

Google Form:  

https://docs.google.com/forms/d/e/1FAIpQLSdjfK61QFN-y120gVppy3fBWguGFHHbB68TVxqjgWt4FBZamw/viewform?usp=send_form 

Variables Captured: Participants were required to input their names and the names of individuals they are acquainted with within the class. 

Connection Strength: To quantify the relationships, respondents assigned a connection strength on a scale of 1 to 10, where 1 indicated a weak connection, and 10 represented a strong connection. 

Ethical Considerations and Privacy Measures: Respecting the privacy and ethical considerations of participants was paramount throughout the data collection process. The survey was designed to be voluntary, and participants were assured of the confidentiality and anonymity of their responses. No personally identifiable information beyond names was collected, and the data obtained was aggregated and anonymized for analysis. 

 

Graph Representation: 

Graph Construction: The social network was represented as a directed graph, where nodes corresponded to both students and professors, and edges represented connections between them. The directed nature of the edges signified the directionality of the connections, acknowledging that a connection from Student A to Student B may not necessarily imply a reciprocal connection. 

Node and Edge Definitions: 

Nodes: Nodes in the graph represent individual members of the university class, encompassing both students and professors. Each node is uniquely identified by the participant's name. 

Edges: Edges between nodes represent the connections reported in the survey. The strength of the connection, as indicated by the numerical values assigned in the survey, was used to determine edge weights. 

 

Implementation: 

Graph Construction: 

Pre-step - Generating Excel Spreadsheet:  

Before commencing the graph construction process, a crucial pre-step involves the extraction of data from the Google Forms survey responses. The raw data, often stored in a Google Sheets spreadsheet, is exported as a structured Excel spreadsheet. This spreadsheet serves as the foundation for constructing the social network graph, ensuring a systematic and organized approach to handling the collected information. 

Excel Sheet: 

https://docs.google.com/spreadsheets/d/154YfYl9NDN2J9_RNOdgVTRvqyMX78cj4rJy-LqpIcDc/edit?usp=sharing 

Graph Construction Process: 

Node Identification: Parse the Excel spreadsheet to identify unique nodes, representing both students and professors. Each node is associated with a unique identifier, usually derived from the participant's name. 

Edge Establishment: Extract connection information from the spreadsheet to establish edges between nodes. For each reported connection, create a directed edge, considering the directionality based on the participant's input. 

Edge Weight Assignment: Utilize the numerical values provided in the survey responses to assign weights to edges, reflecting the strength of connections. These weights will be crucial for subsequent analyses, including the application of Dijkstra's algorithm. 

Directed Graph Representation: Model the social network as a directed graph, where nodes represent individuals and edges signify social connections. Ensure that the graph construction captures the nuances of social ties within the university class. 

Dijkstra's Algorithm Application: 

  

Graph Initialization: Load the constructed graph, complete with nodes, edges, and edge weights, into the algorithm. This involves converting the Excel spreadsheet data into a format compatible with graph manipulation libraries. 

Node Selection: Choose a starting node within the social network as the focal point for Dijkstra's algorithm. This could be a specific student's node, initiating the exploration of shortest paths from this origin. 

Application of Dijkstra's Algorithm: Execute Dijkstra's algorithm on the prepared graph to calculate the shortest paths and distances from the selected starting node to all other nodes. Leverage the edge weights to incorporate connection strengths into the analysis. 

By integrating these pre-steps and considerations into the graph construction and Dijkstra's algorithm application processes, the social network analysis is not only grounded in the real-world data obtained from Google Forms but also adaptable to the evolving dynamics of the university class's social connections. 

  

Discussion: 

Interactions and Collaboration: 

Patterns of Interactions: The analysis revealed intricate patterns of interactions within the university class, highlighting a rich tapestry of academic and social collaborations. Highly connected students acted as hubs, facilitating the flow of information and fostering collaborative endeavors. The multiple shortest paths between individuals highlighted the resilience and flexibility of the social network, accommodating diverse communication channels. 

Impact on Academic and Social Dynamics: The identified patterns of interactions have profound implications for both academic and social dynamics. Collaborative clusters contribute to a vibrant academic atmosphere, where students exchange knowledge and support each other. The flexibility in communication channels ensures a robust network that can adapt to changing circumstances, fostering a dynamic social environment within the university class. 

Professor-Student Connections: 

Exploration of Connections: The connections between students and professors underscored the integral role faculty members play in the social network. Professors identified influential nodes as connectors, bridging the gap between students and contributing to a more interconnected class structure. The presence of direct connections between students and professors emphasized the potential for mentorship and academic guidance. 

Contribution to Network Structure: Professor-student connections significantly contribute to the overall network structure. The active engagement of professors influences information flow, providing students with valuable insights and guidance. Such connections create a network that is not only student-centric but also incorporates the expertise and influence of faculty members, contributing to a well-rounded academic community. 

 

Conclusion: 

In summary, this social network analysis within our university class unveiled a tapestry of connections, interactions, and collaborations that form the backbone of our academic community. By applying graph theory and Dijkstra's algorithm to the data collected through Google Forms, we gained valuable insights into the structure and dynamics of the social network. 

  

Key Findings: 

Interactions and Collaboration: The analysis illuminated patterns of collaboration, displaying the significance of highly connected students as hubs in information exchange. The flexibility of communication channels and the presence of diverse shortest paths highlighted the resilience of the social network. 

Professor-Student Connections: Professors emerged as influential connectors, actively contributing to the overall network structure. Direct connections between students and professors emphasized the potential for mentorship and academic guidance, enriching the academic experience. 

Network Metrics: The application of network metrics, including centrality measures and clustering coefficients, provided quantitative insights, revealing influential nodes and cohesive clusters within the social network. 

 

Acknowledgments: 

We thank the individuals and organizations who have contributed to the successful completion of this social network analysis project within our university class. Their support and collaboration have been invaluable in bringing this endeavor to fruition. I extend my heartfelt thanks to all the classmates who participated in the Google Forms survey and shared valuable insights into their connections within the university class. Your active engagement formed the foundation of this project. 
