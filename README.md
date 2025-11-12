# LogicForge
LogicForge is a new way to make software

Its not a template engine its a minimalist executor for AI-generated code

You tell an AI what you want to build the AI writes a blueprint script using the LogicForge API you paste that blueprint into the app and LogicForge builds it

Simple
What It Can Do

    Create full project structures with any file you need

    Install dependencies using pip npm etc after asking you first

    Compile real software like C++ libraries Java JARs and OS components
    -- Even build a fucking bootloader from scratch

The tool is a simple executor the power comes from the AI blueprint
How to Use

1 Get a Blueprint

    Open cli_core.py

    Copy the entire AI Guide comment block at the top

    Paste it into your favorite AI like ChatGPT or Gemini

    Tell the AI what to build for example "Using the provided API write a blueprint for a simple Flask server"

    The AI will give you a Python script That's the blueprint

2 Run the Blueprint

    Launch the LogicForge app (python main.py)

    Paste the AI's blueprint script into the text box

    Click the "Run Builder" button

    Watch it build

Installation

You need Python 3

No other bullshit is required to run the app itself

If your blueprints need other tools like git or gcc you have to install those yourself The require_tool function will tell you if you're missing something
Philosophy

    GUI is minimalist a text box and a button thats it

    Backend is powerful all the logic is in the code not the UI

    The AI does the work you provide the goal the AI provides the plan the tool executes the plan

This project will stay free I hate DRM and paywalls I am not a cock block duh
