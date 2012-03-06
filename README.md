This subproject is meant to host translation files for easier exchange and collaboration. The files that go into RHQ 
releases still live on the main RHQ [git at fedorahosted][2] (see [here for coregui][3] )

Basically fork the project, start translating and then send pull requests. We will then take the updated translation 
files and put them back into the main RHQ repo.

If you want to add a new language, copy the default file (e.g. Messages.properties) to Messages_xx.properties and then
work on that new file (xx is the language code of the target language).

Also small contributions matter. You can make a change!

*NOTE:* Please read the following [wiki article][1] for some of the more technical aspects 
like file format, encoding and hints about IDE setup etc.



[1]: http://rhq-project.org/display/RHQ/Working+with+the+Resource+Bundles
[2]: http://git.fedorahosted.org/git/?p=rhq/rhq.git;a=summary
[3]: http://git.fedorahosted.org/git/?p=rhq/rhq.git;a=tree;f=modules/enterprise/gui/coregui/src/main/resources/org/rhq/enterprise/gui/coregui/client;h=cd9bf5f208c22ddae9d3a394c99ba6f073cb2771;hb=HEAD

