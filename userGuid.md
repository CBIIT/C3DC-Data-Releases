02/4/2026

Childhood Cancer Clinical Data Commons (C3DC)

User Guide

| Version | Date       | Description     | Author    |
| ------- | ---------- | --------------- | --------- |
| 1.0.0   | 03/05/2024 | Initial Release | C3DC Team |
| 1.1.0   | 05/01/2024 | Release 2       | C3DC Team |
| 1.2.0   | 07/31/2024 | Release 3       | C3DC Team |
| 1.3.0   | 11/07/2024 | Release 4       | C3DC Team |
| 1.4.0   | 03/05/2025 | Release 5       | C3DC Team |
| 1.6.0   | 06/18/2025 | Release 6       | C3DC Team |
| 1.7.0   | 10/22/2025 | Release 7       | C3DC Team |
| 1.8.0   | 02/04/2026 | Release 8       | C3DC Team |

Table of Contents

[Introduction and Overview 3](#_Toc1354454190)

[C3DC Home Page 4](#_Toc1622375588)

[C3DC Explore Page 6](#_Toc772430492)

[C3DC User Guide 7](#_Toc1265705931)

[Facet Search 8](#_Toc229948986)

[Chart Visualization 9](#_Toc1705691419)

[Table Visualization 10](#_Toc1352007949)

[Synonym Search 11](#_Toc753095238)

[CPI Participant Indicator 12](#_Toc78925181)

[Download Harmonized Data 13](#_Toc802816784)

[Cohort Selector 13](#_Toc1173264561)

[C3DC Cohort Analyzer 16](#_Toc107148101)

[Customizable Properties 17](#_Toc723771695)

[Enhanced Analytical Capabilities 18](#_Toc954829898)

[Cohort Analyzer Tutorial 18](#_Toc362764139)

[C3DC Studies Page 23](#_Toc2073277940)

[C3DC Studies Details Page 23](#_Toc1359607568)

[C3DC Data Model Page 24](#_Toc1174290140)

[C3DC Resource Page 25](#_Toc994675578)

[C3DC About Page 26](#_Toc1112127046)

[Announcements 28](#_Toc968933955)

[Release Notes 29](#_Toc1915052683)

[User Guide 30](#_Toc1376457483)

# Introduction and Overview

**The Childhood Cancer Clinical Data Commons** (C3DC) enables searching demographic and phenotypic clinical data of childhood cancers. These data have been harmonized to a standard set of common data elements (CDEs). C3DC empowers researchers to search for participant-level data to create synthetic cohorts and export data for analysis.

This document describes a high-level overview of the features of C3DC. Investigators are encouraged to explore C3DC themselves, using this guide as a primer.

# C3DC Home Page

The C3DC Home Page, located at [clinicalcommons.ccdi.cancer.gov](https://clinicalcommons.ccdi.cancer.gov/home), allows users to navigate to key sections of the application, including Explore, Cohort Analyzer, Studies, Data Model, Resources, and About pages.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-one.png)

Figure 1: C3DC Home Page (top)

At the bottom of the Home page, there are links to brief descriptions of key sections of the C3DC application.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-2.png)

Figure 2: C3DC Home Page (bottom)

# C3DC Explore Page

The Explore Page is the main interface for searching and visualizing data. Users can apply faceted filters, view dynamic chart, and inspect participant-level tables that update in real time based on selected criterial.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-3.png)

Figure 3: The Explore Page - Faceted Search (left), Visualization (top), and Data Tables (bottom)

C3DC User Guide

The "Explore the C3DC User Guide" button allows a quick access to this C3DC user manual, offering detailed feature explanations and step-by-step instructions. Additionally, users will find various use cases in this guide, making it easy to find help and learn how to navigate the system effectively.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-4.png)

Figure 4: C3DC User Guide Button in the Explore Page

Facet Search

Data is organized into seven main categories: Study, Demographics, Diagnosis, Genetic Analysis, Treatment, Treatment Response, and Survival. When you select a category, its facets open in a horizontal panel, allowing you to expand or collapse individual facets. Each category contains multiple subcategories that can be used to further refine your filters.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-5.png)

Figure 5: Performing a faceted search on the C3DC Explore Page

Chart Visualization

The **Stats Bar**, **Visualization Section**, and **Data Table** dynamically update based on applied filters.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-6.png)

Figure 6: Results returned from a faceted search in the Stats bar

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-7.png)

Figure 7: Results returned from a faceted search in six graphs in the Visualization section

- Chart visualization illustrates the proportions of each value in Race, Sex at Birth, Diagnosis, Anatomic Site, Age at Diagnosis, and Treatment Type in the form of either pie chart or histogram.
- Users can easily switch between pie chart and histogram through the toggle button by each visualization.
- Download button for each visualization is also available for users to download a PNG file.

Table Visualization

Table visualization displays participant details with **tooltips explaining table headers, i**ncluding Studies, Participants, Diagnosis, Treatment, Treatment response, Survival, and Genetic Analysis. Users can click "More" button on the upper right side to access Survival table.

Visible columns in each table can be customized by clicking the "View columns" button in the upper righthand corner of the table and selecting or deselecting available columns (Figure 4). Note that some fields cannot be unselected and will always be displayed.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-8A.png)

Figure 8A: Results returned from a faceted search in the Table section

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-8B.png)

_Figure 8B: Survival table in the Table section_

Synonym Search

When searching for a participant, Users can use any recognized synonym from the CCDI Participant Index (CPI). The system will identify the synonym, note that it matches a known participant, and display the corresponding participant_id and details in the results table below.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-9.png)

Figure 9: Searching by synonym capabilities and match confirmation

CPI Participant Indicator

For participants with additional synonym values from the CPI, an icon will be displayed next to the participant_id values within the Participant tab table. Hovering over the icon displays a tooltip with the clickable link that opens a popup table containing synonym information from the CPI.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-10A.png)

_Figure 10A: Table view with annotations showing the existence of synonyms for a participant._

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-10B.png)

_Figure 10B: Clicking on participant icon shows a pop-up window showing synonym mapping_

Download Harmonized Data

Users can download the contents of the Studies, Participants, Diagnosis, Treatment, Treatment Response, Survival, and Genetic Analysis tabs by selecting the "Download Data" button under the table tab headers. Users can download filtered data in either **CSV or JSON formats**.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-11A.png)

_Figure 11A: Download button to download harmonized data in the Explore Page_

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-11B.png)

_Figure 11B: Download Diagnosis Table tab as CSV file format_

Cohort Selector

The Cohort Selector enables users to create a cohort with a size of up to 4000 and manage up to 20 cohorts. This feature offers flexibility to researchers, allowing them to create cohort groups according to their specific requirements.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-12A.png)

Figure 12A: Cohort Selection features visible on the Explore page Table tabs (see choice buttons in orange rectangle)

Users can do the following:

- Create New Cohort:
  - Users can select participant IDs from the table or choose to add all participants based on the faceted results and create a new cohort.
    - Users can name and describe the cohort for easy reference.
    - A user can add up to 4000 participants in each cohort.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-12B.png)

_Figure 12B: Create a new cohort by adding all the participants in the table or selecting a subset of participants using checkbox_

- Add Participants to Existing Cohort:
  - Select participants and add them to existing cohorts or remove them. Entire cohorts can also be deleted as needed.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-12C.png)

_Figure 12C: Adding entire or selected participants to an existing cohort_

- View All Cohort(s): View a list of all created cohorts, making it easier to manage and analyze groups.
  - Cohort ID: Create your own IDs to identify saved cohorts
  - Cohort Description: Create descriptions for saved cohorts
  - Save Changes: Save the changes made to the selected cohort. This includes changes to cohort ID, cohort description, and any participants.
  - **Copy Cohort:** Create a copy of an existing cohort and add or remove participants as needed. This action creates a new cohort with the same participants and settings, with **"Copy"** appended to the cohort name.
  - Download Selected Cohort:
    - Download the metadata of selected cohort in one of two formats.
      - Manifest CSV: a list of participant IDs and high-level metadata.
      - Metadata JSON: a JSON file containing all metadata information for the participants in the selected cohort, including CPI synonyms
  - View Cohort Analyzer: Navigate to the Cohort Analyzer from the cohort list.
  - Explore in CCDI Hub: Export cohorts (up to 4000 participants for each cohort) that open the CCDI Hub with pre-filtered data based on selected participants.

_![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-12D.png)_

_Figure 12D: View All Cohorts popup allows users to manage up to 20 cohorts. Users were given choices to download cohort metadata, view cohort analyzer, and export cohort to CCDI Hub_

# C3DC Cohort Analyzer

The Cohort Analyzer offers a powerful method to explore how various clinical attributes overlap and differ across multiple groups. The Cohort Analyzer is designed to compare up to three cohorts and visualize their intersections through an interactive Venn diagram, corresponding histograms, and a data table, and survival analysis visualizations. This feature leverages cohorts created on the Explore page, enabling users to analyze key relationships and distinctions based between datasets effectively.

By visualizing the shared and unique data points using a Venn diagram, you can identify common patterns or variations in key clinical variables such as diagnosis, treatment, and participant characteristics. This analysis helps reveal underlying trends in the clinical data that may be crucial for research, such as identifying which treatment protocols are common across cohorts or exploring the presence of specific diagnoses.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-13.png)

_Figure 13: Cohort Analyzer landing page_

##

## Customizable Properties

The radio buttons allow users to select more than one property for comparison. The Venn diagram of Participant ID shows the number of participants shared between different sets, while the Venn diagrams of Diagnosis or Treatment display the number of unique values under each category. Available properties include:

- Participant ID
- Diagnosis
- Treatment

## Enhanced Analytical Capabilities

Users will be able to visualize overlaps and unique attributes within each cohort. In addition, users can:

- Investigate specific sections of the Venn diagram to view participant-level details from the corresponding table view
- Export results, including the data table, histograms, and Venn diagram, for further analysis or integration into other platforms.
- Use advanced filters to refine cohort comparisons, such as narrowing by treatment or specific diagnosis.
- Download result: The cohort result can be downloadable as a CSV with individual high-level metadata or a JSON file with comprehensive metadata, including CPI synonyms.
- Build in Explore Dashboard: Export your analysis into a pre-filtered view within the Explore Dashboard for streamlined review and exploration.
- Explore in CCDI Hub: Export cohorts (up to 4000 participants) that open the CCDI Hub with pre-filtered data based on selected participants.
- "Add Example Cohorts" button allows user to explore cohort analyzer features easily by adding 3 mock cohorts

## Cohort Analyzer Tutorial

To start using the Cohort Analyzer, you will first need to select the cohorts you want to analyze. As you add cohorts, the system will automatically keep track of your cohorts on the left side Cohort Selector. This tool's functionality adapts based on the number of selected cohorts, ensuring a customized analysis.

Select your first cohort by clicking the checkbox in the Cohort Selector sidebar. The Venn diagram and table update to display cohort information based on the selected radio button (Participant ID, Diagnosis, or Treatment). By default, histograms for Sex at Birth and Race are displayed. Users can also enable Kaplan-Meier survival plots with accompanying risk tables to compare overall survival across cohorts or select additional histograms such as Treatment Type and Treatment Outcome by checking the boxes above the visualization panel. In this example, we are using the participant ID and diagnosis, thus the table will contain properties specific to the participant as well as show to what cohorts the participant belongs.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-14.png)

Figure 14: One Cohort Selected: You have created and selected one cohort.

Select another cohort in the Cohort Selector to see the Venn diagram and table update again. This time, if there are common participants between both cohorts, the diagram will show the shared participants in the intersection between the two. Clicking the Diagnosis radio button shows a Venn diagram of unique and shared diagnosis values between two cohorts. In the table below, with none of the Venn diagram selected, it will display all participants and their respective cohort. Selecting part of the Venn diagram will update the table content below accordingly. Histograms on the right side also updates automatically comparing two selected cohorts side-by-side.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-15.png)

Figure 15: Two Cohorts Selected. You have selected two cohorts. Visualize shared and unique data points between these cohorts.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-16.png)

_Figure 16: Two Cohorts Selected. Visualize shared and unique Diagnosis values between the two selected cohorts_

Select a third and final cohort. The Venn diagram and table will update again to display all participant-level data corresponding to the radio button selection.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-17.png)

Figure 17: Three Cohorts Selected: You have selected three cohorts. Explore their intersections and unique attributes using the Venn diagram.

Please note that the number in parentheses by the cohort's name in the Venn diagram represents the count of unique records for that radio button selection. The number inside the Venn diagram sections are the count of unique values for that radio button selection. Finally, the count next to your cohort in the Cohort Selection side bar indicates the total participants in your cohort.

At this point, you can select one of these pieces on the Venn diagram to update the table to show only those participants and their respective data. In the example below, the center intersection was selected. The table updates showing only participants that are found in all three cohorts. With this section selected, a user can also create an entirely new cohort with these filtered participants by clicking the "Create New Cohort" button.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-18.png)

Figure 18: View the center intersection between all Cohort selected (see dark green highlighted region)

The user will see the intersections of all three cohort. Additionally, the user will also see intersections between two cohorts. Clicking on the desired intersection will result in the table being updated accordingly with metadata for those selected participants.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-172.png)

Figure 19: View the specific intersections between selected Cohorts (see dark green and gray highlighted area)

The Cohort Analyzer now includes Kaplan-Meier survival plots with accompanying risk tables. This feature allows users to compare overall survival across selected cohorts based on diagnosis, sex at birth, race, treatment type, or treatment outcome. Use the new **Survival Analysis** option in the visualization panel to enable this view. Review the Kaplan-Meier curves to compare survival probability over time and use the risk table to see the number of participants remaining under observation at each time point. Updating cohort selections or comparison attributes will automatically refresh the results. Users can expand the survival analysis by clicking the expand (X) option and download the Kaplan-Meier plot, the risk table, or both.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-20.png)

Figure 20: View the survival analysis in the expand

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-21.png)

Figure 21: Download the survival analysis in the different section

# C3DC Studies Page

Users can navigate to the Studies Page to view the list of dbGaP accessions, study names, and counts for participants and diagnoses.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-22.png)

Figure 22: The Studies Page

##

## C3DC Studies Details Page

By clicking on the dbGaP accession number (e.g., phs000463), users can access detailed information about the studies. This action will redirect users to the dbGaP page to view a high-level overview of the information. Currently, source data files are only available for open access data (TARGET datasets phs000463, phs000464, phs000465, phs000466, phs000467, phs000468, phs000469, phs000470, and phs000471) and manifest metadata is available for all other CCDI studies. If you are interested in accessing the controlled access data, please follow this [link](https://datacatalog.ccdi.cancer.gov/CCDI_CGC_Data_Access_Instructions_2.0.pdf) for instructions on how to access it.

For other CCDI studies, source data can be found in the [CCDI Hub](https://ccdi.cancer.gov/explore).

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-23A.png)

Figure 23A: The Studies Details page - downloadable Open Access Source file data for TARGET datasets

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-23B.png)

Figure 23B: The Studies Details page - downloadable manifest metadata files for all other CCDI studies

# C3DC Data Model Page

The [data model](https://github.com/CBIIT/c3dc-model) is developed collaboratively with multiple organizations to establish standard terms for pediatric cancer. In this harmonization effort, we are using CDEs (Common Data Elements) to enhance data accuracy, consistency, and interoperability across health research studies. CDEs are defined in the caDSR (Cancer Data Standards Registry and Repository) and provide controlled terms, vocabularies, detailed information on data representation, and robust metadata. The C3DC data model schema consists of well-defined classes with attributes and permissible values.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-24A.png)

_Figure 24A: The Data Model Navigator (DMN) page - Graph with nodes visible and dynamically arranged_

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-24B.png)

Figure 24B: The Data Model Navigator (DMN) page - Table view with readme

# C3DC Resource Page

By clicking on each resource, users can access a range of useful tools and information available on the site.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-25.png)

Figure 25: The Resource page

# C3DC About Page

Users can navigate to the About Page by clicking the link on the Home Page menu bar, where you will find more information about the content of C3DC. This includes details such as dataset and data model information as well as links to useful resources. There are dropdown menus to access the following documents:

- Announcements
- Release Notes
- User Guide

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-26.png)

Figure 26: The About page

## Announcements

The Announcements page contains all C3DC updates, both data and application, with the newest release information at the top of the list.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-27.png)

Figure 27: The Announcements page

## Release Notes

The Release Notes page contains the change logs of all releases, noting the differences between the previous versions of both the data and application.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-28.png)

Figure 28: The Release Notes page

## User Guide

The User Guide page contains the mission statements for CCDI and C3DC, as well as useful resources related to the C3DC project.

![](https://raw.githubusercontent.com/CBIIT/C3DC-Data-Releases/refs/heads/images-1-9-0/user-guid-image/Figure-29.png)

Figure 29: The User Guide