----CONTRIBUTION GUIDE----

The contribution process is...

Use waffle.io to manage tasks/issues
Make an issue (or multiple issues)
Make a PR that references that issue
Get it code reviewed by someone on the team, address any comments
Merge into dev-master - This will include all comments -  Recap during Night Debrief
Master will be the clean copy with no dead code included - Confirm with team members what will be merged to final master


Code style guide

Pay attention to the linter!
Use semicolons
Use Tabs
Trailing commas where possible
const or let over var
Use require and module.exports in .js files
Use import and export in .jsx files, unless require makes for cleaner code
Put import statements at top
Put the default export at bottom
Consider splitting up any file larger than 100 lines
Define container components and presentational components in separate files
Use the "ducks" pattern for redux
Name files using lowercase-and-dashes instead of camelCase or PascalCase, except for when the default export is a class, then use PascalCase
Define react components as pure functions (instead of classes) whenever possible

