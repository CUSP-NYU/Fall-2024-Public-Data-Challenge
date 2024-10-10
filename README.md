# Fall-2024-Public-Data-Challenge

# CUSP Fall 2024 Public Data Challenge

The Center for Urban Science + Progress (CUSP) at NYU Tandon is excited to host a Public Data Challenge on Saturday, October 19, 2024 for students in the M.S. in Applied Urban Science and Informatics program. Over the course of one day, students engage with datasets and navigate the complexities of real-world scenarios, transforming information into actionable insights. Students work alongside peers, faculty mentors, and project sponsors, creating lasting connections that extend far beyond the duration of the event.

### About this overview

This overview contains the following information:

- [Event Details](#event-details)
    - [Eligibility](#Eligibility)
    - [Key Dates](#key-dates)
    - [Event Location](#event-location)
    - [Expectations for Final Presentations](#expectations-for-final-presentations)
    - [Evaluation Criteria](#evaluation-criteria)

- [Challenges](#challenges)
    - [International Center for Community Land Trusts](#international-center-for-community-land-trusts)
    - [New York State Office of Parks, Recreation and Historic Preservation](#new-york-state-office-of-parks-recreation-and-historic-preservation)
    - [The Municipal Art Society](#the-municipal-art-society)
    - [Town+Gown:NYC @ NYC Department of Design and Construction](#towngownnyc-nyc-department-of-design-and-construction)


## Event Details

### Eligibility

The Fall 2024 Public Data Challenge is open to students in CUSP’s M.S. in Applied Urban Science and Informatics program. 


### Key Dates

Wednesday, October 16 at noon
Deadline for students to submit questions in advance to our partnering sponsors via this Google Form. Answers will be published on the Public Data Challenge Repository on Github as they are made available, no later than Saturday, October 19 before the challenge.

Saturday, October 19
Date of the Fall 2024 Public Data Challenge at 370 Jay Street in the 12th Floor Seminar Room, from 11:00 AM to 6:00 PM. Lunch and snacks will be provided for all participants.

Monday, October 28
Feedback from project sponsors will be shared with the teams, and the projects with the highest scores based on the sponsors’ evaluations will be announced.


### Event Location

The Fall 2024 Public Data Challenge will take place in Room 1201 at 370 Jay St. Brooklyn, NY 11201.


### Expectations for Final Presentations

Final presentations may include code, visualizations, and/or written summaries. All work must be original, with clear citations for any references used. Each submission must also include a list of all team members and their specific roles.


###  Evaluation Criteria

Project sponsors will act as judges and evaluate each presentation using the following questions: 

- Is the proposed solution relevant to the original problem statement?
- Is the proposed solution innovative? 
- Does the proposed solution have the potential to make an impact?
- Is the proposed solution technically rigorous?
- Is the final presentation clear and engaging?

Outstanding projects will be featured on CUSP’s website and communication channels.


# Challenges

## [New York State Office of Parks, Recreation and Historic Preservation](https://parks.ny.gov)

### Problem statement

The New York State Office of Parks, Recreation, and Historic Preservation has awarded thousands of grants for open space, trails, and park development. The information related to these grants have been stored in an Access database, and records related to each grant project, such as paper maps and deeds, have been stored in paper files around the state. Some records are incomplete. The State has a responsibility to manage these grant-funded properties to ensure public access to open space and recreation. However, it is difficult for the State to determine where all of these properties are due to incomplete records, name changes to parks and sites, and decentralized storage of paper records.


## Overview of the open datasets and links

Data for this project can be accessed on CUSP's Research Computing Facility (RCF). It includes:

- Office of Parks, Recreation & Historic Preservation (OPRHP) Grants Access database, which is used by the Grants Bureau to track and report on grant data
- New York Protected Areas Database (NYPAD), a database of protected lands in New York State. We would like to be able to view our project location data in a similar format
- Empire State Development (ESD) Consolidated Funding Application(CFA) Project Location Report, which includes OPRHP grant location data including longitude and latitude


## Goals and desired outcomes for the Public Data Challenge

The New York State Office of Parks, Recreation, and Historic Preservation would like to develop a GIS-layer to identify all of the grant-funded properties from around the State to more easily manage responsibilities related to conserving open space and outdoor recreational space. The first step toward this goal is to organize the existing data for all grant funded properties, including property names (including all aliases), the year and project of the grant funding received, and location information (City, Town Village, County, Address, etc), and then obtain GPS coordinates (lat/long) of each property.



## [The Municipal Art Society](https://www.mas.org) 

### About The Municipal Art Society (MAS)
The Municipal Art Society of New York lifts the voices of the people in the debates that shape New York’s built environment and leads the way toward a more livable city from sidewalk to skyline. Our research focuses on the intersection of urban design, planning, and policy. MAS works to leverage public partnerships, democratize data, and advocate for citywide systems change. For more information, visit [The Municipal Art Society website](https://www.mas.org/initiatives/). 

### Problem Statement
New York City contains many different types of publicly accessible open spaces, from large parks and natural areas to neighborhood playgrounds, community gardens, and plazas. It is widely recognized that some neighborhoods are endowed with a range of well-maintained open spaces while others are not. Recent research from organizations like New Yorkers for Parks and The Trust for Public Land underscores the disparities. The challenge is that when it comes to fully analyzing this important amenity, there is no single dataset or web tool that sufficiently aggregates all types of publicly accessible open space and allows researchers and advocates to more accurately evaluate quality and distribution. Information is not centrally located and resources are published separately by a multitude of governmental agencies. There are also inconsistencies in how different entities define “open space.” Together, these issues lead to an incomplete and inconsistent picture of open space in New York City and uninformed policy decisions about where and how to invest in it. 

### Datasets 
New York City’s Open Data Portal contains information about different types of open space in separate datasets published by the City agencies that own and maintain the sites, such as the Department of Parks and Recreation (NYC Parks), Department of Transportation (DOT), and the Department of Environmental Protection (DEP). Other spaces are operated by State agencies, the federal government, or private parties. Below is a non-exhaustive list of key datasets to examine.

- [NYC Parks Properties, Preserves, and Natural Areas](https://www.nycgovparks.org/about/data)
- [NYS Parks Property](https://data.gis.ny.gov/datasets/nysparks::ny-state-parks-property/about)
- [DOT Plazas](https://data.cityofnewyork.us/Transportation/NYC-DOT-Pedestrian-Plazas/k5k6-6jex/about_data) 
- [DOT Open Streets](https://data.cityofnewyork.us/Health/Open-Streets-Locations/uiay-nctu/about_data)
- [DCP Privately Owned Public Spaces (POPS)](https://data.cityofnewyork.us/City-Government/Privately-Owned-Public-Spaces-POPS-/rvih-nhyn/about_data)
- [Community Gardens that participate in NYC Park’s GreenThumb program](https://data.cityofnewyork.us/browse?Data-Collection_Data-Collection=GreenThumb+Gardens&q=greenthumb )
- [NYC Parks/DOE Schoolyards to Playgrounds](https://data.cityofnewyork.us/dataset/Schoolyard-to-Playgrounds/dbmp-698d)

The City has also made available a number of planimetric layers related to parks, plazas, and other open space.


### Goals and Desired Outcomes

This data dive challenges participants to develop a single, comprehensive dataset of all open spaces in New York City. The dataset should include as much information as possible pertaining to the type (e.g., neighborhood park, playground, community garden, etc.) and size of each open space, its location, relevant features (e.g., sports fields, benches) and any other relevant information that allows organizations like MAS to more fully understand open space quality and availability across New York City neighborhoods. 

In order to do this, participants will need to:  

- Propose a definition for open space in the context of New York City 
- Understand existing open space datasets
- Utilize this knowledge to develop deliverable(s) that should include, but not be limited to: 
    - A comprehensive dataset containing open spaces of all types and that span multiple governmental jurisdictions.
    - A summary of the complexities and shortcomings of the data, and proposals for improvement. For example, how can we identify open spaces in the city that are truly accessible to the public? Does compiling datasets alone exclude any unconventional spaces that should be included? Are there methods or strategies for streamlining the data compilation?


## [International Center for Community Land Trusts](https://cltweb.org/)

### About the International Center for Community Land Trusts
The International Center for Community Land Trusts is a not-for-profit nongovernmental organization established in 2018 to promote and to support community land trusts and similar strategies of community-led development on community-owned land in countries throughout the world. The Center provides the following services:

- Collecting and curating historical materials documenting the origins and evolution of the
worldwide CLT movement;
- Conducting, cataloging, and disseminating academic and non-academic research;
- Producing case studies, directories, guides, and other educational materials; and
- Providing training, referral, and technical assistance for organizers and practitioners
working with CLTs and similar strategies for the equitable and sustainable development
of place-based communities.
- Publishing books and monographs under its imprint Terra Nostra Press.

### Problem Statement 
As part of nternational Center for Community Land Trusts' Legal Collaborative project, the organization has been developing The CLT State Law Database Project, a database of state statutes in the US that relate to community land trusts. An an early beta version of this database can be viewed [here](https://cltweb.org/state-laws-us/). 

The preiliminary development road consists of: 

- Beta Version (current): spreadsheet data in Airtable (table and card views)
- Version 1.0: expanded to include research from Vermont and NYU law schools (which will be completed by December 2024), with a chatbot front-end that solely references this data source. If we are able to get a little fancier, we could also include a map-based interface to make it easier to zoom in on specific states.
- Version 2.0: chatbot front-end that expands data sources to include publicly available datasets for state and municipal laws, curated scholarly articles, and model statute/ordinance language provided by subject matter experts.
- Version 3.0: expanded to include international datasets and accessibility for multiple
languages.

This challenge will focus on architecting Version 1.0, as well as refining the road map overall.


### Use Case and User Profiles
| Use Case                                                                                     | User Profiles                                           |
|----------------------------------------------------------------------------------------------|--------------------------------------------------------|
| Persons looking for examples of laws to help them draft new laws for their state or locality. This is particularly important for community land trusts in areas with few or no established laws.<br>Persons seeking information on existing laws applicable to their location, assisting with identifying funding sources, permitted legal practices, etc.<br>Students or faculty researching community land trusts. | Law school clinical faculty and students<br>Practicing attorneys<br>CLT practitioners (non-attorneys)<br>Local, county, and state policymakers/government staff |


## Town+Gown:NYC @ NYC Department of Design and Construction

### About Town+Gown:NYC
Town+Gown:NYC @ NYC Department of Design and Construction [Town+Gown](https://www.nyc.gov/site/ddc/about/town-gown.page) is a city-wide research program in the Built Environment that develops and supports applied research projects, using NYC's built environment as a laboratory for the research and brings academics and practitioners together on research projects to support practice and policy change based on research results.

T+G’s Utilidor Working Group [Town+Gown Working Groups](https://www.nyc.gov/site/ddc/about/town-gown-working-groups.page) has supported various analyses, including life cycle cost benefit analysis modeling of implementing utilidors (or multi-utility tunnels) and analysis and modeling to identify opportunities for implementing utilidors as one innovative subsurface design solution to support changes to current practice of direct burial of subsurface utility distribution infrastructure.


### Problem Statement 
T+G’s Utilidor Working Group Town+Gown Working Groups (nyc.gov) has supported various analyses, including life cycle cost benefit analysis modeling of implementing utilidors (or multi-utility tunnels) and analysis and modeling to identify opportunities for implementing utilidors as one innovative subsurface design solution to support changes to current practice of direct burial of subsurface utility distribution infrastructure.

Capital projects to repair and/or upgrade public and private utility aging subsurface distribution infrastructure, known as state of good repair (SOGR) projects, compete with other utility capital needs.  They are also buried under the street requiring excavation to conduct SOGR activities, which make SOGR expensive and thus done less than at optimal levels. Traditional key performance indicators (KPIs) for aging subsurface infrastructure lead to practices that extend their useful lives within targeted maximum failure rates.

This infrastructure includes electricity, gas, steam, telecommunications, water and sewer distribution pipes.  It is vulnerable to aging, extreme weather and climate change. Aging distribution infrastructure is a hazard like natural and manmade hazards but is not included in hazard analysis. Traditional KPIs lead to institutional practices to extend assets’ useful lives within targeted maximum failure rates, which expect infrastructure failures and do not include consideration of the impacts on communities where failures occur.  

There is little reliable subsurface asset locational and condition data at the utilities, much less publicly available.  Surface data observations, however, can suggest subsurface infrastructure vulnerability from aging subsurface infrastructure and has, in smaller research projects demonstrating proof of concepts, been deployed via mapping tools to analyze subsurface vulnerabilities as well as to analyze the impacts of failures in the neighborhoods they occur.  This project would expand on all prior smaller projects and apply them to create a city-wide mapping analysis tool to suggest areas of interest for potential utilidor implementation and assess the impact of failures in communities.


### Data Overview and Challenge Goal with Desired Outcomes

Publicly available surface data can suggest subsurface infrastructure vulnerability and, with other data, permit assessment of community impacts of failures.  A city-wide analytical model with data visualization features would enable the city to plan for future subsurface use and bring the community impact from failures into related policies and practices.

This challenge will help determine whether city-wide scale surface and other data can be used in the absence of available subsurface infrastructure location and condition data to help the city develop policies and practices for better subsurface use planning and to bring the impacts in communities from failures into the policy and practice development?

Much of the prior work on smaller scales had been done with publicly available data, which can be used and scaled to this project to suggest subsurface infrastructure vulnerability and potential locations for utilidors across the city.  Scaling this work to the city-wide scale for all 5 boroughs is the initial challenge goal for the Fall 2024 Public Data Challenge.  Datasets used on prior projects included:

- Excavation—or cut--permit data suggest where private utility subsurface vulnerabilities exist; can also help point to where disruptions should be avoided via utilidors; and implies partial road closures a disruptive element
- Street pavement condition rating data suggest where excavations have led to roads not meeting design life and requiring more roadway resurfacings; also suggest potential subsurface condition issues
- SCOUT data elements below to augment street pavement condition rating data above and suggest additional potential vulnerabilities/disruptions:
    - Water Maintenance - Running Hydrant (DEP): Fire hydrant leaking or running at full force
    - Sidewalk Condition - Sidewalk Concrete Pedestrian (DOT): Sidewalk with a hole large enough and deep enough to cause immediate harm to a pedestrian
    - Sewer Maintenance - Street Cave-In (DEP): A collapse of the roadway surface in which the pavement has cracked apart and fallen into a deep empty space without a solid bottom
    - Sewer Maintenance - Catch Basin Sunken (DEP): Sunken, raised, damaged or defective storm drain
    - Street Condition - Pothole (DOT): An irregularly shaped, usually circular or ovular, hole in the street with a definable bottom
    - Street Condition - Failed Street Repair (DOT): Utility cut no longer level with the surrounding street surface. Utility cuts are usually square or rectangular in shape
    - Street Condition - Defective Hardware (DOT): Street hardware such as, but not limited to, electric vaults, that are cracked, missing, above grade or below grade and generally could be a trip hazard or other danger
- Major NYC budgeted and scheduled roadway projects by DEP, DOT and DDC from https://capitalplanning.nyc.gov/map/capitalprojects#10/40.7128/-74.0807.  There will be disruptions from these projects and these projects are intended to address SOGR issues.
- 311 data (do not include any operational info related to complaint, just the occurrence time and location):
    - Water leaks
    - Sewer backups
    - Street cave-ins or just cave-ins
    - Crashes, which, if located near cut permits or NYC projects, could relate to construction pit obstructions, disruptions to mobility
    - Noise-construction relates to excavation activities
    - Downed electrical and telecom wires in Queens related to ConEd’s undergrounding projects in Queens (opportunities for utilidors)
    - Notice of claims data to show where disruptions actually happened in the past (available for the challenge but prior projects did not get to use this data)

If the challenge results in a successful proof of concept, students who are interested in continuing the work could bring in other data (some public, some private).  For example, there is a private subsurface mapping tool with public access at a low level of confidence (as compared to the levels possible with funds) that could underlay the surface data mapping.  There is Notice of Claims data to begin the community impact analysis, which prior projects did not get to.  It might be possible to obtain credit card data and/or cell phone data to add more analysis of impacts of failures on local businesses.  It is possible that students could have access to traffic data from Streetlight to analyze the traffic impacts from failure.

If a team of students wish to continue this work after the Challenge, the analytical model with visualization capabilities developed by the team should be in a format that would permit the city to update it as more data becomes available.
