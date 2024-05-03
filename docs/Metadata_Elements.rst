Metadata Elements
=================

This section provides guidance to elements included in the NRW Metadata Schema which are derived from UK Gemini and MEDIN metadata standards. Each Section contains the title of the elements and a descriptions of what should be entered into each element.

Users may also wish to consult the full `UK Gemini 2.3 specification <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series>`__. and 'MEDIN 3.1.2 Guidance Notes <https://medin.org.uk/sites/medin/files/documents/MEDIN_Schema_Documentation_3_1_2_full-1.pdf>'__.

Unique Resource Identifer URI
--------

The URI allows a data resource to be identified.  The number should be auto-generated when you create a record and may contain two possible prefix. The Prefix for datasets owned by NRW is NRW_DS and if it is a Third-Party Dataset it should be EXT_DS.

*Note: Users should take care in ensuring they use the correct URI number and not create a number that is not given to them in the data entry process.*

Title
--------

The title is the name that the dataset is commonly known by. It should be given a brief title that describes its contents. This will include the data subject, geographic extent, and date range. For datasets about species include the common name and then the scientific name.  Avoid file names, underscores, jargon, or acronyms.

There are two boxes in Data Discovery for this element, one for English and one for the welsh translation of the title if it is known. 

Alternative Title
--------
This should include any other names for the dataset including acronyms or any other name the dataset can be referenced by. For single datasets you can include the exact file name used in the corporate store where the data is held such as AreasofOustandingNaturalBeauty.lyr. If you want to add more alternative title's then please select the **+** sign to add more.

*Note: For Security reasons please do not include the full file-path of the dataset.

Dataset Language
--------
This is the language used in the dataset and not the language used for the metadata. These are from a controlled vocabulary but most instanced will use either Welsh or English.

Abstract
--------
This is a brief narrative summary describing content of the data resource. The abstract should provide a clear and brief statement of the content of the data resource.  Include what has been recorded/mapped, what form the data takes, what purpose it was collected for, and any limiting information, e.g., limits or caveats on the use and interpretation of the data.  It is recommended that acronyms and abbreviations are reproduced in full (i.e., use Natural Resources Wales instead of NRW). If you have a translation of the abstract then this can be included in the box which has **Cymraeg**.
	
	*Note: with Gemini 2.3 there is now a requirement for the abstract to be at least 100 characters long, and to be different from the* `title <#title>`__ *element. Validation will display an error if these conditions are not met.*

Lineage
--------
Lineage element should be used to document additional information about the background or history of the data resource and can include data quality statements.  The element can include information about source material; data collection methods; data processing methods; quality control processes and may be useful in determining its fitness for purpose.  

Any specific information warnings should be added here.

If there is separate documentation that contains a methodology (e.g., a Science Report, Standard Operating Procedure (SOP) or data processing notes) then this document should be referenced in the Additional Information Source Element

Additional information
----------------------
Any reference to external information that are considered useful, e.g., NRW Evidence Report title, Standard Operating Procedure (SOP), project website.  This should NOT be the web site or service where the data is published as that information is recorded in the element "Resource Locator"

You may include a specialist contact at NRW.  Only post details should be provided and not names and contact details. 

Dataset reference date
----------------------
This element can inlclude up to 3 different Date Types.

**Creation Date** refers to the date the dataset was created or if the creation date is not known use the date it was first made available to staff.

**Publication Date** is when the data is published externally for download i.e. on DataMapWales, NBN or other approved NRW publishing mechanism. This should be updated on the occurance of a published dataset being updated.

**Revision Date** is when the dataset has been updated and a new version has been created. This should only be used once and the date changed for each update to the dataset.

Temporal Extent
----------------------
This is the date or date range of the period of collection of the data.  Include start date and end date of survey or data capture period. 

For some data resources data collection, may be continuous.  In these cases, the end date may be left blank.  This should only be applied where data is updated on a frequency greater than quarterly.

Resource Maintenance and Update Frequency
---------------------- 

This is the frequency with which modifications and deletions are made to the data resource after it was first produced. The element is created as part of a controlled vocabulary and you shoud choose the appropriate frequency from the drop down list. If the update cycle is unknown, please choose '**Unknown**' from the list.

NRW Internal Location
-------------------
This should be the corporate data store name or archived location; file pathway should only be used if not in a corporate store or archive.  This information is required to aid internal data management.  For Spatial data please include the location of the data layers on the X: Drive

NRW Internal Custodian
-------------------
The internal staff member or team that is identified as the Data Custodian for the data resource.  This should be the person or team who take local responsibility for either its creation, maintenance or can answer questions about the content of the data resource.

Topic Category

-------------------

A basic classification for the data resource.  Select one or more categories that most closely represent the topic of the data resource from the controlled vocabulary. 

Keywords  NRW Thesaurus

-------------------

Please include any keywords which you think help identify the dataset and increase its the data's discovarability. This can include species names, survey types, locations such as SSSI's or other protected site designations. 

To add a keyword from the NRW Thesaurus you will need to select the book icon and select **NRW Thesaurus** a search box will then be opened for you to search for the relevant keyword. 

*Note: If you cant find a suitable keyword which you would like adding please contact your Data Discovery Administrator and they can add it for you.*

Keywords - GEMET INSPIRE themes
-------------------
All geospaital datasets should contain at least one INSPIRE theme keyword. Keywords are from a controlled vocabulary and can be selected by clicking the box and scrolling through the term list or searching for the theme in the search box. 

Keywords - SeaDataNet Parameter Discovery Vocabulary
-------------------
All datasets that are Marine Data Resources should ensure they have one of these keywords from the controlled vocabulary.

To add a keyword from the NRW Thesaurus you will need to select the book icon and select **SeaDataNet Parameter Discovery Vocabulary** a search box will then be opened for you to search for the relevant keyword. 

Responsible Organisations
-------------------
This element Details the organisation(s) responsible for the establishment, management, maintenance, and distribution of the data resource. For each metadata record at least one of the below organisation types should be recorded except **Custodian** which is just for use with Marine datasets. In some cases multipe organisations can be listed for each element.E.g. a data resource was created in joint partnership between NRW and Welsh Government then both would be the originator or owner.

To add an organisation you will need to search the name of the organisation in the search box. Once you have found the organisation you can select the "+" symbol and click what organisation type they belong to.

**Owner** Data Discovery also contains Third-Party datasets so it is important to capture the owner of the data resource. If the data has been collected by a contractor/surveyor under contract, then NRW should be entered as Owner not the contractor.

**Originator** This element requires who recorded the original data. Much of NRW data is collected under contract or by third parties as well as dedicated teams, it is important to document who captured the data as this lends to an assessment of quality of the data. 

**Distributor** Who is the responsible organisation for releasing the data where applicable.

**Custodian** Who is the organisaion responsible for maintaining the data resource.

*Note: If you can't find the organisation then please contact your Data Discovery Administrator*

Data Format
--------------------------------
This will be the format in which the digital or physical data can be provided. The element is created of 3 components which should be completed for metadata to be valid against the NRW Metadata Schema. If your data comprises of numerous Data Formats you can select the **+** to add multiple Data Formats.

**Name** This is a free-text field and users can include more detail on the data format type here. For example for Database users can type Microsoft Access as the database name.
*Note: For all GIS datasets ESRI Feature Class should be added to the name field*


**Version** This should be populated with the version information about the format of the resource. For example you can add  **Windows 10** to be the version of software for an Excel Spreadsheet. If no version information is known then please populate this with **Unknown**

**Type** Is the title of the data format which is set from a controlled vocabulary, more details on each type can be found below.

**Database**	Files that are used to store data in database applications such as Oracle or MS Access
**Delimited**	File formats that are delimited by commas, tabs, semi colons that can be opened using software packages such as MS Excel
**Documents**	Files that hold written information such as pdf, doc,
**Geographic Information System**	Files that are geographic in scope and can be opened by MapInfo or ESRI
**Image**	Still image files such as jpeg, tiff, png that may be opened by applications such as PhotoShop
**Google Earth and Oceans**	Files (e.g. kml, kmg) used to display data and images using Google applications Earth and Oceans.
**Network Common Data Form**	Binary data files conforming to a set of conventions allowing them to be manipulated through the NetCDF API and tools built using that API
**Text or Plaintext**	Files encoded in a character convention, usually ASCII, that need to be handled with a generic text editor such as Vi or Notepad or bespoke software

Resource Locator
--------------------------------
The is the web address or where the data is accessible from i.e., it should be a recognized web service or view or data download service, for example,National Biodiversity Network Atlas, DataMapWales, NRW data download page.  You should only add the address when the data becomes available.  You should not add web pages that simply provide additional information, such as, project websites as this information would be added to element Additional Information Resource

The has  seperate sub-elements which should all be completed

**Name** This is the name of the type of download link. One of the following should be typed here - View and Download, Web Service. For datasets that are published to DataMapWales then the View and Download link should be added and also the Web Mapping Service link.
**URL** This is the URL link to the data.
**Protocol** This can be selected from the *Recommended Values* box to the left of the element, in most cases this should be **Web Address URL**

Extent
--------------------------------
This element defines the geographical extent of coverage of the data resource relative to an administrative hierarchy. 

To add a Geographic Identifer to the Extent you **must** use one of the values in the *Recommended Values* box and not to write in your own values. In most cases this can be set to **Wales**

bounding box
--------------------------------
This is a rectangle enclosing the extent of the data resource described in latitude and longitude.  It has 4 elements: West, East, South, North. 

To enter a bounding box in three different ways. 

The first is you can use the map provided to draw a bounding box around your dataset. Alternativly you can use a pre-defined extent to choose from the **Choose a Region** box if there is an applicable value to choose from. Finally if you know the bounding box co-ordinates then you can enter these in the N,E,S,W boxes in the map and the map will draw the extent for you. 

Spatial Reference System
------------------------
This is theIdentifier of the system of spatial referencing whether by coordinates or geographic identifiers, used in the data resource.  One of the following can be selected:

OSGB 1936 / British National Grid (EPSG:27700)
WGS 84 Lat/Long (EPSG:4326)
OSGB 36 Lat/Long (EPSG: 4277)
ETRS89 Lat/Long (EPSG:4258). *This option should only be included when the data is transformed to the INSPIRE specification for the relevant INSPIRE theme*.

Spatial Resolution
------------------------
For this element two options are available  **Distance** or **Equivalent Scale**. 

**Distance** provides an indication of spatial resolution of the data is and is the equivalent to ground sample distance. For data captured in the field it is the average distance between sampling points.

*Note You should not complete this field if the data is not collected to a strict sampling regime*

**Equivalent Scale** should only be used if Distance can not be completed and is the level of detail expressed as the scale denominator of a comparable hardcopy map or chart. This field should only be used where data is captured/digitised to a specific background map, e.g., OS products.  If data is captured to MasterMap enter 2500. The spatial resolution should not be confused with map scale the data is usually displayed at as this is purely a display attribute

Spatial Representation Type
------------------------
This is the method used to spatially represent geographic information. To enter a representation type please select one of the options in the drop down list.


Limitations on public access
----------------------------
This element refers to NRW's ability to release or withhold all or part of the dataset to the public, per the FOI Act, EIR and DPA. The element should state if the dataset is either **Restricted** or have **other Restrictions**. Reasons for restricting the dataset should be included in the below **Access Restrictions Text** Section.

Access Constraints Text
----------------------------
The purpose of this element is to describe any restrictions on access the dataset. 

For dataset that have gone through an internal Open Data Assessment and has been classified with an Open Government Licence can include the following: 

*There are no access restrictions to this data. NRW may release, publish or disseminate it freely*

Use Constraints
------------------------
Where the above access restrictions are about the restrictions placed on accessing our data this element is about restrictions placed on **using** our data. 

The element comprises of two sub-elements. The first is a drop down list where you can select if the use of the data is **restricted** or has **other restrictions**. The second is a free text field where users can describe any restrictions on using the data. For datasets that have been classed as Open the below can be used.

*© CNC/NRW
Data may be re-used under the terms of the Open Government Licence providing it is done so, acknowledging both the source and NRW's copyright. It is the recipient's responsibility to ensure the data is fit for the intended purpose.*

Licence
------------------------
This should include one of the options in the dropdown list to describe the type of licence the dataset has and should only be used once the data has been through an Open Data Assessment.

Attribution Statement
------------------------

This element is used to acknowledge the owners of the data

For NRW data use add: 
Contains Natural Resources Wales information © Natural Resources Wales and Database Right. All rights reserved. 

If OS data is included in NRW data add: 
Contains Ordnance Survey Data. Ordnance Survey Licence number AC0000849444. Crown Copyright and Database Right.


Extent - Vertical extent
------------------------
Describes the vertical domain (height range) of the data resource. The element is composed of the **minimum value**, **maximum value** and the **vertical 
coordinate reference system** (recorded as a name or code from a recognised thesaurus, i.e. `EPSG Geodetic Parameter Registry <http://www.epsg-registry.org/>`__).


This element should be completed only where the vertical extent is relevant (e.g. geology, mining, etc.). If it is relevant, then all sub-elements are mandatory.

To add the vertical extent you will first need to add the Vertical Extent Keyword in the search box, once this has been added you can add the vertical extent by either selecting **with CRS** *Coordinate Reference System* or **with Datum.** *Newlyn Datum*

Once you select which reference system to use you can add the minimum and maximum values in metres. 


Data Quality
--------------------

This element is specifically to meet INSPIRE obligations and describes the degree to which the data resource conforms to the INSPIRE thematic specification. You would only complete this field if you know that the data resource has been transformed to meet the INSPIRE Regulation by the Spatial Data Unit.

Metadata language
-----------------

The language used to document the metadata. The purpose of this element is to identify the language used in a multi-lingual metadata service, 
for example in the INSPIRE geo-portal.

Parent identifier
-----------------
NRW may create metadata for a group of datasets that are all related, in a case such as this, we should also create one overarching metadata entry (Series metadata).  The parent ID allows the tagged set to be identified as part of a Series.  

To add a Parent Identifer you will need to use the **Associated Resources** to the right of the data entry screen and select add and then **Link to a Parent**. A search box should now appear and you can then search for the parent dataset. The Parent Identifer Box should now automatically have the Parent Unique Resource Identifer in the box.

Metadata Date
-------------------------
This refers to the date the metadata was created and added to Data Discovery. It is not the date the data was created or published.

Metadata standard name
----------------------
Name of the metadata standard or profile used, cited with a reference to the appropriate register entry. 

Metadata standard version
-------------------------
Version of the metadata profile used

Metadata Point of Contact
-------------------------

This is automatically pre-set to Natural Resources Wales but for datasets owned by Third-Party organisations then the Organisation Name, Email and Role (which should remain as Point of Contact) should be used as a minimum.
	
	


