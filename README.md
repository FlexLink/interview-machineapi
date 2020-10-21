# Machine data API Home Exercise

## Intro
Your purpose of this work is to create a client library 
in Go or Java to access our simulated [machine data API](./api/swagger.yaml) service. 

### What to do
- Client library should be written in Go or Java
- Add documentation to your code
- You need to implement the `Add`, `Get`, `List` and `Remove` operations on the `machine` resource. You should support paging for `List` as well.
- Don't forget to write human-readable tests to get the quality level you would expect in production. 
- Please, do some debugging and workaround first, before reaching out for help, in case you see any problems running the machineapi or Docker compose. Try to find a solution if something is wrong. 

### What NOT to do
- Don't use a rest api library for your client. Test libraries are OK.
- Don't use a code generation

### Docker
 - Modify the existing docker-compose.yaml file, add your section
 - We will check your work by running `docker-compose up` and looking at your tests running the client connecting to provided machine API service. 
 - Machine API service simulate unstable behavior sometimes as a real service in Web. 
 - When you are running docker compose, machine api Swagger UI is available at [http://localhost:8115/swagger/index.html](http://localhost:8115/swagger/index.html) 
 
## How to submit your exercise
- Include your name in the README 
- Create a private repository on GitHub, copy the `docker-compose.yaml` from this repository
- Add @flexlink-code-review as a collaborator to your private repository in repo Settings / Manage access
- Please inform our recruitment team you have completed the exercise

