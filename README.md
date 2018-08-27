# pccwglobal-confluence-theme
Development repo for POC of a PCCW Global brand on top of confluence, facilitated through a plugin.

Initial starting reference for this repo originated with:
https://developer.atlassian.com/server/confluence/writing-a-confluence-theme/


## Working with this repo... 

Install the Atlas SDK and the required java version.
Info here: https://developer.atlassian.com/server/framework/atlassian-sdk/set-up-the-atlassian-plugin-sdk-and-build-a-project/

### Commands:

* atlas-run     -- installs this plugin into confluence and starts it on localhost (first run will download all of confluence's files with maven).
* atlas-package -- rebuilds the latest changes to the plugin and notifies the QuickReload module (https://developer.atlassian.com/server/framework/atlassian-sdk/automatic-plugin-reinstallation-with-quickreload/) in the currently running 'atlas-run' initiated local server of the changes. This has been added as a VSCode default build 'task'.

Other standard atlas commands:

* atlas-debug   -- same as atlas-run, but allows a debugger to attach at port 5005
* atlas-cli     -- after atlas-run or atlas-debug, opens a Maven command line window:
                   - 'pi' reinstalls the plugin into the running product instance
* atlas-help    -- prints description for all commands in the SDK

Atlassian's documentation is available at:
https://developer.atlassian.com/display/DOCS/Introduction+to+the+Atlassian+Plugin+SDK


## Main documentation about creating a theme

https://developer.atlassian.com/server/confluence/creating-a-theme/

