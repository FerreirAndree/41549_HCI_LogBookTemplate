<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: [Solomiia Koba]
**Date**: [26-02-2025]
**Product**: [BusWay App]


Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**                      | **Severity** | Recommendation            |
| ------------------------------ | ------------ | ------------------------- |
| Loading indicators missing or while searching shedules | 2     | Add loading spinners|
| Error message about incorrect setting of notifications is unclear  |   3    | Display clear error message with troubleshooting tips|
| Delayed or missing updates on shedule changes (when a bus is delayed, but its shedule isn't updated, it doesn't appear anymore) |       3       | Implement notifications for real-time changes or delays, add alerts section|
| Missing descriptive information (e.g.originally, it's difficult to understand the purpose of "man", some values etc)|      2        | Add description labels like "bus stop in: - mins" to help user get what the system is displaying |
The app does not clearly communicate why the information is unavailable while route selection, it shows "no available information" instead of explain directly the reason| 3 | Show clearer messages with indications how to proceed



# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**                      | **Severity** | Recommendation            |
| ------------------------------ | ------------ | ------------------------- |
| The distance to bus stop is always "0m"| 2 | Recalculate distance to show useful and real values  |
| The icon for user location can be confused with search icon| 1  | Use diferent icon         | 


# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**                      | **Severity** | Recommendation            |
| ------------------------------ | ------------ | ------------------------- |
| No confirmation before deleting saved routes|      3        |  Add confirmation prompt  |



# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**                      | **Severity** | Recommendation            |
| ------------------------------ | ------------ | ------------------------- |
| User need remember exact names of bus stop for searching|3 |  Implement automatic sugestions (based on name of location)    |
| No guidance when route or bus stop isn't found| 2 |  Suggest nearby stops or auto-correct input|

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**                      | **Severity** | Recommendation            |
| ------------------------------ | ------------ | ------------------------- |
| No option to change app language|    3        | Add language option in settings menu  |


# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**                      | **Severity** | Recommendation            |
| ------------------------------ | ------------ | ------------------------- |
| Font size is too small on some pages|   2     | Set bigger font or allow users to edit the size  |

# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**                      | **Severity** | Recommendation            |
| ------------------------------ | ------------ | ------------------------- |
| User need remember exact names of bus stop for searching routes| 3 |  Implement automatic sugestions (based on  name of location)|


# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**                      | **Severity** | Recommendation    |
| ------------------------------ | ------------ | ----------------- |
| Absence of customer support/contact option whithin the app for users experiencing issues | 3 | Include help section or chatbot feature |
| Limited onboarding for new users | 2          | Add a tutorial, tips  |  


