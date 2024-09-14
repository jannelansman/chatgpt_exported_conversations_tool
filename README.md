#  ChatGPT exported conversations search and rendering tool
## Main notes
* The tool is written in Python and made to be run in JupyterLab. I will likely post a CLI version later on, so that using JupyterLab wont be necessary.
* The tool can read the `conversations.json` files exported from ChatGPT, find which conversations contain specified search strings, internally convert the conversations into Markdown, and render the Markdown in JupyterLab.
* The rendered conversations include the date when the conversation was initially created, and the url to the conversation online, making it easy to find and continue the original conversation online.
* The search can be done just from titles, or from the titles and contents.
* The search can be case sensitive/case insensitive.
* The tool defaults to reading the `conversations.json` from the same directory with the notebook, but the path can be changed by editing the `config.ini` file.

## Image of the tool's JupyterLab interface
![search_tool_screenshot](https://github.com/user-attachments/assets/99a7578a-186b-4dbe-9c9b-eace0b4334b7)
