# Results & Discussion

## Database structure

### Database and Metadata description
Note: Comment about OADB blog under this section
### Utility of the github/git

### General comments to add
ability to download data and need to be a team member to be able to submit updates and corrections and data submission etc...
## Description of data





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

Each folder is included with .info files, which provide the necessary metadata about the organism, strain or detailed information about the analysis and relevant links to input data, software versions used and their parameters to reproduce the analysis were included.
In the main project folder "ash_dieback", we have provided templates for metadata info files for alignments (alignment.README), annotation (annotation.README), assembly (assembly.README), blast (blast.README), organism (org.README), reads (reads.README), sequences (sequences.README) and strain (strain.README).
These pre-made templates provide guidelines for the necessary metadata to be provided by the submitter of data and analyses.
In addition to the provided info files, github provides a wiki section, where contributors can provide detailed description of the datasets submitted to the repository.
Organization of data in to folder structure and with the availability of wiki and users can provide a written description in addition to the data and parameters of analysis.
Along with the metadata info files and project wiki section, we have created a blog at http://oadb.tsl.ac.uk/, where contributorss can provide description about the data submitted or analysis performed. These wiki sections and blog website helps to promote open science collaborations through sharing of the latest developements and insights in to the current research of the project.
We have used github as the
Use of github make the attribution of contribution transparent.
Tracking of who did what is handled by the commit history and provides framework for transperant colloborative works and user attribution of the work.
Addiionally such a tracking would also facilitate any mistakes and necessary verification could be done to see the issue is sorted.

By submitting raw data and their metadata on public repositories such as SAR or ENA, it would make the database mainternance
and the space usage managable and all the data will be available publicly.


git version control and github graphical interphase

The database if downloadable as a zip from the github.com website or clone using git commands. To be able to browse, view and
download the data you don't have to be member of the community. However if you would like to contribute to the analysis or data,
you have to signup to be a member of the ash-dieback-crowdsoucre organization. To be a memeber you should get in touch with
the admin at oadb@tsl.ac.uk with your github username.

Crowdsourcing databases provides oppurtunity to dissaminate latest analysis and promote colloboration between labs working
on similar aspects of the project.

The github repo is named based on the project "ash-dieback-crowdsource".
Base folder in the database is a data folder and with a markdown file explaining the data and folder structure available in the database.
This base folder contains invidual folder for each organim and few .README files templates for each data types and analysis types
presented in the database and metadata about organims and strains or isolates specific to each organisms.

Under each organism folder has metadata for the organism and individual folders for each clone or strain or isolate.
Each strain contains folders describing various data and analyses described earlier.

Such a sementically arranged folder structure is aimed to faciliate intutive data browsing.


I could write about oadb blog, shall include about geefu or not??
