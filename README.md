# AutomatedCodingChallengesAssembly

This repository contains the dataset for automated coding challenge assembly. The dataset is derived from the Pintia programming practice platform (https://pintia.cn/) and includes 207 programming problems along with the corresponding student submission codes from the 2023 Spring term.

## File Description

**Filename:** `code_extracted_data.json`

This file is a JSON data file that contains a dictionary composed of multiple `problem_set_problem_id` entries. Each `problem_set_problem_id` is an object representing a specific problem set. Each problem set object includes the following fields:

- **title:** The title of the programming question, presented in its original Chinese form from Pintia.
- **content:** The content description of the question, also in its original Chinese form from Pintia. However, only a portion of the content is displayed here, just to distinguish different task descriptions between programming questions.
- **program_count:** The number of example codes.
- **program_n:** This represents a programming example where n is a varying number from 1 to the `program_count`.
