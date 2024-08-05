# Climate Data Science

## Project Overview

### Objective

Convert published research, and research data trails into deterministic and probabilistic algorithms and imputations
relating to climate change and prediction of asset pricing. Encode those algorithms in Python. 

### Deliverables

For each research paper:

- **Algorithms Encoded in Python**: Develop and encode deterministic and probabilistic algorithms from the research
  paper.
- **Documentation of the Algorithms**: Comprehensive documentation detailing the algorithms, their functions, and how
  they relate to the research.
- **List and Definitions of Dependent and Independent Variables**: Provide a detailed list and definitions of all
  dependent and independent variables used in the research paper.

## Data Description

### Data Sources

We will supply the necessary data and the research papers. The data sources include but are not limited to:

1. PRISM Climate Data
2. NCREIF Property Data
3. Redfin Housing Market Data
4. National Oceanic and Atmospheric Administration (NOAA) Climate Data Online
5. Bureau of Economic Analysis (BEA) Regional Data
6. U.S. Census Bureau County Population Totals
7. Thomson Reuters Loan Pricing Corporation (DealScan)
8. COMPUSTAT
9. National Climate Data Center (NCDC) of NOAA
10. S&P Global Market Intelligence
11. Datastream
12. Worldscope
13. Kenneth French’s Data Library
14. Ivy DB OptionMetrics
15. CRSP (Center for Research in Security Prices)
16. S&P Global Trucost
17. ISS Carbon Risk Ratings
18. Morningstar ESG Fund Flows
19. Palmer Drought Severity Index (PDSI)
20. Google API for Geocoding Addresses
21. National Centers for Environmental Information (NCEI)
22. World Bank Economic Data
23. U.S. Bureau of Economic Analysis (BEA) GDP Data

## Methodology

### Approach

1. **Algorithm Extraction**: Extract algorithms from each research paper, including mathematical formulas, coefficients,
   and assumptions.
2. **Data Acquisition**: Gather the necessary datasets identified in the papers to support the algorithm development.
3. **Data Cleaning and Preparation**: Clean and preprocess the data to match the requirements of the algorithms.
4. **Algorithm Encoding**: Encode the extracted algorithms into Python, ensuring they are functional and accurate.
5. **Validation and Testing**: Validate the algorithms using the provided datasets to ensure they produce the expected
   results.
6. **Documentation**: Document each algorithm, including the logic, data requirements, and any assumptions made during
   the encoding process.

## Tools and Techniques

- **Programming Language**: Python

## Project Timeline

The project will proceed one research paper at a time, with each paper being fully analyzed, its data gathered,
algorithms developed and tested, and documentation completed before moving on to the next paper.

## Expected Challenges

- Handling missing or inconsistent data.
- Ensuring accuracy and completeness of extracted algorithms.
- Validating algorithms against provided datasets.
- Thoroughly documenting complex methodologies and assumptions.

## Evaluation Criteria

- **Accuracy**: Algorithms must produce correct and reliable results.
- **Completeness**: All relevant aspects of the research paper must be encoded.
- **Clarity**: Documentation should be clear, comprehensive, and easy to follow.
- **Usability**: Algorithms should be practical and applicable to real-world use cases.

## Next Steps

Please fork this repository and spend **no more than 15-30 minutes** writing up how you would approach this project,
focusing on your methodology and any potential challenges you foresee. Submit your proposal by Friday, August 9.

## Submission Instructions

1. **Clone this repository**:
    - Clone the repository to your local machine using the command.
      ```bash
      git clone https://github.com/Climate-Index-AI/climate-economics-data-science.git climate-impact-algorithms-proposal
      ```

2. **Create a new private repository**:
    - Create a new PRIVATE repository on your GitHub account. Name it as `climate-impact-algorithms-proposal`

3. **Change the remote URL**:
    - Navigate to the cloned repository folder:
         ```bash
         cd climate-impact-algorithms-proposal
         ```
    - Change the remote URL of the cloned repository to your new private repository.
      ```bash
      git remote set-url origin <your private repo url>
      ```

4. **Add your proposal**:
    - Add a file named `proposal.md` with your write-up on how you would approach this project.

5. **Commit and push your changes**:
    - Commit your changes and push them to your forked repository:
      ```bash
      git add proposal.md
      git commit -m "Add project proposal"
      git push origin main
      ```

6. **Invite the repository owner**:
    - Go to your forked repository on GitHub.
    - Click on "Settings" and then "Collaborators" under the "Access" section.
    - Invite the repository owner to your private repository by adding their GitHub username by clicking in the "Add people" button.
        - Owners GitHub username: `tom-mcmillan` and `vitorbarros`

7. **Notify the repository owner**:
    - Once the repository owner has been invited, email `tom@climateindex.ai`, and `vitor@climateindex.ai` with the
      subject "Climate Economics Data Science Project Proposal - [your name]" and include a link to your forked
      repository.
