# TODO

## Done
- [x] add toggle for admins in /users  
- [x] can't unadmin one's self (prevents last-admin-standing scenario)  
- [x] only show/permit admin links for admins  
- [x] CLI tooling (db folder, admin, encryption phrase, port)  
- [x] temp csv cache file for downloads  
- [x] upgrade to express 4.0 to get rid of annoying messages  
- [x] save menu button works  
- [x] SQL Editor: refresh schema on connection change  
- [x] SQL Editor: prompt to choose a connection if one hasn't been chosen  
- [x] default db location should be user's HOME directory/sqlpad.  
- [x] --dev flag for console.logging  
- [x] add datatypes to schema info  
- [x] add initial visualizations  
- [x] make routes separate js files (broken up by related chunks)  
- [x] clean up various dates being displayed to appropriate values  
- [x] viz pane/ui hidden away until needed  
- [x] clean up and organize front end js (started browserifying things)  
- [x] update notifications like nodemon  
- [x] about/thank-you page  
- [x] viz selections saved with query
- [x] viz ui updates with new query results (fields may have changed)  
- [x] only render viz if all req fields are provided
- [x] clean up console.loggings
- [x] SQL Editor: download filename uses query name  
- [x] cleanup css for query page
- [x] decide last accessed date stuff (hidden for now)
- [x] Change BASE TABLES to just TABLES
- [x] Remove test connection logging
- [x] Only schema in db info
- [x] all delete buttons should have confirmations
- [x] user/connection sorting (sane default only)
- [x] smart column width in query results (max(value length) or max(column name length)) but no more than some amount (400px)
- [x] vis types - they should probably have an ID and a label, for when things get complicated (multiple bar charts?)


## Before considered 1.x.x  
- [ ] github pages on what/how/why  


## Later or never
- [ ] public mode: anyone can view/run existing queries
- [ ] public mode: anyone can view/edit/run queries (but not save)
- [ ] public mode: anyone can view/edit/run/save queries
- [ ] fun mode (for fun)
- [ ] upload zip of .sql files
- [ ] connection: window colors (for dif. environments)  
- [ ] connection: prepend arbitrary SQL (TRANS ISOLATION LEVEL, etc)  
- [ ] connection: prefer SSL (for postgres --> heroku)  
- [ ] SQL Editor: Excel file download  
- [ ] multiple bar charts
- [ ] Get rid of tags?
- [ ] Loading animation?
