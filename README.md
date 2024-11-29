# DSA210_project_ipek

## Motivation/Idea of the Project 

In women's life, hysical, mental, and cognitive symptoms of menstrual cycle, significantlly affects various aspects. By studying these aspects, this project aims to increase awareness about these changes and provide important insights about women that can improve their physical and mental well-being.

The main idea is to how menstrual cycle's different phases affecting on women's pyhsical, mental and cognitive health. Categorazing and studying these synptoms, project aims to find correlation between specific synptoms and a specific part of a menstural cycle.


## Data Source of This Data

Data for this project is extracted from a menstural cycle tracker app. App provides significant insights such as :
  * Initial and last day of menstural period
  * Physicals symptoms:_migranes, body cramps, acne and headache._
  * Mental symptoms: _anger, sadness, and mood swings._
  * Cognitive symptoms: _confusion and lack of concentration._

All these data is collected from several cycles in order to be sure about the consistency and reliability of these symptoms.

These data is extracted from a period tracker app in JSON format. Example data:

```json
[
 {
      "date": "2024-10-02",
      "cycleDay": 2,
      "isPeriod": true,
      "flowLevel": "moderate",
      "symptoms": [
        "mild cramps",
        "headache"
        ]
    },
    {
      "date": "2024-10-15",
      "cycleDay": 15,
      "isPeriod": false,
      "flowLevel": "none",
      "symptoms": [
        "ovulation pain",
        "bloating"
      ]
    }
]
 
 
## Limitations and Future Work of this Project

### Limitations
* Data depends only on an individual, which might lead to inaccuracies and bias.
* Because it only depends on an individual, it might not be generalized to other people.
* Menstrual cycle is affected by various environmental effects which cannot be determined (lack of knowledge about external factors).

### Future Plans
* Expanding datasets with contributions from other users in the app.
* Analyze and focus on external factors more, such as diet and sleeping schedule.
* Incorporate a machine learning system to predict the possible symptoms' severity based on the history of previous cycles.
* Create a system that includes additional variables for individuals, like hormone levels and sleep quality.

    

  
