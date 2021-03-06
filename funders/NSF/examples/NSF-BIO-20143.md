# Climatic Limitation of Alien Weeds in New Zealand: Enhancing Species Distribution Models with Field Data

By: Jennifer Pannell
Created on 03/08/2016 using the [DMPTool](https://dmp.cdlib.org/) Template: NSF-BIO: Biological Sciences (2015- )

You can find the full-text at [https://dmptool.org/api/v1/plans_full/20143.pdf](https://dmptool.org/api/v1/plans_full/20143.pdf) 

## Data and Materials Produced

> Describe the types of data, physical samples or collections, software, curriculum materials, and other materials to be produced in the course of the project.  (For collaborative proposals, the DMP must cover all the various data types being collected by each collaborator.)

Data collected

A presence/absence survey of all non-native Crassulaceae plants on Banks Peninsula, New Zealand was conducted in 2010 by road. In total, 844 grid cells of 30 arc-seconds (WGS 1984) were surveyed, approximately 39% of the region. Grid cells containing rock outcrops and other likely habitat were targeted, ignoring outcrops above 500 MASL [surveyed by Wiser and Buxton 2009]. Where there was no road access, cells were surveyed via walking tracks and boat. Species presence/absence and approximate abundance was recorded.

Global occurrence data of Aeonium arboreum (L.) Webb &amp; Berthel., Aeonium haworthii (Salm-Dyck) Webb &amp; Berthel., and Cotyledon orbiculata (L.) were collated. Records were collected from online databases (e.g. GBIF, available at http://www.gbif.org), surveys (e.g. NVS, available at http://nvs.landcareresearch.co.nz), online herbarium records (e.g. http://virtualherbarium.org.nz), and physical examination of non-digitised herbarium records. Society newsletters, proceedings, and journal articles were used, as well as national flora and personal communication with local residents, experts and herbaria. Where location records were unclear or vague, the surrounding area was searched using Google StreetView (https://www.google.com/maps/streetview), resulting in an additional 19 records.

Field transplant experiments were conducted on Banks Peninsula between November 2010 and November 2012, using cuttings of A. arboreum, A. haworthii and C. orbiculata. Permission was obtained from the Ministry of Primary Industries for the propagation of C. orbiculata. Cuttings were collected from local populations, and were transplanted to 40 field sites between 7 and 681 MASL in Christchurch City Council reserves, after cultivation and de-hardening in glasshouse. Plant size (width, height, and breadth in mm) was measured every 6 months. Plant deaths and flowering were recorded at every site visit (monthly in summer to prevent seeding).

Germination experiments were conducted at the same transplant sites overJuly 2011 - November 2012, using seeds of A. arboreum, A. haworthii, and C. orbiculata collected from 8 local populations per species. Seeds were planted into cell trays, with 100 seeds per population, and 3 populations per species in each tray. One tray was transplanted to each site. Seedlings were counted every month for first 3 months, then at standard 6-monthly measurement intervals.

Field surveys of naturalized populations of A. arboreum, A. haworthii, and C. orbiculata on Banks Peninsula were conducted over November 2010 - March 2011 (at peak flowering), and then again a year later. Eight populations per species were surveyed, across a climate gradient. Transects measuring 50m were set up at each site. Along transects, 50 plants were permanently tagged. Each plant was classified by life stage and had its rosettes (Aeonium sp.) or leaves from base of tag (C. orbiculata) counted, as well as inflorescences. Ten adult plants were sub-sampled for estimation of flowers per inflorescence, and measurement of internodes (Aeonium sp., mm) and plant breadth, width and height (all species, mm). At each site, number of inflorescences and individuals in population was estimated. In the second year, the same measures were taken as well as recording dead/missing plants. Additionally, breadth, width and height of all 50 plants was measured, and seedlings (&lt;1 year old) within 1m of transect were counted.

Seed counts were conducted in the laboratory, using seeds collected in March 2011. Five inflorescences per population were collected from each of the 8 survey sites, before dehiscence. Seeds per pod was estimated by weight according to the International Rules For Seed Testing guidelines (ISTA, available athttps://www.seedtest.org). Seed viability was tested in the laboratory, using triphenyl tetrazolium chloride. One mixed sample of 100 seeds from each survey site was tested, according to ISTA guidelines.

Temperature was recorded at each transplant and survey site. Measurements were taken every 4 hours to the nearest 0.5 degrees Celsius, for the duration of data collection, using Thermochron iButtonTM data loggers. Aspect was recorded to the nearest cardinal direction using a compass. Elevation was recorded using a handheld GPS (sites were also GPS tagged). Canopy cover was measured using a convex spherical densiometer (Forestry Suppliers Inc., model 43887) according to the methods of Lemmon (1956).

Materials produced

Species distribution models of potential habitat for the study species in New Zealand were run, as well as niche analyses comparing the New Zealand and global distributions. Occurrence data was cleaned and resampled. Climate data were obtained from Worldclim (http://www.worldclim.org). Global land use and livestock data were obtained from FAO (http://gaez.fao.org). New Zealand land use data were obtained from the Land Cover Data Base (http://lris.scinfo.org.nz), and livestock data from AgribaseTM.

Climate variables were derived for all field sites (growing degree days, frost days, precipitation, solar radiation, aspect, elevation, and canopy cover). Temperature variables were derived from data logger recordings. Precipitation was estimated from the nearest weather station in the CliFlo database (http://cliflo.niwa.co.nz). Aspect, elevation and canopy cover were as recorded in field. Solar radiation was modelled in ArcMap 10.0 using the Solar Analyst tool (Fu and Rich 1999) and a 15m DEM.

Generalized linear mixed models (GLMMs) were run on field data against climate. From the field experiment, relative growth [ln(Volume t+1) - ln(Volume t)] was run as a gaussian model, and mortality and germination as logistic models. From survey data, probability of flowering was run as a logistic model, while inflorescences per plant, flowers per inflorescence and seeds per pod were run as Poisson models. Response variables were modelled against climate variables using stepwise backward selection.

Finally, one integral projection model (IPM) was parameterized for each species, integrating all field data to model population growth as a function of climate. Developed in R, the model followed a similar structure to the package IPMpack Metcalf et al. (2013)and the code described by Merow et al. (2014).


## Standards, Formats and Metadata

> Describe the standards to be used for all the data types anticipated, including data or file format and metadata. 

All data files will be saved as CSV or ASCII files for cross-platform compatibility, exchangeability and long-term access. Metadata will be created as seperate XML files using DataCite's metadata schema version 3.1 (https://schema.datacite.org/), the standard format for Figshare (https://figshare.com/).

Metadata fields will include: identifier, creator, title, publisher, publication year, contributor (host institution), subject, language, size, format, rights, description (abstract, column names and units), dates (updated), geo-location (if relevant). The following datasets will be stored:


	Species occurrence data (world)
	Raw temperature data (data loggers, Banks Peninsula)
	Derived climate data (Banks Peninsula)
	Transplant experiment data - a) site descriptions, b) deaths, c) flowering, d) growth, e) seedling counts
	Field survey data - a) site descriptions, b) main 50 plants, c) sub-sampled 10 plants, d) seeds per pod
	Model codes (SDMs, niche analyses, GLMMs, IPMs) - R scripts
	Model outputs (SDMs) - ASCII layers for GIS



## Roles and Responsibilities

> Describe the roles and responsibilities of all parties with respect to the management of the data (including contingency plans for the departure of key personnel from the project).

Data collection and production of materials: Jennifer L. Pannell

Supervision of project: Prof. Phil Hulme, Prof. Richard Duncan and Prof. Susan Worner.

Data storage: Hard copy to be left with Lincoln University library on submission of PhD thesis. As part of the data management plan for the Bio-Protection Research Centre, Lincoln University, all data will also be uploaded to Figshare (https://figshare.com).


## Dissemination Methods

> Describe the dissemination methods that will be used to make data and metadata available to others during the period of the award, and any modifications or additional technical information regarding data access after the grant ends.


All data and metadata will be stored privately in the cloud on Figshare until publication, after which point it will be made open-access under a Creative Commons license, and citable in its own right. Data will be searchable on Figshare, and downloadable by any user. Use of universal formats will ensure maximum exchangeability and cross-platform compatibility for all users. All data will be under embargo until publication of chapters as manuscripts, or 3 years after the PhD has been awarded, whichever is sooner.


## Policies for Data Sharing and Public Access

> Describe the PI’s policies for data sharing, public access and re-use, including re-distribution by others and the production of derivatives. Where appropriate, include provisions for protection of privacy, confidentiality, security, intellectual property rights and other rights.


No restrictions on data necessary, or ethical or privacy issues. Intellectual property rights will rest with the original author of the data (J. Pannell), and the project supervisors (P. Hulme, R. Duncan, S. Worner). Data will be free to use under the expectation that it will be correctly attributed and cited using the Figshare DOI.


## Archiving, Storage and Preservation

> Where relevant, describe plans for archiving data, samples, software, and other research products, and for on-going access to these products through their lifecycle of usefulness to research and education. 

USB hard drive and paper copies of data and metadata to be stored at Lincoln University library, New Zealand. Data will be archived along with PhD thesis. Digital copies will be stored on Figshare.

The the stability and accessibility of Figshare provides a suitable option for long term storage of data, and should ensure minimal risk of data loss. The following explanation is copied from: (https://figshare.com/blog/Applying_for_a_grant_Let_us_help_you_with_your_Research_Data_Management_Plan/51).

&quot;Figshare and the CLOCKSS Archive have partnered to preserve Figshare's publically available content in CLOCKSS's geographically and geopolitically distributed network of redundant archive nodes, located at 12 major research libraries around the world. This action provides for content to be freely available to everyone after a &quot;trigger event&quot; and ensures an author's work will be maximally accessible and useful over time.

Figshare is hosted using Amazon Web Services to ensure the highest level of security and stability for research data. Amazon S3 stores multiple, redundant copies of the research outputs. AWS utilizes an end-to-end approach to secure and harden infrastructure, including physical, operational, and software measures. Amazon S3 provides authentication mechanisms to ensure that data is kept secure from unauthorised access. The security and persistence of the files on Figshare makes it easy to prevent plagiarism of research data, as all uploads are time-stamped.

By documenting the research outputs according to DataCite&rsquo;s metadata schema, the data will be easily filterable and manageable. When made public the associated metadata is disseminated through DataCite at the California Digital Library helping: establish easier access to research data; increase acceptance of research data as legitimate contributions in the scholarly record; support data archiving to permit results to be verified and re-purposed for future study.

Figshareoffers unlimited storage space for data that is made publicly available on the platform. Users of the site maintain full control over the management of their research whilst benefiting from global access, version control and secure backups in the cloud.

All research outputs made publicly available through Figshare will have a DOI to make the outputs citable and all metrics on the impact of the research will be openly available both on the site and through the open API.&quot;

References


	Fu P, Rich PM (1999) Design and implementation of the Solar Analyst: an ArcView extension for modeling solar radiation at landscape scales. Proceedings of the Nineteenth Annual ESRI User Conference 11‑31.



	Lemmon PE (1956) A spherical densiometer for estimating forest overstory density. Forest Science 2(4): 314‑320.



	Merow C, Dahlgren JP, Metcalf CJ, Childs DZ, Evans ME, Jongejans E, Record S, Rees M, Salguero‐G&oacute;mez R, McMahon SM (2014) Advancing population ecology with integral projection models: a practical guide. Methods in Ecology and Evolution 5(2): 99‑110. DOI: 10.1111/2041-210x.12146



	Metcalf CJE, McMahon SM, Salguero‐G&oacute;mez R, Jongejans E (2013) IPMpack: an R package for integral projection models. Methods in Ecology and Evolution 4(2): 195‑200. DOI:10.1111/2041-210x.12001



	Wiser SK, Buxton RP (2009) Montane outcrop vegetation of Banks Peninsula, South Island, New Zealand. New Zealand Journal of Ecology 33(2):164‑176.






Processed 2016-09-28 16:57:27.590934
