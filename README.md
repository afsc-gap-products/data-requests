<!-- README.md is generated from README.Rmd. Please edit that file -->

# [AFSC RACE Groundfish and Shellfish Assessment Program Data Request Tracking System](https://github.com/afsc-gap-products/data-requests) <img src="https://avatars.githubusercontent.com/u/91760178?s=96&amp;v=4" alt="Logo." align="right" width="139" height="139"/>

[![](https://img.shields.io/github/last-commit/afsc-gap-products/gap_products.svg)](https://github.com/afsc-gap-products/gap_products/commits/main)

`data-requests`: This is a repository dedicated to use only for communication about data requests via GitHub issues. 

> The code in this repository is regularly being updated and improved. Please refer to [releases](https://github.com/afsc-gap-products/data-requests/releases) for finalized products and project milestones.

## This code is primarily maintained by:

**The Groundfish Assessment Program** (afsc.gap.metadata@noaa.gov;
[@afsc-gap-products](https://github.com/afsc-gap-products))

**Nancy Roberson** (Nancy.Roberson AT noaa.gov;
[@NancyRoberson](https://github.com/NancyRoberson))

Alaska Fisheries Science Center (AFSC) National Oceanic and Atmospheric Administration (NOAA)  
Resource Assessment and Conservation Engineering Division (RACE)  
Groundfish Assessment Program (GAP)

7600 Sand Point Way N.E., bldg. 4  
Seattle, WA 98115 USA

## User Resources

- [Data Access Documentation for All Production Data](https://afsc-gap-products.github.io/gap_products/)
- [Fisheries One Stop Shop (FOSS)](https://www.fisheries.noaa.gov/foss)
- [Groundfish Assessment Program Bottom Trawl Surveys](https://www.fisheries.noaa.gov/alaska/science-data/groundfish-assessment-program-bottom-trawl-surveys)
- [AFSC’s Resource Assessment and Conservation Engineering Division](https://www.fisheries.noaa.gov/about/resource-assessment-and-conservation-engineering-division)
- [Survey code books](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual)
- [Publications and Data Reports](https://repository.library.noaa.gov/)
- [Research Surveys conducted at AFSC](https://www.fisheries.noaa.gov/alaska/ecosystems/alaska-fish-research-surveys)

## Making a request

If you are interested in a subset of the raw data, or a data product, first peruse our [public data portal](https://www.fisheries.noaa.gov/foss/f?p=215:200:1801780733911:Mail:NO:::) to see if the haul and catch data there are sufficient. 

If that does not fulfill your needs, [submit your request as an issue](https://github.com/afsc-gap-products/data-requests/issues) to this repository. Note that requests for querying historical raw data will be filled more quickly and with more regular periodicity than requests for derived data products that require new analysis (and depending on the time needed for this development, the latter may require discussions of the nature of the collaboration as noted in the section below "Credit for data and analysis"). 

If possible, include the following information:

1. Data product requested (stratum CPUE, etc.)
2. Species
3. Region (GOA, AI, Bering Sea)
4. Time frame
5. Research team making the request (PI /requester name, and tag team members with GitHub accounts, or email addresses if requestor does not have a GitHub account)

To better understand what data are available and how to interpret the data you receive, please see the full [documentation](https://afsc-gap-products.github.io/gap_products/) and [metadata](https://www.fisheries.noaa.gov/inport/item/22008), and review our [survey codebooks](https://www.fisheries.noaa.gov/resource/document/groundfish-survey-species-code-manual-and-data-codes-manual).

## Fulfilling a request

If you are a GAP scientist providing data to a requester, when you are done,

1) **Comment on the issue** for that request with code or a link to the code you used to generate that data product. If it is something very standard like a CPUE table, there's no need to post the code, just note which script or static table you used.

2) **Deposit the data** in our [Google Drive folder](https://drive.google.com/drive/folders/1hfNhfOmIDC7dSigbsz4P3amZWj4jMv_u?usp=sharing) and prefix it with the issue number (e.g., `5_salmon_shark/`). If you don't have access to this folder, contact Lewis, Duane, or Ned. Once the data request has been fulfilled, make a note on the issue and close it.

## Credit for data and analysis
Adapted from Stan's [note](https://github.com/afsc-gap-products/data-requests/issues/3) to the groundfish team:

The AFSC Groundfish Assessment Program (GAP) staff produces important data for research and management of fishery resources and, as a result of these vast collections, we are often the recipients of data requests. Some of these data requests are routine and minor and don't take much time or effort. Other data requests can be large, require custom processing, and can take a great deal of time, effort, and skill. In all instances when GAP-produced data is used, GAP and/or GAP employees should be acknowledged for the time and effort to produce the data. 

These acknowledgments can take the form of a “thank you” note in informal documents or websites, to co-authorship or formal acknowledgments in scientific papers. **In every instance, the Groundfish Assessment Program and the scientist(s) responding to the data request need to be recognized for their efforts. The form of acknowledgment should depend on the product GAP data was used for and on the GAP employee contribution (e.g. data only, data & data-products (graphs, tables, figures), data & interpretation or data and writing).** 

**GAP employees** are encouraged, when providing data products to others, to ask for appropriate acknowledgment at the time of acceptance of the data request. For example, you can include a note in the email stating: “I would appreciate acknowledgment of the hard work by the personnel of AFSC Groundfish Assessment Program needed to collect the data.”

The acknowledgment in the form of co-authorship requires a significant contribution to the paper. If  you think coauthorship is appropriate to the request, make this request in your initial response to the data request. Support your request with information about your specific contribution. Stan cites Yale University's [“Guidance on Authorship in Scholarly or Scientific Publications”](https://provost.yale.edu/policies/academic-integrity/guidance-authorship-scholarly-or-scientific-publications):

>Each author should have participated sufficiently in the work to take public responsibility for its content. All co-authors should have been directly involved in all three of the following:
>
>1. Planning and contribution to some component (conception, design, conduct, analysis, or interpretation) of the work that led to the paper or interpreting at least a portion of the results;
>
>2. Writing a draft of the article or revising it for intellectual content; and
>
>3. Final approval of the version to be published.  All authors should review and approve the manuscript before it is submitted for publication, at least as it pertains to their roles in the project.

In general, if a data request requires a GAP scientist to write code for an analysis to derive a product (e.g., life-staged biomass estimates or CPUE summarized for a specific region or time frame) then it is appropriate to request coauthorship, with the above qualifications in mind. Each co-author is responsible for considering his or her role in the project and whether that role merits attribution of authorship. Co-authors should review and approve the manuscript, at least as it pertains to their roles in the project.

Discuss data requests with your supervisor and/or Program Manager and reach a decision on the effort required to complete data requests. If you feel that it should earn you co-authorship, this should be negotiated with the data requester before you fulfill the data request and be part of your Performance Plan.

## Access Constraints

**User Constraints:** Users must read and fully comprehend the metadata prior to use. Data should not be used beyond the limits of the source scale. Acknowledgment of AFSC Groundfish Assessment Program, as the source from which these data were obtained, in any publications and/or other representations of these data, is suggested.

**General questions and more specific data requests** can be sent to <afsc.gap.metadata@noaa.gov> or submitted as an [issue on our GitHub
Organization](https://github.com/afsc-gap-products/data-requests). The version of this data used for stock assessments can be found through the Alaska Fisheries Information Network (AKFIN). For questions about the eastern Bering Sea surveys, contact Duane Stevenson (<Duane.Stevenson@noaa.gov>). For questions about the Gulf of Alaska or Aleutian Islands surveys, contact Ned Laman (<Ned.Laman@noaa.gov>). For questions specifically about crab data in any region, contact Mike Litzow (<Mike.Litzow@noaa.gov>), the Shellfish Assessment Program lead.

For questions, comments, and concerns specifically about the [Fisheries One Stop Shop (FOSS)](https://www.fisheries.noaa.gov/foss) platform, please contact us using the Comments page on the [FOSS](https://www.fisheries.noaa.gov/foss) webpage.

[U.S. Department of Commerce](https://www.commerce.gov/) \| [National Oceanographic and Atmospheric Administration](https://www.noaa.gov) \| [NOAA Fisheries](https://www.fisheries.noaa.gov/)
