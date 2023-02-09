# The Human Microbiome Project
## Stream data with DDA:
```
from dagshub.streaming import DagsHubFilesystem

fs = DagsHubFilesystem(".", repo_url="https://dagshub.com/DagsHub-Datasets/human-microbiome-project-dataset")

fs.listdir("s3://human-microbiome-project")
```

## Description: 
The NIH-funded Human Microbiome Project (HMP) is a collaborative effort of over 300 scientists from more than 80 organizations to comprehensively characterize the microbial communities inhabiting the human body and elucidate their role in human health and disease. To accomplish this task, microbial community samples were isolated from a cohort of 300 healthy adult human subjects at 18 specific sites within five regions of the body (oral cavity, airways, urogenital track, skin, and gut). Targeted sequencing of the 16S bacterial marker gene and/or whole metagenome shotgun sequencing was performed for thousands of these samples. In addition, whole genome sequences were generated for isolate strains collected from human body sites to act as reference organisms for analysis. Finally, 16S marker and whole metagenome sequencing was also done on additional samples from people suffering from several disease conditions.
## Contact: 
The NIH-funded Human Microbiome Project (HMP) is a collaborative effort of over 300 scientists from more than 80 organizations to comprehensively characterize the microbial communities inhabiting the human body and elucidate their role in human health and disease. To accomplish this task, microbial community samples were isolated from a cohort of 300 healthy adult human subjects at 18 specific sites within five regions of the body (oral cavity, airways, urogenital track, skin, and gut). Targeted sequencing of the 16S bacterial marker gene and/or whole metagenome shotgun sequencing was performed for thousands of these samples. In addition, whole genome sequences were generated for isolate strains collected from human body sites to act as reference organisms for analysis. Finally, 16S marker and whole metagenome sequencing was also done on additional samples from people suffering from several disease conditions.
## Update Frequency: 
Uncertain
## Managed By: 
https://commonfund.nih.gov/hmp
## Resources: 
1. resource: 
	- Description: https://aws.amazon.com/datasets/human-microbiome-project/
	- ARN: arn:aws:s3:::human-microbiome-project
	- Region: us-west-2
	- Type: S3 Bucket

## Tags: 
[aws-pds](#aws-pds), [life sciences](#life&nbspsciences), [genetic](#genetic), [genomic](#genomic), [metagenomics](#metagenomics), [microbiome](#microbiome), [fasta](#fasta), [amino acid](#amino&nbspacid), [fastq](#fastq)
## Publication: 
1. publication: 
	- Title: Strains, functions and dynamics in the expanded Human Microbiome Project
	- URL: https://www.nature.com/articles/nature23889
	- AuthorName: Jason Lloyd-Price, Anup Mahurkar, Gholamali Rahnavard, Jonathan Crabtree, Joshua Orvis, A. Brantley Hall, et al.

2. publication: 
	- Title: The Human Microbiome Project
	- URL: https://www.nature.com/articles/nature06244
	- AuthorName: Peter J. Turnbaugh, Ruth E. Ley, Micah Hamady, Claire M. Fraser-Liggett, Rob Knight & Jeffrey I. Gordon

3. publication: 
	- Title: New microbe genomic variants in patients fecal community following surgical disruption of the upper human gastrointestinal tract
	- URL: https://www.sciencedirect.com/science/article/pii/S2452231718300289
	- AuthorName: Ranjit Kumar, Jayleen Grams, Daniel I. Chu, David K.Crossman, Richard Stahl, Peter Eipers, et al
