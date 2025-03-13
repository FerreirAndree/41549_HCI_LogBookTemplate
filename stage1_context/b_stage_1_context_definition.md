[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| Busway Aveiro app    | Official Aveiro public transport app        | [[Competitor Analysis BusWay]] |





## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution

Chosen competitor: Busway Aveiro application.

### - Heuristic Evaluation

#### Method
For the heuristic evaluation, we followed 10 Nielsen's Usability heuristics to analyze the user experience.
1. Three experts of our team independently analyzed the app.
2. Each expert identified usability issues based on Nielsen's heuristics.
3. We assessed the severity of each issue using a 0 (no issue) to 4 (critical problem).
4. After the individual procedure, we conducted to conclusions and prioritized key usability problems.


#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**                                                                                                                                                                                                                                                                 | **André** | Solomiia | Gonçalo | Recommendations                                                                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | -------- | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| It's difficult to navigate through the popup tab with favorite, near and recent routes                                                                                                                                                                                    | 2         | 2        | 0       | Add 2 arrow buttons to navigate in easier way                                                                                                                                            |
| The app rarely displays the real-time position of a bus on the map. When no bus is shown, there is no explanation as to why, nor any indication of a system issue. A user unfamiliar with this limitation might assume that no buses are currently operating on that line | 3         | 3        | 0       | Show a message when real-time data is unavailable like "Real-time tracking is currently unavailable for this line. Please check the schedule for estimated times", map all buses on road |
| When a bus is not being "mapped" in real time, as soon as the scheduled arrival time passes, the app assumes the bus will not arrive and instead displays the next scheduled bus as the next available option.                                                            | 4         | 4        | 0       | Recommendation from above                                                                                                                                                                |
| Error message about incorrect setting of notifications is unclear, thus the user can't understand how to use this feature and what is wrong                                                                                                                               | 0         | 3        | 0       | Display clear error message with troubleshooting tips                                                                                                                                    |
| Missing descriptive information (e.g.originally, it's difficult to understand the purpose of "man", some values etc)                                                                                                                                                      | 0         | 2        | 2       | Add description labels like "bus stop in: - mins" to help user get what the system is displaying                                                                                         |
| The warnings tab does not promote fast understanding of the line changes and such as it could do. Its also not explicit that you have to click the warning text to get more info. Also some warnings have a map and other have the download file for the map.             | 0         | 3        | 4       | Give some visual cues to help get to that conclusion and fix the maps                                                                                                                    |
| The icon for user location can be confused with search icon                                                                                                                                                                                                               | 0         | 1        | 0       | Use diferent icon                                                                                                                                                                        |
| The distance to bus stop is always "0m", so thus the user can think it's near                                                                                                                                                                                             | 0         | 2        | 0       | Recalculate distance to show useful and real values                                                                                                                                      |
| The only way for returning to the previous page<br>is by the browser's default return button. Some<br>less experienced computer users might get lost.                                                                                                                     | 0         | 2        | 1       | Add some kind of return button to the subpages                                                                                                                                           |
| Some warnings have maps and other have a file for download.                                                                                                                                                                                                               | 0         | 2        | 2       | Make either all maps or all files for download.                                                                                                                                          |
| No confirmation before deleting saved routes, users may unintentionally delete them                                                                                                                                                                                       | 0         | 3        | 0       | Add confirmation prompt                                                                                                                                                                  |
| No option to change language (for some users that don't understand the language selected by system it gets impossible to use the app)                                                                                                                                     | 0         | 3        | 0       | Add language option in menu settings                                                                                                                                                     |
| The design is minimalistic, doesn't contain unnecessary information                                                                                                                                                                                                       | 0         | 0        | 0       | No suggestion, it's good point.                                                                                                                                                          |
| Font size is too small on some pages                                                                                                                                                                                                                                      | 0         | 2        | 0       | Add bigger font or allow to users edit the size.                                                                                                                                         |
| User need remember exact names of bus stop for searching                                                                                                                                                                                                                  |           | 3        |         | Implement automatic sugestions (based on name of location)                                                                                                                               |
| Different Schedule pages for different destinations, even ones that go through the same route.                                                                                                                                                                            | 0         | 0        | 2       | Reorganize the routes page or make it a single one. Perhaps give an estimation of the course and routes you are able to take.                                                            |
| Absence of customer support/contact option whithin the app for users experiencing issues or onboarding tutorials for new users                                                                                                                                            | 0         | 3        | 0       | Include help section or chatbot feature                                                                                                                                                  |




---
### - Cognitive Walkthrough

#### Method
The cognitive walkthrough method evaluates the usability of app by analyzing how easily a new user can complete key tasks. This process can identify potential dificulties users might face when navigating the app.

#### Task Selection and Task Analysis

We selected the tasks that are critical for user experience in public transport area.

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Consult shedules**     | 1. Open the app         |
|                             | 2. Select "view shedules"						   |
|                             | 3. Choose a line 							   |
|                             | 4. Define a direction (departure/arrival)			           |
|                             | 5. Select day type                        |
|							  | 6. Confirm and proceed with consulting    |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **2. Plan a trip**            | 1. Open the app |
|								| 2. Open "Route planning" section
|                               | 3. Select user's current location (initial point)                 |
|                               | 4. Choose destination              |
|                               | 5. Put the time        |
|								| 6. Select route option (faster/...)
| 								| 7. Confirm the information above|
| 								| 8. Observe the exibited route (if the input was correct) and consult details of route



#### Results

Task1: Consult shedules

| Step # | Task/Action to Perform                         | Will User Know What to do at this step? (Yes/No) | Notes                                                                           | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes                                                      | Is Action Successful? (Yes/No) | Suggestions for Improvement                                                                                                                                                                                                                                            |
| ------ | ---------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1      | User select view shedules in the side menu     | Yes                                              | The label is clear and visible                                                  | Yes                                                                                       | Screen changes                                             | Yes                            | No suggestion needed                                                                                                                                                                                                                                                   |
| 2      | Choose a line                                  | Yes                                              | The interface clearly presents a list of lines                                  | Yes                                                                                       | The selected line appears below                            | Yes                            | Search bar for lines searching                                                                                                                                                                                                                                         |
| 3      | User must choose a direction before proceeding | Maybe                                            | If users try to skip this step, they are blocked without explanation            | Yes                                                                                       | Appears below                                              | Yes                            | The selection of a direction is mandatory before choosing the day type, but it is not clear enough. The interface doesn't indicate, that direction selection is required next step. Suggestions: add a visual indicator to guide user through the process and tooltips |
| 4      | User should select a type of day               | No                                               | The option is disabled until previous steps are completed, but it isn't obvious | No                                                                                        | User may not understand why they can't select the day type | No                             | Add tooltips and appropriate messages of error                                                                                                                                                                                                                         |
| 5      | Confirm and proceed to view shedules           | Yes                                              | The shedules loads successfully                                                 | Yes                                                                                       | The final shedule appears                                  | Yes                            | No changes needed                                                                                                                                                                                                                                                      |


---

Task2: [This is the task2]

| Step # | Task/Action to Perform                                                 | Will User Know What to do at this step? (Yes/No) | Notes                                                                                                                                                                                                             | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes                                                                                                                                          | Is Action Successful? (Yes/No) | Suggestions for Improvement                                       |
| ------ | ---------------------------------------------------------------------- | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ | ----------------------------------------------------------------- |
| 1      | The user opens app                                                     | Yes                                              |                                                                                                                                                                                                                   | Yes                                                                                       | The main screen appears                                                                                                                        | Yes                            | ------                                                            |
| 2      | Navigates to "New departures"                                          | Yes                                              |                                                                                                                                                                                                                   | Yes                                                                                       | The appropriate interface with map appears                                                                                                     | Yes                            | ------                                                            |
| 3      | Select the point for departure (current location/select on map)        | Yes                                              | If the user select by his current location and not through the map, it doesn't urges any effort from user. But as the first-time user how to do this, because the mark of location has to coincide with stop icon | Yes                                                                                       | It will be exibited on the camp "your location"                                                                                                | Yes                            | Add the tooltips that indicated how to select the stop on the map |
| 4      | Destination selection (by map, typing or automatic location detection) | Yes                                              | The same issues from above                                                                                                                                                                                        | Yes                                                                                       | It will be exibited on the camp "your location"                                                                                                | Yes                            | Add the tooltips that indicated how to select the stop on the map |
| 5      | Select time (now or set specific time of the day)                      | Yes                                              |                                                                                                                                                                                                                   | Yes                                                                                       |                                                                                                                                                | Yes                            | -----                                                             |
| 6      | A user chose a path type                                               | Yes                                              |                                                                                                                                                                                                                   | No                                                                                        | The system doesn't show on the camp the selected option, the user need to open the list another time just to see whether it was selected or no | Yes                            | Show the selected option on the screen                            |
| 7      | Cick on the confirmation button                                        | Yes                                              |                                                                                                                                                                                                                   | Yes                                                                                       | There appears the route information (bus stops...)                                                                                             | Yes                            | --                                                                |






---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

For the user interviews, we adjusted the questions from a previous template to better suit our system. We conducted interviews with five users who had varying levels of experience with public transport. While we followed the structured questions, the conversations often extended beyond the predefined topics, allowing for deeper insights into user needs and behaviors.

## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |
| ...        |                    |                                                                 |                              |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
