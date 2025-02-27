<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: [Gonçalo Ribau]
**Date**: [25-02-2025]
**Product**: [BusWay Website & App]

---

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**                                                                                                                                                                                                                                                     | **Severity** | Recommendation                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------- |
| The home page has excessive information <br>and may get confusing                                                                                                                                                                                             | 2            | Leave only the most important info<br>and put the rest in the respective subpage. |
| The bus search may get confusing with all the buttons everywhere                                                                                                                                                                                              | 2            | Simplify the UI with a better disposition of the buttons                          |
| The warnings tab does not promote fast understanding of the line changes and such as it could do. Its also not explicit that you have to click the warning text to get more info. Also some warnings have a map and other have the download file for the map. | 4            | Give some visual cues to help get to that conclusion and fix the maps.            |
| Sometimes the subpages might take a while to load (does't seem friendly for older devices)                                                                                                                                                                    | 3            | Improve the links between pages and/or lighten up their code.                     |
| Most of the UI in the subpages is very basic and not intuitive at all                                                                                                                                                                                         | 2            | Improve the readability and looks of the pages for more obvious use.              |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**                                                                                                             | **Severity** | Recommendation             |
| --------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------- |
| Some text or words may get overwhelming<br>for older people which are part of the users of<br>the service (bus lines) | 1            | Lighten up the terms used. |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**                                                                                                                                             | **Severity** | Recommendation                                 |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ---------------------------------------------- |
| The only way for returning to the previous page<br>is by the browser's default return button. Some<br>less experienced computer users might get lost. | 1            | Add some kind of return button to the subpages |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**                                                   | **Severity** | Recommendation                                  |
| ----------------------------------------------------------- | ------------ | ----------------------------------------------- |
| Some warnings have maps and other have a file for download. | 2            | Make either all maps or all files for download. |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**                                                                                      | **Severity** | Recommendation                                                                                                                |
| ---------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| Schedules are in a different subpage to warnings.                                              | 3            | Put them in the same subpage.                                                                                                 |
| Different Squedule pages for different destinations, even ones that go through the same route. | 2            | Reorganize the routes page or make it a single one. Perhaps give an estimation of the course and routes you are able to take. |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and functionality personalized or customized for individual users?

| **Issue**                                                                                                                                       | **Severity** | Recommendation                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------- |
| The content destribution is the same for experienced and new users. Maybe having extra info on the home page helps navigation for novice users. | 1            | Maybe make some shortcuts for the most important tasks. |

# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnecessary elements been removed?

| **Issue**                                          | **Severity** | Recommendation                                                   |
| -------------------------------------------------- | ------------ | ---------------------------------------------------------------- |
| Too much info on the main page.                    | 2            | Clean up the interface, even without removing such info.         |
| Too much text with no visual cues in the subpages. | 3            | Clean up some unneeded text and add some images and visual cues. |
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**                                                                                                                                  | **Severity** | Recommendation                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | ---------------------------------------------------------------- |
| There is documentation for download and for consulting in the website, although the latter  Give some more emphasis to said documentation with visual cues.  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  d  s  |

