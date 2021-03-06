# ASSESSMENT OF WATER QUALITY OF HOROOLO DRAIN

By: Arif  Asghar
Created on 01/24/2016 using the [DMPTool](https://dmp.cdlib.org/) Template: NSF-AGS: Atmospheric and Geospace Sciences

You can find the full-text at [https://dmptool.org/api/v1/plans_full/19365.pdf](https://dmptool.org/api/v1/plans_full/19365.pdf) 

## Products of research

> Describe the types of data and products that will be generated in the research, such as physical samples, space and/or time-dependent information on chemical and physical processes, images, spectra, final or intermediate numerical results, theoretical formalisms, computational strategies, software, and curriculum materials.

The USGS will develop science-quality, applications-ready, time-series of key terrestrial variables and produce them on an operational basis using historical, current, and future Landsat observations. The terrestrial variables will follow the guidelines established through the Global Climate Observing System (GCOS) and include Climate Data Records (CDRs) that represent geophysical transformations of Landsat data (e.g., calibrated radiances, inter-calibration of Landsat instrument radiances, surface reflectance and surface temperature), and Essential Climate Variables (ECVs) that represent specific geophysical and biophysical land properties. CDRs and ECVs offer a framework for producing long-term Landsat datasets suited for monitoring, characterizing and understanding land surface change over time (Strategic Plan for Developing Landsat-scale Climate Data Records and Essential Climate Variables).

Therefore, the USGS Land Remote Sensing Program sets the following goals for the next five years:


	Generate a surface reflectance CDR from calibrated Landsat 4-7 and future Landsat missions as a first step in transforming Landsat data into a time series for terrestrial monitoring.
	Conduct research to develop and implement a technical approach to develop terrestrial ECV products of dynamic surface water extent (SWE), burned area (BA) and snow covered area (SCA).
	Link this work to USGS terrestrial monitoring activities involving scientific assessments and decision support.


Nominal CDR production will generate surface reflectance products for every Landsat acquisition over the continental U.S. (CONUS) and Alaska from 1984 to the present. There are approximately 1,176,019 scenes archived at EROS from Landsat 7 Enhanced Thematic Mapper Plus (ETM+) and 603,863 scenes from Landsat 5 Thematic Mapper (TM). The total volume currently estimated for storing the raw Landsat pixel values, surface reflectance values, and ancillary quality information is 4.49 petabytes (PB).


## Data format

> Describe the format in which the data or products are stored (e.g. hardcopy logs and/or instrument outputs, ASCII, XML files, HDF5, CDF, etc). What metadata will be part of the data sets produced?

The surface reflectance CDR derived from Landsats 4-7 Thematic Mapper (TM) and Enhanced Thematic Mapper Plus (ETM+) is produced using Landsat Ecosystem Disturbance Adaptive Processing System (LEDAPS) software baselined at EROS and currently running under version 2.2.1. Landsat 8 Operational Land Imager (OLI) surface reflectance is generated with a different algorithm to take advantage of that instrument's unique characteristics. All Landsat surface reflectance products share the basic specifications listed below.

Projection: Universal Transverse Mercator (UTM)

Format: Exelis Visualization (ENVI) binary (.img)

Pixel Size: 30-meter (m)

Temporal Coverage Landsat 4 TM: July 1982 to December 1993

Temporal Coverage Landsat 5 TM: March 1984 to May 2012

Temporal Coverage Landsat 7 ETM+: July 1999 to within one week of present

Temporal Coverage Landsat 8 OLI: April 2013 to within one week of present

Metadata for these products is generated in extensible markup language (XML) format for distribution with the data products, and follow Federal Geographic Data Committee (FGDC) standards. Metadata attributes are also embedded within the data product file headers. The field names in typical LEDAPS metadata are shown below, and are currently used to populate the discovery databases in EarthExplorer for product search and order.

&lt;data_provider&gt;, &lt;satellite&gt;, &lt;instrument&gt;, &lt;acquisition_date&gt;, &lt;scene_center_time&gt;, &lt;level1_production_date&gt;, &lt;solar_angles&gt;, &lt;wrs&gt;, &lt;lpgs_metadata_file&gt;, &lt;corner&gt;, &lt;corner&gt;, &lt;bounding_coordinates&gt;, &lt;projection_information&gt;, &lt;corner_point location&gt;, &lt;corner_point location&gt;, &lt;grid_origin&gt;, &lt;utm_proj_params&gt;, &lt;projection_information&gt;, &lt;orientation_angle&gt;, &lt;bands&gt;, &lt;short_name&gt;, &lt;long_name&gt;, &lt;file_name&gt;, &lt;pixel_size&gt;, &lt;data_units&gt;, &lt;valid_range&gt;, &lt;calibrated_nt&gt;, &lt;app_version&gt;, &lt;production_date&gt;


## Access to data, and data sharing practices and policies

> Describe your plans for providing access to data, including websites maintained by your research group and contributions to public databases. If maintenance of a web site or database is the direct responsibility of your group, provide information about the period of time the web site or database is expected to be maintained. Also describe your practice or policies regarding the release of data&#8212;for example whether data are available before or after formal publication and the approximate duration of time that the data will be kept private. Describe your policies (where applicable) for protection of propriety data, privacy and confidentiality, intellectual property, or other rights or requirements.

As algorithms achieve provisional status, Surface Reflectance data products are available through EarthExplorer, under the &ldquo;Data Sets&rdquo; tab as &ldquo;Landsat CDR.&rdquo; The ESPA On Demand Interface also offers Surface Reflectance, in addition to Original Input Products and Metadata, Top of Atmosphere (TOA) Reflectance, and several Spectral Indices products: http://espa.cr.usgs.gov. Services such as reprojection, spatial subsetting, and pixel resizing are also available on that site.

All Landsat CDRs and ECVs are generated under intentions of perpetuity to support long term monitoring of land change. The only applicable restrictions to these collections are standard compliance to International Traffic in Arms Regulations (ITAR).


## Policies and provisions for re-use, re-distribution and production of derivatives

> Describe your policies regarding the use of data provided via general access or sharing. If you plan to provide data on a website, will the site contain disclaimers, or conditions regarding the use of the data in other publications or products? If the data or products are copyrighted, how will this be noted on the website?

There are no restrictions on the re-use or re-distribution of the Landsat surface reflectance CDRs, as these products are intended for public use in the study of long term land change. The data providers simply request users include the following citation in publication or presentation materials based on these products to acknowledge the USGS as a data source, and to credit the original research.

Landsat Surface Reflectance products courtesy of the U.S. Geological Survey Earth Resources Observation and Science Center.

If possible, reprints or citations of papers or oral presentations based on USGS data are welcome at EROS User Services (http://landsat.usgs.gov/contactus.php). Such cooperation will help USGS stay informed of how the data are being used.


## Archiving of data

> Describe whether and how data will be archived and how preservation of access will be handled. For example, will hardcopy logs, instrument outputs, and physical samples be stored in a location where there are safeguards against fire or water damage? Is there a plan to transfer digitized information to new storage media or devices as technological standards or practices change? Will there be an easily accessible index that documents where all archived data are stored and how they can be accessed? If the data will be archived by a third party, please refer to their preservation plans (if available).

Landsat CDRs and ECVs are generated with the intention of providing long term data records for use in land change studies. The collections will be archived at USGS EROS under the same protocols for preservation as lower-level Landsat data. Once operational, these products will be publicly available through an on-line interface (EarthExplorer), and backed up on tape and external disk.

A digital presence for access to and information about the CDRs and ECVs is expected to be supported indefinitely through the USGS Land Remote Sensing Program, which will either host or provide links to relevant Web sites and documentation. So far, an Algorithm Description Document (ADD) and Product Guides are available to facilitate use of the data set (http://landsat.usgs.gov/CDR_LSR.php).




Processed 2016-09-28 16:57:24.615672
