---
title: "Genomes in the Cloud and the Law of the Land"
date: 2021-11-21T00:45:28+11:00
---

How likely would you be to hand over your DNA sequence if you knew your genome was stored in the cloud - perhaps on a server overseas? 

By 2025, it is estimated that we will have sequenced up to 40 exabytes of genetic data (National Human Genome Research Institute, 2021). This data has already produced life-saving diagnoses and will continue to serve as the basis for cutting edge research for many years to come. 

Research and industry, however, face the challenge of dealing with the grand scale of this data. A single genome can be easily sequenced for less than $1000, but the cost of storing and analysing this data is nearly two or three times as much.
However, one key bit of technology that has enabled this progress is the power of the cloud. 


## Why the Cloud?

Computers that process genetic data are incredibly powerful and expensive but aren’t typically used 24/7 and given the increasing number of individuals we are sequencing and analyzing, it would be expensive to manage this infrastructure in-house. To avoid such costs, outsourcing this infrastructure to cloud providers has become popular. The cloud is ‘elastic’ - you only pay for what you use and you are able to request as many resources as required. Whilst cloud solutions were initially built for industry, they have been increasingly popular in academia as opposed to on-premises hardware. 

Each of the three major cloud operators - AWS, Google Cloud and Microsoft Azure - hold their market share by offering both computing and storage, along with a suite of resources to enable genomic science on their platform. Beyond the monetary savings, the cloud enables flexibility to bring the software to the data rather than the other way round - as moving terabytes of genetic sequence data is still prohibitively expensive (Krumm & Hoffman, 2020)  - hence enabling collaboration at an international scale.

The cloud was meant to abstract away the physical servers to provide infrastructure as a service, however, significant privacy, legal and security challenges have arisen as a consequence. 


## Data Sovreignity 
Each individual’s genetic code is one-of-a-kind. While anonymization and encryption can protect the identities of individuals and minimize the impact of a data breach, this isn't possible with genetic data. 

It’s nearly impossible to anonymize an individual’s DNA sequence and, to date, many of our core computational tools don’t yet work with encrypted genomic data (Kolata, 2013). Hence a breach in genomic data can be far more devastating than any other data breach, like a credit card database breach. 
Therefore, to protect personal and identifiable genomic data many nations have introduced legislation to enact data sovereignty. 

Data sovereignty is the key concept that the data belongs to and is governed by the legislation and policies in the countries where it was collected and processed.

For example, the General Data Protection Regulation (GDPR) that is enforced in the EU, considers genomic data as personal data. Companies that collect and process personal data from EU residents are legally obliged to anonymize and encrypt this data on their servers wherever they are located - else they face hefty fines.

South Africa has been one of the first African countries to draft a new data sovereignty law, dubbed the Draft National Data and Cloud Policy (Schneidman et al., 2021). The country is home to among the world’s most diverse populations and hosts over half of all the data centres on the continent, but if passed this law, along with a previously passed law called POPIA (Nordling, 2019), would potentially require all personal data from South Africa to remain in South Africa, making data-sharing and acquiring broad consent from South Africans more difficult. 
Moreover, many of these laws are not internationally compatible with each other and moving genomic data across the globe requires a case-by-case examination - which isn’t conducive to doing science in the cloud. For instance, unlike GDPR, Australian data privacy laws consider genomic data not to be an example of personal data. 


Fortunately, consortia like the Genomic Alliance for Global Health (GA4GH) are aiming to set international standards and policies to enable such global collaboration. They aim to allow cloud technologies to play well with genetic data in a way that complies with GDPR and similar legislation, and set protocols regulating how data is collected, managed, and transferred. However, many companies such as 23andme are notably absent from such consortia. 


## Blockchain technologies...to the rescue?

How do we weigh the benefits of discoveries in personalised medicine against the obligations of keeping genetic data safe and secure?


It’s crucial that individuals have control over their data. Some, for example, might not trust that a government’s laws are sufficient to protect their own genome, and might prefer to have their own control. Once such instance can be seen in the USA, where insurance companies are able to access any genetic data stored on health records (Molteni, 2019). 


Well-established direct-to-consumer testing companies like Ancestry and 23andme have collected consumer genetic data and stored it away in their own repositories and clouds. In contrast, a new line-up of start-ups is experimenting with blockchain technologies to give individuals the power to control who accesses their genetic sequences. 


Companies like Genomes.io provide an encrypted data vault where an individual’s DNA is sequenced privately and stored. Researchers and service providers are then able to access this data anonymously by requesting an individual’s consent through a mobile app. 

Whilst the DNA itself isn’t stored on the blockchain, the interactions between the individual and the third-party providers are recorded on a blockchain that is popular for its immutability (Genomes.io, 2019). However, will similar technologies be adopted in biobanks to enable discoveries in personalised medicine? Only time will tell. 


However, it’s likely that such technologies might show promise in incentivising individuals to share their DNA, since they know they can control who has access to it.

## References and additional reading 

1. Genomes.io. (2019, June 26). Your DNA Vault: A new standard in genomic data security. Medium. https://medium.com/@Genomesio/your-dna-vault-a-new-standard-in-genomic-data-security-7a8a55d74e89
2. Kolata, G. (2013, January 17). Web Hunt for DNA Sequences Leaves Privacy Compromised. The New York Times. https://www.nytimes.com/2013/01/18/health/search-of-dna-sequences-reveals-full-identities.html
3. Krumm, N., & Hoffman, N. (2020). Practical estimation of cloud storage costs for clinical genomic data. Practical Laboratory Medicine, 21, e00168. https://doi.org/10.1016/j.plabm.2020.e00168
4. Molteni, M. (2019, January 5). The US Urgently Needs New Genetic Privacy Laws. Wired. https://www.wired.com/story/the-us-urgently-needs-new-genetic-privacy-laws/
5. National Human Genome Research Institute. (2021, March 22). Genomic Data Science Fact Sheet. National Human Genome Research Institute. https://www.genome.gov/about-genomics/fact-sheets/Genomic-Data-Science
6. Nordling, L. (2019). A new law was supposed to protect South Africans’ privacy. It may block important research instead. Science. https://www.science.org/content/article/new-law-was-supposed-protect-south-africans-privacy-it-may-block-important-research
7. Schneidman, W., Cooper, D., Govender, D., Mkhize, M., & Naidoo, S. (2021, November 5). Overview of South Africa’s Draft National Data and Cloud Policy. Global Policy Watch. https://www.globalpolicywatch.com/2021/11/overview-of-south-africas-draft-national-data-and-cloud-policy/