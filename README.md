# CodemodForReact17EnzymeAdapter
It does replace the reeact16 enzyme adapter with react 17 enzyme adapter in repo wide jest.setup.js files.
For react 16, there's a official adapter for enzyme. 
But when we try react bump to 17, no official enzyme adapter is yet released. There are few adapters released by others, we have used one o fit. 
apart from declaring in package.json, we need to update the import statements as well. 
Id you are having more number of files that imports, then manual process is difficult.
This codemod does that help in updating the import statements.
