Metadata Elements
=================

This section provides guidance to elements included in the NRW Metadata Schema which are derived from UK Gemini and MEDIN metadata standards. Each Section contains the title of the elements and a descriptions of what should be entered into each element.

Users may also wish to consult the full `UK Gemini 2.3 specification <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series>`__. and 'MEDIN 3.1.2 Guidance Notes <https://medin.org.uk/sites/medin/files/documents/MEDIN_Schema_Documentation_3_1_2_full-1.pdf>'__.


Unique Resource Identifer (URI)

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
-------------------
This is the date or date range of the period of collection of the data.  Include start date and end date of survey or data capture period. 

For some data resources data collection, may be continuous.  In these cases, the end date may be left blank.  This should only be applied where data is updated on a frequency greater than quarterly.

Resource Maintenance and Update Frequency
-------------------
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

Keywords - NRW Thesaurus
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

Extent - Geographic bounding box
--------------------------------
:Gemini: `Bounding box <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#44>`__
:INSPIRE: Geographic bounding box
:ISO19115: MD_DataIdentification.extent > EX_Extent > EX_GeographicExtent > EX_GeographicBoundingBox
:Obligation: Mandatory
:occurrence: Many

:Definition:
	Rectangle enclosing the extent of the data resource described in latitude and longitude, to enable the resource to be located geographically. 
	It has four sub-elements: *west bounding longitude*, *east bounding longitude*, *south bounding latitude*, and *north bounding latitude*.

:Guidance:
	A pre-defined extent can be chosen from the drop down menu, or bounding coordinates can be manually entered in the corresponding boxes. The 
	west bounding longitude should be less than the east bounding longitude, and the north bounding latitude must be greater than the south.

|userdoc_fig_7_8_1_GeogBoundingBox|

Extent - Geographic description
-------------------------------
:Gemini: `Extent <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#15>`__
:INSPIRE: n/a
:ISO19115: MD_DataIdentification.extent > EX_Extent > EX_GeographicExtent > EX_GeographicDescription.geographicIdentifier
:Obligation: Optional
:occurrence: Many

:Definition:
	The geographical extent of the data resource relative to an administrative hierarchy. Note that it is the coverage of the data resource, not 
	the individual objects in the data resource. Thus if the data resource was national parks in Scotland, the extent would be 'Scotland', even 
	though many parts of Scotland do not have National Parks. Sub-elements of the geographic description are the *code* identifying the extent and 
	the *designating authority* (optional).

:Guidance:
	Enter a pre-defined extent of country or Local Authority using one of the controlled lists available in the drop down above the bounding box element (e.g. Geonames). 
	Note that this element may also be populated using a linked data register entry, for example `http://statistics.gov.scot/id/statistical-geography/S92000003 <http://statistics.gov.scot/id/statistical-geography/S92000003>`__.

|userdoc_fig_7_9_1_GeogDescription|



Extent - Vertical extent
------------------------
:Gemini: `Vertical extent information <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#16>`__
:INSPIRE: n/a
:ISO19115: MD_DataIdentification.extent > EX_Extent > EX_VerticalExtent
:Obligation: Optional
:occurrence: Many

:Definition:
	Describes the vertical domain (height range) of the data resource. The element is composed of the **minimum value**, **maximum value** and the **vertical 
	coordinate reference system** (recorded as a name or code from a recognised thesaurus, i.e. `EPSG Geodetic Parameter Registry <http://www.epsg-registry.org/>`__).

:Guidance:
	This element should be completed only where the vertical extent is relevant (e.g. geology, mining, etc.). If it is relevant, then all sub-elements are mandatory.
	
	To add the vertical extent:
	
	**1|** In default (simple) view, scroll to the extent element and click |button_edit_verticalextent|.
	
	**2|** Enter a minimum value in metres.

	**3|** Enter a maximum value in metres.

	**4|** Choose the appropriate vertical CRS from the recommended values dropdown list.

|userdoc_fig_7_11_1_VerticalExtent|


File identifier
-------------------
:Gemini: `File identifier <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#45>`__
:INSPIRE: metadata/2.0/rec/common/fileIdentifier
:ISO19115: MD_Metadata.fileIdentifier
:Obligation: Mandatory
:occurrence: One

:Definition:
	Unique identifier for this metadata file.

:Guidance:
	To support the operation of UK Location and INSPIRE, discovery metadata records must include a File Identifier for the resource. This will be auto-generated by a metadata creation tool (e.g. the metadata portal itself or an external metadata editor) and once created cannot be changed.

	File identifier should not be confused with the UK GEMINI2 metadata item `Resource identifier <#resource-identifier>`__, which identifies the data resource being described.

|userdoc_fig_7_31_1_FileIdentifier|	

Hierarchy level name
--------------------
:Gemini: `Hierarchy level name <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#47>`__
:INSPIRE: Hierarchy level
:ISO19115: MD_Metadata.hierarchyLevelName
:Obligation: Mandatory for series and services, optional for datasets
:occurrence: One

:Definition:
	The name of the hierarchy level for which the metadata is provided (eg dataset, series, service).

:Guidance:
	Set to '**service**', '**series**', or '**dataset**' as appropriate. Note that in UK Gemini this element is conditional for datasets.

|userdoc_fig_7_19_1_MetadataHierarchyLevel|

Keyword
-------
:Gemini: `Keyword <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#6>`__
:INSPIRE: Keyword
:ISO19115: MD_Identification.descriptiveKeywords > MD_Keywords
:Obligation: Mandatory
:occurrence: Many

:Definition:
	Terms covering the subject of the data resource that are more specific than those entered under `topic category <#topic-category>`__.  Ideally, 
	these will be standardised keywords originating from a controlled vocabulary, so that resources can be identified in any search.

:Guidance:
	It is recommended that keyword values be taken from a standardised subject vocabularies, such as `General Environmental Multi-Lingual Thesaurus (GEMET) <http://www.eionet.europa.eu/gemet/en/themes/>`__ or the `Integrated Public Sector Vocabulary (IPSV) <http://id.esd.org.uk/list/subjects>`__,
	and the formal citation provided (including the date, version and any amendments where appropriate). This will enable other users to perform 
	more efficient searches and eliminate resources that are of no interest more easily.
	
	If the dataset is covered under INSPIRE, then the **first** keyword should be from the `General Environmental Multi-Lingual Thesaurus (GEMET) - INSPIRE Spatial Data Themes <http://www.eionet.europa.eu/gemet/en/inspire-themes/>`__ list. 
	Service records must include a keyword from the INSPIRE `Classification of spatial data services <http://inspire.ec.europa.eu/metadata-codelist/SpatialDataServiceCategory>`__ code list.
	
	To add new keywords from a controlled vocabulary to the editing form:

	**1|** Click the |button_edit_selectthesaurus| button below the keywords element.
	
	**2|** Select the desired thesaurus (e.g. GEMET - INSPIRE themes, version 1.0). This will add a search box for the thesaurus.
	
	**3|** Click to select the relevant keyword. The citiation for the originating vocabulary will be pre-populated.
	
	*Note: alternately, free text keywords can be added by clicking the* |button_edit_addkeyword| *button.*

|userdoc_fig_7_12_1_Keywords|


Limitations on public access
----------------------------
:Gemini: `Limitations on public access <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#25>`__
:INSPIRE: Limitations on public access
:ISO19115: MD_Identification.resourceConstraints > MD_LegalConstraints.accessConstraints & otherConstraints
:Obligation: Mandatory
:occurrence: Many

:Definition:
	Restrictions imposed on **access** to the data resource for security and other reasons (i.e. who can see the data). 

:Guidance:
	Limitations on public access is different from the `use constraints <#use-constraints>`__ element, which describes limitations on using the data, 
	such as fees or licencing restrictions, rather than the access to it. A data resource can be openly accessible (which all INSPIRE data should 
	be), but have restrictions on its use such as licensing, fees, or usage limitations.
	
	For INSPIRE purposes, the *Limitations on public access* dropdown box must be set to '**other restrictions**'. The anchor element below must then be populated with an appropriate label from the `INSPIRE code list for Limitations on public access <http://inspire.ec.europa.eu/metadata-codelist/LimitationsOnPublicAccess/>`__. Change the anchor label to the appropriate entry from the code list, and ensure the URL points to the corresponding code list URI.

	Article 13 of the Directive contains a list of cases where limitations on public access can be set. With regards to providing the metadata for 
	the datasets and services through discovery services, the limitations on public access can be set on the base of reasons of international 
	relations, public security or national defence. Concerning providing View, Download or Transformation Services, or e-commerce services, 
	limitations on public access can be set on the base of the following reasons:

	* the confidentiality of the proceedings of public authorities, where such confidentiality is provided for by law;
	* international relations, public security or national defence;
	* the course of justice, the ability of any person to receive a fair trial or the ability of a public authority to conduct an enquiry of a criminal or disciplinary nature;
	* the confidentiality of commercial or industrial information, where such confidentiality is provided for by national or Community law to protect a legitimate economic interest, including the public interest in maintaining statistical confidentiality and tax secrecy;
	* intellectual property rights;
	* the confidentiality of personal data and/or files relating to a natural person where that person has not consented to the disclosure of the information to the public, where such confidentiality is provided for by national or Community law;
	* the interests or protection of any person who supplied the information requested on a voluntary basis without being under, or capable of being put under, a legal obligation to do so, unless that person has consented to the release of the information concerned;
	* the protection of the environment to which such information relates, such as the location of rare species.

	This element shall **only** include information regarding access to the resource (not the use of the data, which is documented under the `Use constraints <#use-constraints>`__ section). When Member States limit public 	access to spatial data sets and spatial data services under Article 13 of Directive 2007/2/EC, this metadata element shall provide information on the limitations and the reasons for them. If there are no limitations on public access, this metadata element shall indicate that fact.
	
|userdoc_fig_7_14_1_LimitationsPublicAccess|

Lineage
--------
:Gemini: `Lineage <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#10>`__
:INSPIRE: Lineage
:ISO19115: DQ_DataQuality.lineage > LI_Lineage.statement
:Obligation: Mandatory
:occurrence: One

:Definition:
	A sub-element of `data quality <#data-quality>`__ that should provide information about the events or source data used in the creation of the data resource.   This will be useful in determining whether the data is fit for purpose.

:Guidance:
	The lineage differs from the `abstract <#abstract>`__ in that it covers 'how' the dataset was created as opposed the 'what' and 'why' of the 
	dataset. A brief technical description should be given noting any sources and processes used. Any procedures or protocol associated with the 
	update of the dataset should also be noted, along with notes on previous updates.

|userdoc_fig_7_15_1_Lineage|



Metadata date stamp
-------------------
:Gemini: `Metadata date <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#30>`__
:INSPIRE: Metadata date
:ISO19115: MD_Metadata.dataStamp
:Obligation: Mandatory
:occurrence: One

:Definition:
	The date on which the metadata was last updated.

:Guidance:
	This element is not editable and is set by the editor when the file is saved. It is used by `spatialdata.gov.scot <https://www.spatialdata.gov.scot>`__ and `data.gov.uk <https://data.gov.uk>`__ to determine if metadata 
	with the same field identifier (UUID) has been changed. A single date is specified in the extended format YYYY-MM-DD, where YYYY is the year, 
	MM is the month and DD is the day.

|userdoc_fig_7_18_1_MetadataDate|

Metadata language
-----------------
:Gemini: `Metadata language <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#33>`__
:INSPIRE: Metadata language
:ISO19115: MD_Metadata.language
:Obligation: Mandatory
:occurrence: One

:Definition:
	The language used to document the metadata. The purpose of this element is to identify the language used in a multi-lingual metadata service, 
	for example in the INSPIRE geo-portal.

:Guidance:
	Selected a language from the drop down menu listing entries from the ISO 639-2 code list.  For INSPIRE compliance, this has to be an 
	`official language of the European Community <http://ec.europa.eu/languages/policy/linguistic-diversity/official-languages-eu_en.htm>`__, 
	of which English (eng) is the only one in common use across the UK (and is the default in the SSDI). For non-INSPIRE metadata records, it can 
	be any ISO 639-2 three letter code, of which the relevant entries for the UK are English (eng), Welsh (cym), Gaelic (Irish) (gle), Gaelic 
	(Scottish) (gla), Cornish (cor), Ulster Scots (sco).

|userdoc_fig_7_20_1_MetadataLanguage|

Metadata point of contact
-------------------------
:Gemini: `Metadata point of contact <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#35>`__
:INSPIRE: Metadata point of contact
:ISO19115: MD_Metadata.contact > CI_ResponsibleParty
:Obligation: Mandatory
:occurrence: Many

:Definition:
	This element records the details of the organisation(s) responsible for the creation and maintenance of the metadata record. The structure of 
	this element is the same as the `Point of contact <#point-of-contact>`__ element. There are eight sub-elements:
	
	* Organisation name
	* Position name (i.e. job role or position of the responsible person or business area)
	* Voice (i.e. telephone number)
	* Facsimile (i.e. facsimile number)
	* Address (i.e. postal address as defined by Royal Mail)
	* Electronic mail address (i.e. email address)
	* Resource locator (i.e. web address of the organisation)
	* Role (of the responsible party with respect to the metadata)

:Guidance:
	Of the eight sub-elements, only the **organisation name**, **email address** and **role** are mandatory. All other sub-elements are optional. 
	With regards to the *organisation name*, this should be provided in full without abbreviations. In terms of the *role*, for INSPIRE purposes
	this must be set to *point of contact*.
	
	For *position name*, a general job title (e.g. Data Manager) should be identified rather than individuals which are subject to change without 
	notice and difficult to maintain. Likewise, email addresses should be provided for branch or team (i.e. shared) mailboxes where possible rather 
	than for individuals.
	
	If the user has stored contact details in a `directory entry <UserDoc_Chap5_Create.html#creating-directory-metadata>`__ on the portal, details can be auto-populated by 
	searching for the contact in the search box below the element. 
	
|userdoc_fig_7_17_1_MetadataContact|


Metadata standard name
----------------------
:Gemini: `Metadata standard name <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#54>`__
:INSPIRE: N/A
:ISO19115: MD_Metadata.metadataStandardName
:Obligation: Optional in GEMINI but required in `spatialdata.gov.scot <https://www.spatialdata.gov.scot>`__
:occurence: One

:Definition:
	Name of the metadata standard or profile used, cited with a reference to the appropriate register entry. 

:Guidance:
	This element is required in `spatialdata.gov.scot <https://www.spatialdata.gov.scot>`__ and must be set to `UK GEMINI <http://vocab.nerc.ac.uk/collection/M25/current/GEMINI/>`__ when importing metadata records into the portal. For records created within the portal from templates, this element will be automatically filled in, and will not be editable in the default editing view.
	
	
Metadata standard version
-------------------------
:Gemini: `Metadata standard version <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#55>`__
:INSPIRE: N/A
:ISO19115: MD_Metadata.metadataStandardVersion
:Obligation: Optional in GEMINI but required in `spatialdata.gov.scot <https://www.spatialdata.gov.scot>`__
:occurence: One

:Definition:
	Version of the metadata standard (profile) used.

:Guidance:
	This element is required in `spatialdata.gov.scot <https://www.spatialdata.gov.scot>`__ and must be set to **2.3** when importing metadata records into the portal. For records created within the portal from templates, this element will be automatically filled in, and will not be editable in the default editing view.

|userdoc_fig_7_32_1_MetadataStandard|
	
	
Parent identifier
-----------------
:Gemini: `Parent identifier <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#49>`__
:INSPIRE: N/A
:ISO19115: MD_parentidentifier.scope
:Obligation: Optional
:occurrence: One

:Definition:
	File identifier of the metadata that is a parent to this child metadata. It supports parent-child relationships in metadata and allows navigation from a dataset record to the series record of which it forms a part. 

:Guidance:
	Only to be used if the dataset is part of a series. To add a parent identifier, click |button_edit_addparent| and add the Unique Identifier for the parent record.

|userdoc_fig_7_33_1_ParentIdentifier|



Resource locator
----------------
:Gemini: `Resource locator <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#19>`__
:INSPIRE: Resource locator
:ISO19115: MD_Distribution > MD_DigitalTransferOptions.online > CI_OnlineResource.linkage
:Obligation: Conditional
:occurrence: Many

:Definition:
	Location (address) for on-line access to the resource using a Uniform Resource Locator (URL). This element should point to where the dataset 
	may be accessed, and may be different from where it may be ordered online (which should be included in the web address of the distributor).  

:Guidance:
	This element should primarily be used to enter URLs for web services (i.e. WMS, WFS, etc.), however, links to web pages offering more 
	information or other services (e.g. interactive mapping applications) can also be added. To add an online resource, follow the instructions 
	provided in the `Associated resources <UserDoc_Chap6_Edit.html#associated-resources>`__ section. Once an online resource has been added, it can be edited as normal
	in the editing form. Note that for web services to be displayed in the interactive map, the **protocol**, **layer name** and **description** 
	must be entered. The layer name **must** match that as defined in the GetCapabilities request of the service.
	
|userdoc_fig_7_21_1_OnLineResource|

Resource type
---------------
:Gemini: `Resource type <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#39>`__
:INSPIRE: Resource type
:ISO19115: MD_Metadata.hierarchyLevel
:Obligation: Mandatory
:occurrence: One

:Definition:
	Scope to which the metadata applies (i.e. dataset, series, service).

:Guidance:
	Identify whether resource is a dataset or a series (collection of datasets with a common specification). For metadata created on `spatialdata.gov.scot <https://www.spatialdata.gov.scot>`__, this element is set by the 
	choice of template and should not be changed.

|userdoc_fig_7_5_1_HierarchyLevel|

Responsible organisation
------------------------
:Gemini: `Responsible organisation <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#23>`__
:INSPIRE: Responsible party
:ISO19115: MD_Identification.pointOfContact
:Obligation: Mandatory
:occurrence: Many

:Definition:
	This element records the details of the organisation(s) responsible for the creation, maintenance and distribution of the data resource. The 
	structure of this element is the same as the `Metadata contact <#metadata-contact>`__ element. There are eight sub-elements:
	
	* Organisation name
	* Position name (i.e. job role or position of the responsible person)
	* Voice (i.e. telephone number)
	* Facsimile (i.e. facsimile number)
	* Address (i.e. postal address as defined by Royal Mail)
	* Electronic mail address (i.e. email address)
	* Resource locator (i.e. web address of the organisation)
	* Role (of the responsible party with respect to the resource)

:Guidance:
	Of the eight sub-elements, only the **orgnaisation name**, **email address** and **role** are mandatory. All other sub-elements are optional. 
	With regards to the *organisation name*, this should be provided in full without abbreviations. In terms of the *role*, if a responsible party
	is both the creator, publisher and distributor of the resource then the role should be set to *Publisher*. If the resource was created by a 
	party other than the provider this should also be recorded, using the role value *Originator*.
	
	For *position name*, a general job title (e.g. Data Manager) should be identified rather than individuals which are subject to change without 
	notice and difficult to maintain. Likewise, email addresses should be provided for branch or team (i.e. shared) mailboxes where possible rather 
	than for individuals.

	If the user has stored contact details in a `directory entry <UserDoc_Chap5_Create.html#creating-directory-metadata>`__ on the portal, details can be auto-populated by 
	searching for the contact in the search box below the element.

|userdoc_fig_7_22_1_PointofContact|

Spatial reference system
----------------------------
:Gemini: `Spatial reference system <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#17>`__
:INSPIRE: n/a
:ISO19115: MD_ReferenceSystem.referenceSystemIdentifier > RS_Identifier.code
:Obligation: Mandatory
:occurrence: Many

:Definition:
	Identifier, name or description of the system of spatial referencing, whether by coordinates or geographic identifiers, used in the data 
	resource.

:Guidance:
	The reference system should be recorded referencing a well known common register (e.g. `EPSG Geodetic Parameter Registry <http://epsg-registry.org/>`__) in a URL link format. For INSPIRE purposes the **first entry** must be one of the reference systems listed in Annex D.4 (Default Coordinate Reference Systems) of the `INSPIRE Metadata Technical Guidelines <https://inspire.ec.europa.eu/Technical-Guidelines2/Metadata/>`__. For this reason it is recommended that ETRS89 is included as the first entry, and if desired British National Grid as a secondary entry. Failure to do so will result in a validation error.
	
	The box below the element can be used to search for and add additional reference systems.

|userdoc_fig_7_23_1_ReferenceSystem|

Spatial representation type
----------------------------
:Gemini: `Spatial representation type <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#50>`__
:INSPIRE: Spatial representation type
:ISO19115: MD_DataIdentification.spatialRepresentationType 
:Obligation: Mandatory
:occurrence: Many

:Definition:
	The method used to spatially represent geographic information.

:Guidance:
	This element uses the MD_SpatialRepresentationTypeCode from ISO 19115. Available options are *vector* (the defualt), *grid* (for images and coverage data), *tin* (surface data), and *text, table* (for datasets with an indirect spatial reference).

|userdoc_fig_7_34_1_SpatialRepresentationType|

Spatial resolution - Distance
-----------------------------
:Gemini: `Spatial resolution <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#18>`__
:INSPIRE: Spatial resolution
:ISO19115: MD_Identification.spatialResolution > MD_Resolution.distance
:Obligation: Conditional
:occurrence: Many

:Definition:
	A distance measure of the granularity (in metres), providing an indication of how detailed the data is. It is equivalent to the ground sample 
	distance and should not be confused with the scale of a map (which is purely a display attribute).

:Guidance:
	Enter values that are real numbers, greater than 0, and specified in metres. Commonly used distances can be added from the recommended values 
	drop down next to the element. For data captured in the field, it is the precision at which the data is captured (this may be the accuracy for 
	topographic surveys, or the average sampling distance in an environmental survey). For data taken from maps, it is the positional accuracy of 
	the map, while for image data it is the resolution of the image.

|userdoc_fig_7_24_1_SpatialResDistance|

Spatial resolution - Equivalent scale
-------------------------------------
:Gemini: `Equivalent scale <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#43>`__
:INSPIRE: Equivalent scale
:ISO19115: MD_Identification.spatialResolution > MD_Resolution.equivalentScale > MD_RepresentativeFraction.denominator
:Obligation: Optional
:occurrence: Many

:Definition:
	The level of detail expressed as the scale denominator of a comparable hardcopy map or chart.

:Guidance:
	Where the data is captured from a map, the scale of that map should be recorded as a positive integer. Note that `distance <#spatial-resolution-equivalent-scale>`__
	is the preferred expression for spatial resolution. The equivalent scale should only be given when the distance cannot be determined.
	
|userdoc_fig_7_25_1_SpatialResEqScale|


Title
-----
:Gemini: `Title <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#1>`__
:INSPIRE: Resource title
:ISO19115: MD_DataIdentification.citation > CI_Citation.title
:Obligation: Mandatory
:occurrence: One

:Definition:
	The name given to the data resource.  

:Guidance:
	This should be the formal or product name if one exists. Otherwise the title should be created that is short, encapsulates the subject, 
	temporal and spatial coverage of the data resource, and does not contain terms or jargon that make it incomprehensible.

|userdoc_fig_7_27_1_Title|

Topic category
--------------
:Gemini: `Topic category <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#5>`__
:INSPIRE: Resource topic category
:ISO19115: MD_DataIdentification.topicCategory
:Obligation: Mandatory (datasets), N/A (services)
:occurrence: Many

:Definition:
	Describes the main theme(s) of the data resource, using `topic categories in accordance with ISO 19115 standard <http://inspire.ec.europa.eu/metadata-codelist/TopicCategory>`__.

:Guidance:
	Select from the drop down list one or more categories that most closely represent the topic of the data resource. This element is only meant to 
	represent the general theme of the information. `Keywords <#keywords>`__ should be used to provide greater detail on the nature of the dataset.
	While more than one topic category can be applied, only a limited number of most relevant should be chosen (e.g. topographic maps should not 
	be classified as farming). Multiple topic categories can be added.
	
	Note that the choice of topic category will dictate which categories the data resource is listed under on the **Browse by topics** section of 
	the homepage.

|userdoc_fig_7_28_1_TopicCategory|
	
Use constraints
---------------
:Gemini: `Use constraints <https://www.agi.org.uk/agi-groups/standards-committee/uk-gemini/40-gemini/1062-gemini-datasets-and-data-series#26>`__
:INSPIRE: Conditions applying to access and use
:ISO19115: MD_Identification.resourceConstraints > MD_LegalConstraints.useConstraints & otherConstraints
:Obligation: Mandatory
:occurrence: Many

:Definition:
	Restrictions and legal constraints on **using** the data resource. This can be entered as a free text statement, or link to a URL containing 
	the information.
	
:Guidance:
	Use constraints are different from `limitations on public access <#limitations-on-public-access>`__ which describe limitations on access to the 
	data. A data resource can be openly accessible (which all INSPIRE data should be), but have restrictions on its use such as licensing, fees, or 
	usage limitations. 

	This element comprises two sub-elements: the 'use constraints' which should be set to *other restrictions*, and 'other constraints' which can be free text or a URL link.

	**1|** useConstraints- should contain an MD_RestrictionCode element with code list value "otherRestrictions"

	**2|** otherConstraints- a free text element describing the usage restrictions or link to a URL, as below.
	
	To link to a URL in the otherConstraints element, click the |button_edit_plusdrop| button and choose either the *anchor* option. All records 
	on `spatialdata.gov.scot <https://www.spatialdata.gov.scot>`__ should document the licencing arrangements for the data resource using the anchor type. Where possible, this should link to a URL 
	such as the `Open Government Licence <http://www.nationalarchives.gov.uk/doc/open-government-licence/>`__, 
	`Non-Commercial Government Licence <http://www.nationalarchives.gov.uk/doc/non-commercial-government-licence/>`__,
	or `INSPIRE End User Licence <https://www.ordnancesurvey.co.uk/documents/licensing/inspire-end-user-licence.pdf>`__. 
	Users can further categorise their records in terms of licence type by following the guidance in the `assigning a licence category <UserDoc_Chap6_Edit.html#assigning-a-licence-category>`__ section.

