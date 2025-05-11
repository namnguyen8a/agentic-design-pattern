# ReAct Agent
## What is ReAct Agent
- A ReAct agent follows a specific loop of operations:
    - *Thought*: the agent analyzes the problem and reasons about how to approach it
    - *Action*: the agent takes a specific action based on its reasoning
    - *Observation*: the agent observes the result of its action
    - *Answer*: the agent provides a final answer after gathering enough information

## Refs:
- https://www.linkedin.com/pulse/building-ai-re-act-agent-from-scratch-step-by-step-guide-venkat-cihhe/
- https://github.com/KansSoftware/simple-re-act-agent-from-scratch

## Notes:
- running this cmd inside the activated virtual environment file to register virtual env as a jupyter kernel to run the cell within virtual env
    - `python -m ipykernel install --user --name=react-agent --display-name "Python (.react-agent)"`
        - `--name=react-agent`: the internal name used by Jupyter (here in my local i was created `.react-agent` as virtual env)
        - `--display-name="Python (.react-agent)"`: the name that will appear in the VS Code taskbar.
