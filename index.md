<h1 align="center">Network Analysis of Private Contracting in Failed States</h1>

#### Harrison Hartnett 
#### Professor Carrie Diaz Eaton  
#### DCS375 Network Analysis  
#### April 17th, 2025

## Background
As a politics major in my final year of undergrad, I wanted to write my thesis about private military contracting. The trend of states employing private contractors to outsource military functions both during and since the Cold War has been well documented (Ori Swed and Daniel Burland 2020; Serres 2023). According to Swed and Burland: “The post-Cold War era opened the door for private entrepreneurs to market their security expertise more widely”. In 2003, the number of newly created PMSCs was 79, doubling in the two years since 2001, when only some 38 new PMSCs (Ori Swed and Daniel Burland 2020 p.3). These authors clearly show that the number of PMSCs has increased dramatically since the 1980s, until it plataus around 1200 in 2016. Private military contracting can be problematic for a number of reasons including the difficulty of classifying their employees under international humanitarian law (IHL) (Crowe and John 2017), the potential erosion of state monopolies on the legitimate use of force (Krahmann 2013), and as evidenced by the Abu Ghraib example, the increased potential for human rights violations.

During my research, I realized that something was missing from the existing literature: a  clear accounting of which states tended to engage in private contracting, and where they chose to employ PMSCs. At the same time, I came across a dataset that could be extremely useful for this purpose; the Private Security Database (PSD). This is a database that tracks the deployment of private contractors in collapsing or failed states. It was created as part of a research project "Privatization and Commercialization of Security", which is part of the Collaborative Research Center “Governance in Areas of Limited Statehood” in Berlin (https://www.conflict-data.org/psd/index.html). Although this is not a comprehensive list of all the private military contracting that occured in those years, this analysis is an important step in understanding the scope of PMSC use by states.

The following project is a network analysis of data from the private security database (PSD), focusing on two main questions:
- What insights can be gained about the general structure of the network of private contracting?
- Which countries or institutions tend to employ PMSCs the most?

Using igraph and bipartite R packages to visualize and analyze the network of private military contracting among states.

## Ethical Considerations
This analysis uses publically available software and data for maximum reproducablility. All scholarly sources are referenced and all online resources have appropriate links. None of the data used contains any information that could be traceable to specific individuals.

## Visualizations & Analysis
![Error: Image Not Found](PrivateSecurityNetwork.png)
## References
Crowe, Jonathan, and Anna John. 2017. “The Status of Private Military Security Companies in United Nations Peacekeeping Operations under the International Law of Armed Conflict.” Melbourne Journal of International Law 18(1): 16–44. doi:10.3316/informit.980092731941255.

Krahmann, Elke. 2013. “The United States, PMSCs and the State Monopoly on Violence: Leading the Way towards Norm Change.” Security Dialogue 44(1): 53–71. doi:10.1177/0967010612470292.

Ori Swed and Daniel Burland. 2020. “The Global Expansion of PMSCs: Trends, Opportunities, and Risks.” Working Group on the use of mercenaries as a means of violating human rights and impeding the exercise of the right of peoples to self-determination.

Serres, Dominic. 2023. “Re-Emergence of Private Military and Security Companies (PMSCs) in the Post-Cold War Era: Analyzing the Impact of Security Commodification Amidst Growing Global Power Rivalry.” https://ruj.uj.edu.pl/xmlui/handle/item/314598 (March 29, 2025).

Luke, D. (2015). A User’s Guide to Network Analysis in R. Germany: Springer International Publishing.
