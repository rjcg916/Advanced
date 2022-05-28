## general
- readme file for each runnable project
- each runnable project should be run locally without need for remote resources, connections, etc.
- no secrets exposed in checked-in code : use local secrets + key vault
- bootstrap or agreed upon css framework included
- leverage application identity (versus credential string) whereever possible
- appropriate separation of concerns in projects
  - Data Model / Layer
- each deployable project includes definitions for all infrastructure
## repository
- repository structure matches standards
- repository configured to disallow direct commit to master branch & require review/approval by two non-authors
## .net core 
- startup correctly configured with appropriate services and middleware
- no secrets in appsettings.json
- use null checking/nullability settting
## entity framework
  - seed/test data defined with EF project
## api 
- swagger ui 
- appropriate security defined & configured
- controllers generated via openapi spec
- clients generated via openapi spec

## blazor / server
- program.cs - AddServerSideBlazor, MapBlazorHub
- blazor.server.js in _layout
- use of _Imports.razor for using
- connection error display/handling
- handle uncaught application errors
### components
- factoring of code into components
- group components into "feature folders" 
- named and scoped event handlers and data bindings
- use of template components
- use cascading parameters to avoid cumbersome configuration passing



