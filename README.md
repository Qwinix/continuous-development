# continuous-development
Qwinix Continuous Development Training Repository

Create & Run a Docker image

Steps:
1. Create Dockerfile from Ubuntu 18.04
2. Write a command that echos your name during image build
3. Build image
4. Run image
5. Update Dockerfile to update apt and remove echo statement from step 2
6. Build & Run image - this time, give it a name
7. Update Dockerfile to install nginx, start nginx, copy the file sample.html to /var/www/html/index.html and expose its port
8. Rebuild and run the container in detached mode mapping container port 80 to host port 80
9. Using curl, access the default page from nginx on the container
10. Update Dockerfile to install hexedit then rebuild and run container
11. Check in Dockerfile
12. Cleanup: Stop container and remove image


For deployment yaml's:
1. Fix all syntax errors
2. Ensure each deployment has its port exposed on port 8080
3. Uncomment the email deployment's DISABLE_PROFILE setting
