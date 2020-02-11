|Contents|
| ----- |
| [Create GitHub account and fork this repository](#create) |
| [Contributing information](#contributing) |
|  - [Contributing data](#data) |
|  - [Contributing parameter estimates](#parameter) |
|  - [Contributing documents](#documents) |
| [Collaboration platforms](#platform) |

# Contributing to this GitHub Repository

## <a id="create"></a>Create GitHub account and fork this repository
1. Create a GitHub account and log in through: https://github.com
2. Go to Midas Network repository: https:://github.com/midasnetwork/2019-ncov
3. On the upper right corner, click on **Fork**.  
   **You have now forked the MIDAS 2019-nCoV repository into your github account.**  

## <a id="contributing"></a>Contributing information

To contribute to the 2019-nCov repository with GitHub:
1. Create or update new files or sub-directory in YOUR fork repository, in the folder and in the sub-folder corresponding to your contribution: 
     + To create a sub-directory within the repo, you must Create a New File and add the sub-directory name before the file name: i.e. /SUB-DIR/FILE-NAME.ext  
     + To upload local files to your created sub-directory, click the "Upload Files" button, uploaded files can be edited within GitHub by clicking on each file and the edit button.
     +  "Commit" all your changes
2. To merge changes into the original repo, a *Pull Request* must be initiated by you from your fork.  
     + This request will be reviewed and merged by owner.  
     + Note: All changes must be made from YOUR repo fork.  
     + Click on the green **Pull Request** button.  
     + Owners of the MIDAS nCoV repo will verify and merge your changes to the original repo

*Instructions adapted from Michael Johansson's zika repository:* [![DOI](https://zenodo.org/badge/51947303.svg)](https://zenodo.org/badge/latestdoi/51947303) 

### <a id="data"></a>Contributing data
1. Add your collection of files into the corresponding folder in YOUR fork repository
2. Add a _collection_metadata.csv_ file describing the content of your collection, a template is available [here](https://github.com/midas-network/2019-ncov/blob/master/information_for_contributors/collection_metadata_template_v1.1_8Feb2020.csv).
3. Add a _date_guide.csv_ file, if necessary, describing the variables used in your data-set, a template is available [here](https://github.com/midas-network/2019-ncov/blob/master/information_for_contributors/collection_metadata_template_v1.1_8Feb2020.csv).
4. Create a pull-request to update your collection into the repository, a MIDAS staff member will review it before adding it to the repository. 

### <a id="parameter"></a>Contributing parameter estimates
1. Read the [Data Guide for Parameter Estimates](https://github.com/midas-network/2019-ncov/blob/master/information_for_contributors/parameter_estimates_data_guide_v1_4Feb2020.csv) to ensure your data contains most of the necessary information to contribute to the repository.
2. Create an issue to have a MIDAS staff member add an estimate, or create a pull request to the [estimates.csv file](https://github.com/midas-network/2019-ncov/blob/master/parameter_estimates/2019_novel_coronavirus/estimates.csv) to directly append your estimate to the main repository.

### <a id="documents"></a>Contributing documents
* Create an issue containing the information related to the documents (Citation, link, ...) or the documents you want to add to the repository, and a MIDAS staff member will update the information in the Wiki and in the folder corresponding if necessary. 
* For report document, you can also add your files into the corresponding folder or create a folder if necessary, in YOUR fork repository:
     + If the report uploaded concerns more than one country, it should be upload into the global folder.
     + The report file uploaded should be named following the convention "DATE_short_title" (Date in the ISO Format YYYY-MM-DD)
     + Don't forget to update the _collection_metadata.csv_ files, if a new collection is created, you will need to add a _collection_metadata.csv_ file describing the content of your collection, a template is available [here](https://github.com/midas-network/2019-ncov/blob/master/information_for_contributors/collection_metadata_template_v1.1_8Feb2020.csv)
    + Create a pull-request to update your collection into the repository, a MIDAS staff member will review it before adding it to the repository. 

## <a id="platform"></a>Collaboration platforms
### [Outbreak Science Rapid PREreview Platform](https://outbreaksci.prereview.org)
This rapid pre-review platoform enables the community to give feedback on pre-prints coming out with modeling and other analyses of the 2019-nCoV and other outbreaks.

### [2019 Novel Coronavirus section on virological.org](http://virological.org/c/novel-2019-coronavirus/33)
Virological.org is an online discussion forum for analysis and interpretation of virus molecular evolution and epidemiology.

### [Slack modeling_ncov channel](modelingncov.slack.com)
A Slack workspace maintained by Caitlin Rivers (caitlin.rivers@gmail.com) for discussion on 2019-nCoV research. The workspace includes various channels: general, importation, news, random, publications, forecasting, data, announcements-welcomes
