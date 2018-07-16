# EvolentHealthAssignment
This multi layered architecture.Below is description of each layer

1. EvolentHealth.POC.Business -This layer is business layer and it contains all business logic of the application. It calls functions from    other layer called EvolentHealth.POC.Repository

2. EvolentHealth.POC.Repository - This layer is responsible for communicating with database layer and perform CRUD operations

3. EvolentHealth.POC.Data.Edmx - This layer has edmx file(entity framework) which actually communicates with database.

4. EvolentHealth.POC.Web.Service -This is actually a web api layer which perform GET,PUT,POST and DELETE operation using web API

5. EvolentHealth.POC.Web.Service.Tests - This is automated testing solution to check result of web api


Note:UI layer is not created in project as web API are medium of communcation and request and response is checked using this appliction




