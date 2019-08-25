# Mnemo Loves Lambda

## How I cut my hosting bill by 80% by moving to AWS Lambda
As a developer maintaining an EC2 instance is a tool of the trade. In developing network based software solutions, a Linux based server is a Swiss army knife of tools.

For years I've used a trusty t2-micro instance at $30AUD/mnth to run docker based deployments of both node/mongo and php/mysql based applications. Swap space to crunch through the memory hungry peaks (like composer) and only occasional annoyances when the poor machine ground into unresponsive disk swap hell. Recently lashed out and moved my disk images up into a t2-small at $50AUD/month which nailed my performance problems at least at the scale of my clients.

As a developer I love docker for it's consistency at deployment. I've used docker from everything to shoring up an ancient Centos php/mysql application into something portable through building MQTT based microservices for voice dialog management.
I've seen serverless kicked around as a buzz word and played with terraform to formally configure deployment processes to cloud providers.

Motivated by finance, I've migrated my main client to a serverless deployment on AWS.

Login system


