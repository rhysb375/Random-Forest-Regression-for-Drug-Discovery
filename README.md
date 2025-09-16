# Random-Forest-Regression-for-Drug-Discovery
Here is another similar project to the previous one as a study for random forest machine learning. It is a random forest regression model that uses bioactivity data of bioactive molecules with drug-like properties to predict the inhibitory ability of said molecules on a drug target related to PPMS. 
Its key features include using a range of Python tools such as PaDEL-Descriptor, RdKit and SciKitLearn to turn vast amounts of complex data into clean molecular descriptors to be input into a simple but effective drug discovery tool.
# Issues with this project
- Unfortunately, good quality data on drug targets of PPMS were severely lacking. Although the model works quite well, the data it was trained on constrained its prediction ability (Garbage In, Garbage Out). This highlights the growing importance of acquiring more data through research for AI-driven personalised medicine.
- Another issue was my choice of drug target for this model which was MAP kinase kinase kinase 8 AKA Tumour Progression Locus 2. My rationale for selecting MAP3K8 was this:
1. Simply, the molecular descriptors I planned on using for this model were present in the ChEMBL database for this target. Due to time constraints, I settled for using this drug target.
2. There is promising research around targeting kinases for PPMS, especially concerning Bruton's Tyrosine Kinase (BTK) inhibitors and allosteric TYK2 inhibitors. However, targeting any kinase comes with trade-offs of safety concerns. 

Although there is some preclinical evidence to suggest that inhibiting MAP3K8 can regulate the severity and onset of EAE (MS modelling disease) in mice, there are still many barriers to this drug target being a good point of study. One of which is the fact that MAP3K8 is a highly connected central node in many different biological processes within the body, targeting this with an inhibitor could lead to severe pleiotropic effects. In future, I will not rush into selecting a drug target just based off of satisfactory data. 

Thanks for taking the time to look at my project!
