<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: [André Ferreira]
**Date**: [23-02-2025]
**Product**: [BusWay App]

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**                                                                                                                                                                                                                                                                                                          | **Severity** | Recommendation                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Aba de Popup com 3 vistas para consultar (paragens favoritas, próximas e histórico) requer que se deslize lateralmente para trocar entre vistas, umas vezes funciona outras não, não dão qualquer informação do porquê, nem indicam a maneira correta de trocar entre vistas.                                      | 2            | Colocar 2 botões de seta para trocar entre vistas, caso não seja possível efetuar a troca, lançar um aviso a justificar.                         |
| Muito raramente têm no mapa a posição de um autocarro em tempo real, quando não o têm não indicam o porquê ou sequer que haja um erro,  um utilizador que não saiba deste problema pode entrar numa linha, não ver nenhum autocarro e pensar que não existe nenhum autocarro na linha de momento.                  | 3            | Fazer o mapeamento de todos os autocarros na estrada, ou indicar quando existem autocarros em movimento numa linha mas não estão a ser mapeados. |
| Quando um autocarro não está a ser 'mapeado' no momento, assim que passe a hora tabelada a que este devia chegar a determinada paragem (algo que acontece com regularidade), a aplicação indica que o próximo autocarro a passar nessa paragem será já o autocarro seguinte, quando está eminente a chegada de um. | 4            | Recomendação anterior resolveria este problema.                                                                                                  |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |

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

| **Issue**                                                                                                                                                                                                                                 | **Severity** | Recommendation                                                                                                  |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------------------------------- |
| Não há qualquer indicação ou aviso de quando um autocarro não está a ser mapeado em tempo real, podendo levar os utilizadores, após uma consulta algo 'superficial', a pensar que não se encontram autocarros na estrada naquele momento. | 3            | Mapear todos os autocarros, ou colocar um aviso quando há autocarros na estrada que não estejam a ser mapeados. |
|                                                                                                                                                                                                                                           |              |                                                                                                                 |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |
# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**                                                                                                                                                                  | **Severity** | Recommendation                                                                                                 |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------------------------- |
| Não disponibilizam um local com todas as linhas disponíveis para um utilizador que já saiba que linha(s) pretende usar na sua deslocação rapidamente aceder à(s) mesma(s). | 2            | Adicionar esse tal menu com todas as linhas disponíveis para uma rápida consulta dos seus horários e paragens. |
|                                                                                                                                                                            |              |                                                                                                                |
# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**                                                                                           | **Severity** | Recommendation        |
| --------------------------------------------------------------------------------------------------- | ------------ | --------------------- |
| O design é minimalista, só mostram o necessário, não correm grande risco de confundir o utilizador. | 0            | Ponto bem conseguido. |
|                                                                                                     |              |                       |
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

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                |
