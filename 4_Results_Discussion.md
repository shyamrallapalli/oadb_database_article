# Results & Discussion

## Database design

### Database folder structure
To foster and promote the goals of collaborative crowdsourced genomic analysis of ash and dieback fungus, we had setup a git based genomics data and analyses repository.
We have used the repository framework established by the scientific community working on the E.coli outbreak in Germany (ref) as a reference to design the ashdieback repository.
And we have setup the data repository at https://github.com/ash-dieback-crowdsource/data to utilize the collaborative features of github.com.
The database structure was expanded to support data organization from both host and pathogen as well as feasible to maintain multiple related organisms under same project.
Database was organised in to a hierarchy of folders.
A folder with project name "ash_dieback" was created along with a "readme.md" file explaining about the project, at the root of the repository.
Organism was the next branch of folders. Each organism in turn encompassed multiple strains and each strain contained individual folders that describe various data sets and analyses.
Each strain has following folders reads, assemblies, annotations, alignments.
"Reads" folder has sequence read files resulting from sequencing of RNA, gDNA and other sequencing experiments.
"Assemblies" folder has the genome and transcriptome assemblies, generated using sequence reads generated through various experiments.
"Annotation" folder encompasses gene, protein models generated and the functional annotation of the identfied protein domains, analysis about repeats and transposible elements present in the genome.
"Alignments" folder hosts alignment bam files and sequence read comparison with others strains.
Folders are not restricted to categories mentioned above and can be expanded to the requirement of the project and based on the data and analyses types available.
For example we had  blasts and read quality metrics folders to provide data from blast analysis and seqeuce read quality assesment of the various sequence reads.
This particular folder and sub-folder structure enables managing and maintenance multiple organisms in porject and multiple strains and multiple versions of data under each strains.


The github repo is named based on the project "ash-dieback-crowdsource".
Base folder in the database is a data folder and with a markdown file explaining the data and folder structure available in the database.
This base folder contains invidual folder for each organim and few .README files templates for each data types and analysis types
presented in the database and metadata about organims and strains or isolates specific to each organisms.

Under each organism folder has metadata for the organism and individual folders for each clone or strain or isolate.
Each strain contains folders describing various data and analyses described earlier.

Such a semantically arranged folder structure is aimed to facilitate intuitive data browsing.


### Metadata description
Each folder is included with .info files, which provide the necessary metadata about the organism, strain or detailed information about the analysis and relevant links to input data, software versions used and their parameters were included, in order to reproduce the analysis.
In the main project folder "ash_dieback", we have provided templates for metadata info files for alignments (alignment.README), annotation (annotation.README), assembly (assembly.README), blast (blast.README), organism (org.README), reads (reads.README), sequences (sequences.README) and strain (strain.README).
These pre-made templates serve as guidelines for the necessary metadata to be provided by the submitter of data and analyses.
In addition to the provided info files, github provides a wiki section, where contributors can include detailed description of the datasets submitted to the repository.
Organization of data in to folder structure and with the availability of wiki and users can provide a written description in addition to the data and parameters of analysis.
Further to metadata info files and project wiki section, we have created a blog at http://oadb.tsl.ac.uk/, where contributors can provide description about the data submitted or analysis performed. Github wiki section and OADB blog website reports serve as an avenue to promote open science collaborations through sharing of the latest developments and insights in to the current research of the project.
As mentioned earlier we have used git version control system and use of git makes the attribution of contribution transparent.
Tracking of who did what through commit history facilitates a transparent collaborative platform and makes user attribution of the work, straightforward.
Additionally such a tracking system would also helps to identify any mistakes resulted and documents open discussion of the issue to resolve.
By submitting raw data and their metadata on public nucleotide archives (SRA or ENA), would make the database maintenance and the space usage manageable and all the data will be available publicly.


### Utility of the github/git
The database is downloadable as a zip from the github.com website or clone using git commands.
To be able to browse, view and download the data, user are not required to be member of the community.
However if one would like to contribute to the analysis or data, they have to signup to be a member of the ash-dieback-crowdsoucre organization.
Membership to community can be subscribed by getting in touch with the admin at oadb@tsl.ac.uk and providing information about with your github username.
Git version control through github graphical interphase for personal computes provides easier option to modify, update and commit the changes to the data repository.

ability to download data and need to be a team member to be able to submit updates and corrections and data submission etc...


### General comments to add


## Description of data
OADB repository current holds genomes of both ash and dieback fungus.

Describe the genomes available

genome size and protein coding genes

InterProScan annotation of domains and motifs
comparing proteins sequences to public databases of pfam, PROSITE, SMART etc

Gene Ontology information was extracted from the InterProScan results

Mating Types of dieback fungus

Diversity mRNA data
SNP and INDEL analysis of 6 mixed material possibly more information 43 UK and European isolates of dieback fungus would be made available soon.

Genome browsing and gene content search
