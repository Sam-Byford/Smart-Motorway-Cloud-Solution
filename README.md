# Smart-Motorway-Cloud-Solution
Third year cloud computing module which required an 'infrastructure-as-code' solution for an expanding smart motorway business.

## Task Brief
Your task for this assessment is to design and develop a cloud ‘infrastructure-as-code’ solution for a business scenario (seen below). This development approach allows you to programmatically specify the cloud resources needed for the task in a declarative format using YAML based configuration files via the Google Cloud Deployment Manager (https://cloud.google.com/deploymentmanager/docs/fundamentals) (DM). To accompany the YAML files you can use either Jinja2 or Python file templates to parameterize your cloud service configuration that will allow reuse of your code for common cloud service deployments.

### Scenario
You are in the role as a cloud consultant responsible for the design, development, and deployment of scalable cloud resources for a small-medium enterprise (SME) to support the
growth of its business at both the regional UK level, and the multi-regional level via Europeanonly markets. The business focus is on offering services for smart motorways in terms of weather sensors, ambient light sensors, and remotely controlled road displays and cameras. The data from the sensors, displays, and cameras will need to be securely stored and replicated on the cloud, with access to the data by engineers via web and mobile apps. The volume of the sensor data is anticipated to be up 2000 messages per minute (sensor device to cloud) so scalability is a requirement. By utilising the cloud, it enables the business to quickly react to the growing requirements of their internet traffic, storage requirements, and mobile service needs.

### Development
Your role as the cloud consultant is to manage the development and deployment of the required cloud services to support the SMEs compute needs (e.g. virtual machines) and internet traffic (load balancers, virtual networks/VPNs), regional and multi-regional storage (SQL/NoSQL/bucket), and suitable remote admin access using firewall rules/VPNs. 
You can only use the DM service for the cloud resource types listed here: https://cloud.google.com/deployment-manager/docs/configuration/supported-resource-types ,
you cannot use any other cloud service types for your solution other than those listed.

There is no single correct solution as there are many cloud resources type solutions that could fit. Essentially, each student can demonstrate their intellectual curiosity and technical creativity when designing and developing their own solution.

The YAML configuration file and template files you create should adopt an optimal approach to limit code repetition, with the emphasis on reusable templates as building blocks for importing in your configuration file. Your entire solution must be able to run from a single YAML configuration file.

## Cloud Architecture Diagram
The following diagram displays the resources, storage and network configurations chosen for my solution.

![NewDiagram (1) (1)](https://user-images.githubusercontent.com/32711675/128641199-2f3bc39f-9068-40b4-83c9-dc6d8dbb49dc.png)
