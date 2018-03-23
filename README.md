Continuous Delivery (CD)
Continuous Delivery  is a development practice where code changes are automatically built, tested, and prepared for a release to production.

With continuous delivery, every code change is built, tested, and then pushed to a non-production testing or staging environment. There can be multiple, parallel test stages before a production deployment. In the last step, the developer approves the update to production when they are ready.

Continuous Delivery mandates Continuous Integration.

Continuous Deployment (CD)
Continuous Deployment is a software development practice in which every code change goes through the entire pipeline and is put into production, automatically, resulting in many production deployments every day.

With Continuous Delivery your software is always release-ready, yet the timing of when to push it into production is a business decision, and so the final deployment is a manual step. With Continuous Deployment, any updated working version of the application is automatically pushed to production.

CD:IBM UrbanCode deploy,Jenkins(Cd Plugins),Spinnaker

Spinakker:1)Valid pcf commercial cloud acc.
2)u need to have spinnaker
3)Start ur spinnaker
4)Register few things in pCF(u need to create  a new memory space in PCF)
5)Every memory is associated with an org.(org-->Space)

java -jar spring-cloud-spinnaker-1.0.0.M3.jar --server.port=9999


Pipeline:is group of phases(Dev

Log aggre:Splunk,elastic search,kibana,logstash

Spinnaker:req spinnaker jar file,Commercial PCF cloud license(min memory required fr this 8GB).

PCF:free(2gb),commercial

AWS/PCF/Google cloud:buildpacks(100--512mb)

Buildpack is runtime for ur app

javabuild(jdk+tools)
tomcatbuildpack.

Note:Transtive dependency for spinakker is Jenkins/Hudson server.Capge:5projects

Steps:
-------
1)Chain required jobs in sequence
2)Install Delivery Pipeline plugin(done)
3)Add delivery Pipeline view
4)Run and Validate
