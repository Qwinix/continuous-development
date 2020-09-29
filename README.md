# Qwinix Continuous Development Training Repository

## Program 1: Certified Kubernetes Application Developer
**Unit 1: Core Concepts. Week 1**

### Docker and git basics assessment

Complete the following stages, after each stage, commit the result to your fork:

Stage 1:
1. Create a Dockerfile from Ubuntu 18.04 inside the `docker/` directory
2. Write a command that echos your name during image build
3. Build the image and run it, include the commands you used to build and run the image in a shell script inside the `docker/` directory

Stage 2:
1. Update Dockerfile to update apt and remove echo statement from step 2
2. Build and run the image, this time use your GitHub username as tag and use version 2.0
3. Update your shell script to match the new image tagging 

Stage 3:
1. Update Dockerfile to install nginx, start nginx, copy the file sample.html to /var/www/html/index.html and expose nginx's http port.
2. Rebuild and run the container in detached mode, mapping container port 80 to host port 80
3. Using curl, access the default page from nginx on the container
4. Paste the output of the curl command inside the `docker/` subdirectory and name it "curl.txt"

### YAML Validation

In the `yaml/` subdirectory you will find three yaml files extracted from the microservices-demo solution. These files have been manipulated and are currently syntactically in correct.

Perform the following steps and when completed, commit your code.

1. Fix all syntax errors
2. Ensure each deployment has its port exposed on port 8080
3. Uncomment the email deployment's DISABLE_PROFILE setting
