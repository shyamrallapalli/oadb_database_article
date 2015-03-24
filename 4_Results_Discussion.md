# Results & Discussion

Organization of data in to folder structure and a wiki
and users can provide a written description in addition to the data and parameters of analysis.

We would like to setup a collobarative crowdsourcing platform towards the genomics stuyd of ash and ash diecback fungus. We have used the framework established by German E.coli outburst open scientific community.
This github database is established based on the ideals followed by community working on the E.coli outburst.
We have expanded the framework to make data organization poissble for host-pathogen data as well applicable to muliple organism under same project. Orgaims would be the highest order of folders.
Each organism would encompass multiple strains and each straing would host multiple version of datasets, such as version of genome assemblies datainputs for the genome assemblies.
For each strain we have individual folders setup that describe various data sets and analysis as explained below. Each strain has folder for seuqnece reads, assemblies, annotations, alignments, blasts and read quality metrics. Reads folder has sequence read files resulting from RNA-seq, gDNA seq and other sequencing experiments. Assemblies folder has the assembly sequence files resulting from genome and transcriptome assemblies of the sequence reads files generated through various experiments.


This particular folder and sub-folder structure enables managing and maintenance multiple organisms in porject and multiple strains and multiple versions of data under each strains.

Each folder is included with .info and links to data files providing the metadata and where necessary folders are included with .md files detailing the information about the data and the analysis.
in the root folder we have proivded templates for metadata info files for alignments, annotation, assembly, blast, org, reads, seqeunces and strain.

Use of github make the attribution of contribution transperant. Tracking of who did what is handled by the commit history and provides framework for transperant colloborative works and user attribution of the work. Addiionally such a tracking would also facilitate any mistakes and necessary verification could be done to see the issue is sorted.

By submitting raw data and their metadata on public repositories such as SAR or ENA, it would make the database mainternance and the space usage managable and all the data will be available publicly.

The database if downloadable as a zip from the github.com website or clone using git commands. To be able to browse, view and download the data you don't have to be member of the community. However if you would like to contribute to the analysis or data, you have to signup to be a member of the ash-dieback-crowdsoucre organization. To be a memeber you should get in touch with the admin at oadb@tsl.ac.uk with your github username.

Crowdsourcing databases provides oppurtunity to dissaminate latest analysis and promote colloboration between labs working on similar aspects of the project.

The github repo is named based on the project "ash-dieback-crowdsource".
Base folder in the database is a data folder and with a markdown file explaining the data and folder structure available in the database.
This base folder contains invidual folder for each organim and few .README files templates for each data types and analysis types presented in the database and metadata about organims and strains or isolates specific to each organisms.

Under each organism folder has metadata for the organism and individual folders for each clone or strain or isolate. Each strain contains folders describing various data and analyses described earlier.

Such a sementically arranged folder structure is aimed to faciliate intutive data browsing.


I could write about oadb blog, shall include about geefu or not??


