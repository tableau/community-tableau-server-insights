# Community Tableau Server Insights

[![Community Supported](https://img.shields.io/badge/Support%20Level-Community%20Supported-457387.svg)](https://www.tableau.com/support-levels-it-and-developer-tools)


## What is Community Tableau Server Insights?

Getting real, useful data out of Tableau Server is difficult-more difficult than it should be. The PostgreSQL repository database that powers Server is a maze of confusing tables and cryptic, often incomplete, data. Using these data sources, the hard work of learning the underlying table structures and assembling a coherent data set that can answer real questions has been done for you. Point these at your Tableau Server repository database, and you can jump right into asking questions!

## Setup and Running Samples

### Prerequisites

* Using these data sources requires that you have already [opened up access](https://help.tableau.com/current/server/en-us/perf_collect_server_repo.htm) to your PostgreSQL repository.
* Each file is named for the minimum version of Tableau Server you must be running to make use of it. You'll need to ensure your Server is running at least the version indicated in the file name, and that you have a copy of Tableau Desktop to publish them with.

### Compatibility

Use this chart to determine what version of each data source you need, based on the version of Tableau Server that you are running.

<div class='tableauPlaceholder' id='viz1572634948397' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ta&#47;TableauServerInsightsCompatibilityMatrix&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TableauServerInsightsCompatibilityMatrix&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ta&#47;TableauServerInsightsCompatibilityMatrix&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1572634948397');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

### Open in Tableau Desktop

1. Open a version of Tableau Desktop compatible with the version you wish to use. You should pick the highest file version possible, while still being lower than your Tableau Server version.

2. Set the Tableau Server parameter for the name of your Tableau Server instance. This is used to build hyperlinks for use in URL actions.

3. Set the Timezone parameter for your local time. This is used to set date time fields with the (local) suffix to your local time (all other times are in UCT).

4. Extract the data, if you wish. Here are recommendations for whether and how each data source should be extracted:

|    Data   Source          |    Extract                                 |
|---------------------------|--------------------------------------------|
|    TS Content             |    Full Extract                            |
|    TS Events              |    Incremental Extract (on Event Id field) |
|    TS Background Tasks    |    Live                                    |
|    TS Users               |    Full                                    |
|    TS Web Requests        |    Incremental Extract (on Id field)       |
|    TS Data Connections    |    Live                                    |

5. If row-level security is required, edit the User Filter calculation as appropriate, and add the field to a data source filter for the value of "true".

### Publish to Tableau Server

1. Publish your data source to Tableau Server by right-clicking it in the Data pane, and selecting "Publish to Server".

2. Set the permissions as appropriate. If you intend the data to be seen by admins-only, you will want to restrict permissions. If you've set up row-level security with the idea to share it with your users, you should allow View and Connect rights.

3. Ensure that the Authentication type is set to embedded password.

4. Add a description for the data source.

5. If you've extracted the data, pick a schedule on which it will be refreshed.

6. Click Publish. Now your data about Tableau Server is also hosted on Tableau Server! How meta. Go start asking questions, champ.

## Contributions

Submissions are cool! To contribute, first sign our CLA that can be found [here](https://tableau.github.io/contributing.html). To submit a contribution, please fork the repository then submit a pull request to the `submissions` branch. We will run through standard tests, but expect you be mindful of performance impacts or cardinality changes that may be introduced.

## Code Style

We have standards, for sure. At some point we'll probably even document them. In the meantime, try to follow some of the conventions used elsewhere in these data sources.

## Documentation

Documentation for these data sources exists in the first page of the workbook they are a part of. Fields are documented with comments.

## Issues

Use [Issues](https://github.com/tableau/community-tableau-server-insights) to log any problems or bugs you encounter.
