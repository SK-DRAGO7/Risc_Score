
# CSPM Risk Scorer PoC

A heuristic risk scorer for cloud assets leveraging MITRE ATT&CK mappings and tags to evaluate and score risks. This tool helps in identifying, prioritizing, and mitigating potential vulnerabilities within cloud environments.

## Key Features
- **MITRE ATT&CK Mappings**: Integration with the globally-recognized framework to standardize threat assessment.
- **Tag-Based Scoring**: Contextual risk scoring based on predefined tags, allowing for detailed analysis.
- **Heuristic Analysis**: Uses heuristic methods to evaluate cloud configurations for potential security risks.

## Benefits
- **Risk Prioritization**: Score-based prioritization aids in focusing on the most critical vulnerabilities.
- **Contextual Insights**: Provides a nuanced understanding of security postures through contextual tagging and analysis.
- **Integration with Existing Frameworks**: Standardized approach compatible with organizations already using MITRE ATT&CK.

## Usage
1. **Installation**: Clone the repository and follow setup instructions in the README file.
2. **Configuration**: Use the synthetic data or modeul your own cloud assets to appropriate MITRE ATT&CK techniques and define scoring heuristics.
3. **Running the Tool**: Execute the tool to generate and review risk scores for assets.
4. **To Run the Tool**: streamlit run risk-score-gen.py

## Notes
The CSPM Risk Scorer PoC is a PoC tool for any organization looking to enhance its security posture by systematically assessing and prioritizing risks within their cloud environments. It uses synthetic data that has been generated using a seperate script. The data that you see in the UI may not be representational of a production cloud environment. 

## Streamlit UI

<img width="823" alt="image" src="https://github.com/samvas-codes/cspm-risk-scorer-poc/assets/110348148/a4ab3928-386c-4a61-a224-e6aa224c5cd9">
