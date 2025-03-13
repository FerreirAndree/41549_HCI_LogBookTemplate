<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: [Gonçalo Ribau]
**Date**: [25-02-2025]
**Product**: [BusWay App]

---

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**                                                                                                              | **Severity** | Recommendation                                                            |
| ---------------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------- |
| App opens in map per default, may get confusing to some users                                                          | 2            | Open on some kind of objective menu to promote simplicity and information |
| The tabs might take a while to load (does't seem friendly for older devices)                                           | 3            | Improve the code behind the search                                        |
| Most of the UI  is very basic and not intuitive at all                                                                 | 2            | Improve the readability and looks of the tabs for more obvious use.       |
| Lack of visual cues for every action makes the app feel clunky or angering users if something doesn't work as intended | 3            | Add visual cues for taps and other actions deemed required                |
| The schedules tabs are very bad designed and mostly non-functional/non-existent.                                       | 4            | Add/improve said tabs                                                     |


# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**                                                                                                             | **Severity** | Recommendation            |
| --------------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------- |
| Some text or words may get overwhelming<br>for older people which are part of the users of<br>the service (bus lines) | 1            | Lighten up the terms used |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**                                                                                                                                                                                           | **Severity** | Recommendation                             |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------ |
| The only way for returning to the previous page<br>is by the phone's default return button or by opening the menu again and choosing a different option. Some less experienced users might get lost | 1            | Add some kind of return button to the tabs |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**  | **Severity** | Recommendation |
| ---------- | ------------ | -------------- |
| no comment |              |                |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**                                                            | **Severity** | Recommendation                                |
| -------------------------------------------------------------------- | ------------ | --------------------------------------------- |
| Sometimes the app crashes for no apparent reason without explanation | 3            | Add error reports                             |
| No explanation to why we can't find certain bus lines                | 3            | Explain better why bus lines aren't available |

# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**                                                                                       | **Severity** | Recommendation                                                                                                                |
| ----------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| Users need to find bus stop every time they want to search for a schedule the default way.      | 3            | Separate Stops by lines instead of lines by stops                                                                             |
| Different Schuedule pages for different destinations, even ones that go through the same route. | 2            | Reorganize the routes tabs or make it a single one. Perhaps give an estimation of the course and routes you are able to take. |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and functionality personalized or customized for individual users?

| **Issue**                                                                   | **Severity** | Recommendation                                                |
| --------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------- |
| Always have to search for stops to get a certain bus line                   | 3            | Make it so users are able to search for the bus line directly |
| No option to change mode (dark/light)                                       | 1            | Add the option                                                |
| No option to change language                                                | 2            | Add the option                                                |
| Different tabs to search for stops and search for buses that go from A to B | 2            | Combine both options in the same tab                          |

# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnecessary elements been removed?

| **Issue**                              | **Severity** | Recommendation                                                         |
| -------------------------------------- | ------------ | ---------------------------------------------------------------------- |
| Too little information. Too minimalist | 2            | Give some more info relating to the buses and specially the app itself |


# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**                                                              | **Severity** | Recommendation                                                                          |
| ---------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------- |
| No error messages apart from when there are no buses on a certain stop | 2            | Explain other errors that might happen like crashes or unexpected error in the searches |


# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**                                                                                                                           | **Severity** | Recommendation                                                                        |
| ----------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------- |
| Too little information in regard to the app is provided                                                                             | 3            | Give some more info related to the use of the app, maybe even an interactive tutorial |
| No customer support in the app and no information regarding where the customer support might be provided (like in the main webpage) | 3            | Explain to the users how and where they can get customer support                      |

