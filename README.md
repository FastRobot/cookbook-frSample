# frSample cookbook

Clone and modify this cookbook as a start for whatever new cookbook you need

## Features

* Jenkinsfile for pipeline driven validation/testing
* Rakefile as an integration point
* chefspec
* inspec
* ec2 kitchen driver
* test kitchen roles/environments

## Assumptions

We assume you're developing via a recent ChefDK. 

Jenkinsfile assumes Jenkins 2.0 with the pipeline plugin.

Additionally, we'd like to use the docker chef/chefdk for most operations, driven by the `agent` block in the Jenkinsfile.

## TODO

* actually include the Jenkinsfile
* Rakefile

