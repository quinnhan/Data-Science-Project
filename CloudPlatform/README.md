I have been learning some cloud technologies (GCP and Azure). I think they revolutionize the data world. I'd like to document projects, issues and troubleshooting, what I found facinating and maybe pros and cons of the two platforms. 
### Account and Pricing 
My GCP learning is through Google Qwiklabs which includes video lessions, labs and access to GCP for practice. Trial period is 30 days then $30 monthly and cancel anytime. For Azure, [learning for data folks](https://learn.microsoft.com/en-us/training/browse/?products=azure&roles=data-analyst%2Cdata-scientist) are free on their [website](www.azure.com), 30 days trial access to Azure Synapse Analytics then pay-as-you-go pricing model. 
### First impression
So much for me to learn. Both platforms are **involved**. Who knew that you could write a ML model and tune parameters in **SQL query** in Google Big Query. 

## 1. Projects:
I started with a fundamental knowledge absorbsion before working on a project. I followed [Explore data analytics in Azure with Azure Synapse Analytics](https://microsoftlearning.github.io/DP-900T00A-Azure-Data-Fundamentals/Instructions/Labs/dp900-04-synapse-lab.html). This gives me understanding of how it works. It took about 30 min to complete because I scrutinized each step. Prior to this, it took me 5 days to figure out why firewall prevented me to run Azure SQL pool. TL;DR: I did not have port 80,443,1443 outbound set up. Restarted my computer and voilà. 
1. 350K movies analysis via Azure:
- Dataset: It's free from [Kaggle](https://www.kaggle.com/datasets/stephanerappeneau/350-000-movies-from-themoviedborg) credit to user STEPHANERAPPENEAU
