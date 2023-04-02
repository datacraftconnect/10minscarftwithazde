# 10 Minutes Carft with Azure Data Engineering

This repository contains helpful code required to practice 10 Minutes Craft on azure data engineering that available on below youtube channel.

https://www.youtube.com/playlist?list=PLxVdIVhnvkUDFGiLo7o54AXwRxEUsUerV

# Setting Up Development Environment (Windows 10)

1. Download and Install visual Studio Code from following link,\
https://code.visualstudio.com/
2. Download and Install Python from following link, we have used python 3.10\
https://www.python.org/downloads/
3. Download and Install Azure CLI for windows from following link,
https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli
4. Download and Install git for windows from following link,
https://git-scm.com/downloads
5. Open Visual Studio Code and install python extension for visual studio code by pressing Ctrl+Shift+X, use below link for reference
https://marketplace.visualstudio.com/items?itemName=ms-python.python
6. Open Visual Studio Code and install azure extension for visual studio code by pressing Ctrl+Shift+X, use below link for reference
https://code.visualstudio.com/docs/azure/extensions
7. SignUp for Azure Free account intially, that can be used to expriment with above code with following link,
https://azure.microsoft.com/en-gb/free/
8. Once SignUp is done, go to Subscriptions page to nick Subscription Id and setup an environment path variable in your system locally as follows,
SUBSCRIPTION_ID = 'xxxxxx-xxxx-xxx-xxx-xxxxxxxxxxx'
9. Next open Visual Studio Code(VSC) and on terminal type below command to check weather you are able to login to azure from VSC
```
az login
```