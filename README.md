# AutoDevGPT = Auto-GPT + development

Automated development using LLM technologies.

### Incentive

- I found that AutoGPT is kind of unstable to complete given goals. Therefore I limit the scope of the project to development tasks.
- This project aimed to make a autoGPT like AI agent which can iteratively resolve development problems.

### Roadmap

- Development of a relatively complicated project can be roughly divided into 3 phases
- Making a structure of flow, classes and methods without implementation - this part relies on human first.
- Creating test cases (Test-driven development) for given methods - this part looks possible to be automated
- Complete method implementation and run pass all defined test cases - this part is the first goal to be tackled.

## AI agent setup

1. Developer - 2 commands

- create: 
  - create a method from scratch. By experience it is possible for GPT to generate a method with lines of error
- update: 
  - update a method. If a method is close to completion, update it instead of re-creating from scratch

2. Reviewer

- criticise and suggest next action: 
  - criticise whether an action is good. If not, roll back the code and re-do by the developer
  - Suggest a next action for developer.


