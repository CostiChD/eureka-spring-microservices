# Simple project showing the Eureka with Zuul load balancer arhitecture

  In order to start the entire project follow the next steps:
  - Start the PhotoAppDiscoveryService project and wait for the initialization to be completed.
  - Start the PhotoAppApiZuulApiGateway project and wait for the initialization to be completed.
  - Start the PhotoAppApiUsers project or the PhotoAppApiAccountManagement project.
    Be aware that you can have multiple instances of the same microservice, so you can start each of these 2 microservices more than one time.
    

  <pre>
  In order to see the microservices that are registered go to:          localhost:8080/
  
  In order to access a microservice through Zuul gateway go to:         localhost:8081/(microservice-name)/(request-path)</pre>
