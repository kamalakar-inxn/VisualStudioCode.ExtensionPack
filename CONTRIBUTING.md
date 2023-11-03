If you wish to propose changes to the extension list, you can create a branch, edit the list within the "extensionPack" section of the package.json file, and create a pull request. If you wish to change the major version of the extension pack, this can be done by manually editing the "version" section of the package.json. Minor and patch versions are incremented automatically when built, minor if a "master" branch build, otherwise patch.

A major version change would be justified by potentially breaking changes, for example, the removal of an extension from the list, or an increase in the minimum VS engine version.

The intent of this extension pack is to provide an "all round" or "universal" set of extensions. For extensions particular to specific workspaces/repos, a recommended extensions list can be used as detailed here - https://tech.serhatteker.com/post/2020-05/vscode-extensions-recommended/

There are currently some extensions (e.g. Polymer IDE) that probably should not be in this universal set and should be removed - but we can only do this once recommended extension lists have been added to all relevant projects.

Currently this pack is aimed at full-stack web development. As we cover more technologies we may wish to break out 'Core' and stack-specific extensions (e.g. flavours for .NET Web Development and Python Data Engineering).
