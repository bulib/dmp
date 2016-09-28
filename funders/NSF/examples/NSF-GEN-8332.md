# Arthropod responses to grassland nutrient limitation

By: DMP dmpcurator
Created on 12/11/2013 using the [DMPTool](https://dmp.cdlib.org/) Template: NSF-GEN: Generic

You can find the full-text at [https://dmptool.org/api/v1/plans_full/8332.pdf](https://dmptool.org/api/v1/plans_full/8332.pdf) 

## Types of data produced

> Types of data, samples, physical collections, software, curriculum materials, and other materials to be produced in the course of the project.


	We will collect insects annually from the 30 experimental plots at each of the eight sites (see body of proposal for sampling details). Samples will be immediately deposited in sealable containers labeled with the date, site code (already existing), block, plot, and subsample. An associated record of any observations or notes will be entered in a field tablet computer and labeled with the same information. We will also record environmental information including temperature and general observations. Labeled samples will be transported back to the laboratory, where they will be sorted and identified using a dissecting microscope. We will identify and count the arthropods to the classification of order, with the exception of members of the order Auchenorrhynca, which will be identified to species or morphospecies. Identifications will be reviewed by multiple researchers associated with the project and verified with the assistance of Stuart McKamey of the Systematic Entomology Laboratory of the USDA Agricultural Research Service. Representatives of the identified species and morphospecies will be vouchered to the Bell Museum of Natural History at the University of Minnesota (U of M).
	Abundance for each group will be recorded by hand in a laboratory notebook during sorting. These data will be transcribed into an Excel spreadsheet as each sample is completed. The spreadsheets will be stored on a controlled--‐access U of M server directory that is backed up offsite nightly. Files will be named according to the format site_mmddyyyy_plot.csv using existing unique site codes. Lind will be responsible for the data during and after data collection until publication.
	After identification, Arthropod samples from each experimental plot will be subsampled and sent to the University of St. Thomas Kay lab for stoichiometric analysis. We will receive a spreadsheet of data after processing is complete. This spreadsheet will include the insect identification (including site code, date, year, plot, and arthropod identification) and percent by mass of carbon, phosphorus and nitrogen. These files will be saved as .csv files in the previously described server directory.
	Our data set will be used in combination with the existing Nutrient Network (nutnet.unm.edu) data on plant responses to nutrient manipulation. The NutNet data is currently stored and managed in a MySQL relational database housed at the Minnesota Supercomputing Institute and accessed through a secure internet connection. We will add our data and metadata to the NutNet relational database. The existing csv files will be read into temporary tables in the MySQL database, and then inserted into permanent data tables using insert query statements. The existing database schema links tables of data observations to a &ldquo;plot&rdquo; table describing the experimental unit. New tables will be created for each of the arthropod data types (abundance and stoichiometry) containing the unique plot identifier. Multiple tables may be necessary for efficient data storage and management; for example, an &ldquo;Arthropod&rdquo; table holding scientific names for use can be used to constrain the labels of abundance records to acceptable possibilities.


## Data and metadata standards 

> Standards to be used for data and metadata format and content (where existing standards are absent or deemed inadequate, this should be documented along with any proposed solutions or remedies).


	The project will leverage existing metadata standards currently stored in Ecological Metadata Language (EML) format for the NutNet project. We will add additional metadata entries for the arthropod community composition and arthropod stoichiometry; field notes taken during the time of collection will be recorded. Morpho software will be used to generate the metadata file in EML. We chose EML format for our metadata since it allows integration with existing NutNet data housed in the Knowledge Network for Biocomplexity (KNB) data repository.


## Policies for access and sharing

> Policies for access and sharing; Provisions for appropriate protection of privacy, confidentiality, security, intellectual property, or other rights or requirements.


	After publication of manuscripts based on the data we collect, we will share our data and metadata with the NutNet community via data updates sent annually as .csv files from the existing central relational database. Other NutNet users will need to contact Lind for access to the data. We will also submit both of our datasets (abundance and stoichiometry) to the U of M Digital Conservancy, an archive for digital preservation. Borer has access to this resource as a faculty member. This will occur within a year of publication. The data will be publicly available via the Digital Conservancy, which provides a permanent URL for digital documents.


## Policies for re-use, redistribution

> Policies and provisions for re-use, re-distribution, and the production of derivatives.


	Access to databases and associated software tools generated under the project will be available for educational, research and non--‐profit purposes. Such access will be provided using web--‐based applications, as appropriate. Materials generated under the project will be disseminated in accordance with University/Participating institutional and NSF policies. Depending on such policies, materials may be transferred to others under the terms of a material transfer agreement. Those that use the data (as opposed to any resulting manuscripts) should cite it as follows: Lind, E, E Borer and A Kay. yyyy. Grassland Arthropod abundance and stoichiometry associated with nutrient manipulation. [URL]; accessed on ddmmyyyy. This information will be described in the metadata. Intended and foreseeable users of the data are NutNet collaborators and participants, as well as other scientists interested in arthropod‐plant relationships. This data set could be used in combination with similar data sets from other NutNet sites or for meta‐analysis.


## Plans for archiving and preservation

> Plans for archiving data, samples, and other research products, and for preservation of access to them.


	We will preserve both arthropod datasets generated during this project (abundance and stoichiometry) for the long term in the Digital Conservancy at the U of M. We will include the .csv files, along with the associated metadata files. We will also submit an abstract with the datasets that describe their original context and any potentially relevant project information. Borer will be responsible for preparing data for long--‐term preservation and for updating contact information for investigators.


Processed 2016-09-28 16:57:00.744092
