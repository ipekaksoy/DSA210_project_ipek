# DSA210_project_ipek

## Motivation/Idea of the Project 

In women's life, physical, mental, and cognitive symptoms of menstrual cycle, significantlly affects various aspects. By studying these aspects, this project aims to increase awareness about these changes and provide important insights about women that can improve their physical and mental well-being. Thus, I and other womens will be able to plan and shape their lives accordingly, as they will know on which days their symptoms appear.

The main idea is to how menstrual cycle's different phases affecting on women's pyhsical, mental and cognitive health. Categorazing and studying these symptoms, project aims to find correlation between specific symptoms and a specific part of a menstural cycle.


## Data Source of This Data

Data for this project is extracted from a menstural cycle tracker app. App provides significant insights such as :
  * Initial and last day of menstural period
  * Physicals symptoms:_migranes, body cramps, acne and headache, daily body temperature._
  * Mental symptoms: _anger, sadness, and mood swings._
  * Cognitive symptoms: _confusion and lack of concentration._

All these data is collected from several cycles in order to be sure about the consistency and reliability of these symptoms.

These data is extracted from the menstural tracker of Apple Health which I use in this project to store the dates and the symptoms. As it is provided in the app, i export all of the datas in the app with XML and i clean the irrelevant data which is not about the menstural cycle on this app.
Example data:

```xml
[
 <Record type="HKCategoryTypeIdentifierAcne" sourceName="Health" sourceVersion="17.6.1" creationDate="2024-10-2 17:07:42 +0300" startDate="2024-10-2 12:00:00 +0300" endDate="2024-10-2  12:00:00 +0300" value="HKCategoryValueSeverityUnspecified">
  <MetadataEntry key="HKWasUserEntered" value="1"/>
 </Record>
 <Record type="HKCategoryTypeIdentifierAppetiteChanges" sourceName="Health" sourceVersion="17.6.1" creationDate="2024-10-2 17:07:42 +0300" startDate="2024-10-2 12:00:00 +0300" endDate="2024-10-2 12:00:00 +0300" value="HKCategoryValueAppetiteChangesUnspecified">
  <MetadataEntry key="HKWasUserEntered" value="1"/>
]
 ```
In this example data it shows that on the day of October 2nd, acnes started to appear and there is an appetite change due to the menstural cycle as symptoms.

Also, daily mood is stored in the app called Daylio with five different level of mood whichcategorizes moods into five levels: 'rad,' 'good,' 'meh,' 'bad,' and 'awful.'.This data which exported in the CSV format, provides an opportunity to explore whether specific stages of the menstrual cycle correlate with a mood drop or boost.By examining potential links between mood fluctuations and hormonal changes, this analysis could offer insights into how physiological factors influence emotional well-being. 

Moreover, I recorded my body temperature for several cycles so as to analyze whether specific stages in menstural cycle have a positive correlation with variations in body temperature. This investigation amins to uncover potential patterns linked to hormonal fluctuations during the menstrual cycle.  Moreover, combining mood data with body temperature trends could reveal deeper patterns and relationships. 

### Current Progress in the Project:

 * Data Extraction: Continuing to extract data from the menstural cycle tracker in XML format, from mood tracker in CSV format, and body temperature is recorded in JSON format.
 * Data Cleaning: Irrelevant data unrelated to the menstural cycle has been removed.
 * Premlimary Analysis: Initial patterns of symptoms related to specific cycle days has been identified .



 
## Possible Limitations and Future Work of this Project

### Limitations
* Data depends only on an individual, which might lead to inaccuracies and bias.
* Because it only depends on an individual, it might not be generalized to other people.
* Menstrual cycle is affected by various environmental effects which cannot be determined (lack of knowledge about external factors).

### Future Plans
* Expanding datasets with contributions from other users in the app.
* Analyze and focus on external factors more, such as diet and sleeping schedule.
* Incorporate a machine learning system to predict the possible symptoms' severity based on the history of previous cycles.
* Create a system that includes additional variables for individuals, like hormone levels and sleep quality.

    

  
