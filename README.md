# Prompt Structure and Requirements
This README is for version xxx prompts. This prompt serves the following purposes:
1. Predict Winner
2. Rank first N horses
3. Rank based on Top 4 statistic
4. Rank with Past Record
5. Find relations between XX and YY

## Dimensions
| Dimension | Explanation | Examples | Data Type |
| --------- | ----------- | -------- | --------- |
| Win Odds  | Win odds for horse | 1/2/3/4 | Int |

## Prompt Structure
The prompt paragraphs follow a specific structure to ensure clarity and consistency. Each prompt paragraph consists of the following main parts:

SYSTEM MESSAGE: This section describes any system requirements or special reminders related to the problem. It provides essential information that users need to be aware of before proceeding with the problem.

CONCEPTS: The Concepts section contains important domain-specific concepts relevant to the problem. It serves as a dictionary of key terms and ideas that users should understand to tackle the problem effectively.

CHAIN OF THOUGHT: This section describes the steps to solve the problems and gives appropriate answer and ranking.

CURRENT DATA: This section takes live input from the user and may include static data obtained from other Python files as dictionary objects. For example, it can include data such as "win odds" or "jockey." This data is crucial for solving the specific problem and should be used as a reference during problem-solving.

QUESTION: The Question section presents the specific problem or question that users need to address. It clearly states the desired outcome or solution expected from the user.