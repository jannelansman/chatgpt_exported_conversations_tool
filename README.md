#  ChatGPT exported conversations - Search and Render
## Main notes
* The tool is written in Python and made to be run in JupyterLab. I will likely post a CLI version later on, so that using JupyterLab wont be necessary.
* The tool can read the `conversations.json` files exported from ChatGPT, find conversations containing specified search strings, internally convert the conversations into Markdown, and render the Markdown in JupyterLab.
* The rendered conversations include the conversation's original creation time, and the url to the conversation online, making it easy to find and continue the original conversation using OpenAI's own ChatGPT client.
* The search can be done just from titles, or from the titles and contents.
* The search can be case sensitive/case insensitive.
* The tool defaults to reading the `conversations.json` from the directory where the notebook is, but the path can be changed by editing the `config.ini` file.

## Image of the tool's JupyterLab interface
![search_tool_screenshot](https://github.com/user-attachments/assets/99a7578a-186b-4dbe-9c9b-eace0b4334b7)
