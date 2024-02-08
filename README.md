# Docker_Experiments
Here we are going to see how we can create the docker images of our source code with the help of the dockerfile and then push it in the docker hub. Every step can be understood with the help of images shown below with the command.

# Step - 1: Write The Source Code For Your Project
Here it is a simple Flask hello world app just for the experiment purpose

![Screenshot 2024-02-08 112102](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/befae3f3-950c-4838-ad2d-3740d06eae63)

# Step - 2: Write The Dockerfile For The Source Code

![Screenshot 2024-02-08 112120](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/9a148b69-5ed9-4734-b245-07cb5c556ed5)

# Step - 3: Let's Build The Images From Dockerfile
     $ docker build -t <images_name> .

![Screenshot 2024-02-08 112610](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/eae2298a-89ed-4004-9577-3c55867b6355)

# Step - 4: Now We Can See Images in Docker Desktop

![Screenshot 2024-02-08 112625](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/d52b22cb-26fa-4ce4-a042-8d4a8d759e78)

![Screenshot 2024-02-08 115115](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/8d7ff50d-a91a-4810-b78f-4f4c0881977e)

# Step - 5: Now Will Run Container For The Above Images
      $ docker run -p <host_port>:<container_port> <image_name>

![Screenshot 2024-02-08 112804](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/dfbb36f2-6833-4e8b-9bda-4ebc7c34b922)

![Screenshot 2024-02-08 115609](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/0457c104-8609-4c7c-bafe-f7fab7aa2fbf)

![Screenshot 2024-02-08 112931](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/2ed8bfd4-8c39-404b-a5c0-22cc8232add2)

# Step - 6: Stop The Running Container
     $ docker stop <container_ID>
     
![Screenshot 2024-02-08 113030](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/fb1a6d78-1d38-420c-a2fa-6f27ea221bab)

# Let's Push The Images Into Docker Hub Repository 
For This, You Have To Login To Docker Hub From CLI With Your Username And Password

## Step = 1: Build Images 

![Screenshot 2024-02-08 114017](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/07dcc931-2c00-4274-8a86-5e5d8826cd02)

## Step = 1: Check Images

![Screenshot 2024-02-08 114023](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/0b0222dd-0680-4119-addf-3d75d0f22180)

## Step = 1: Push Images

![Screenshot 2024-02-08 114029](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/17a305be-6fef-4d48-8017-4d4d8f0ab312)

## Let's Check It On Docker Hub

![Screenshot 2024-02-08 113903](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/c630c14d-97f9-4731-afad-bcf49951d5ea)

![Screenshot 2024-02-08 113936](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/b93fb1e3-da35-4804-9ba8-655d68c36aff)

![Screenshot 2024-02-08 113945](https://github.com/satyam19mishra/Docker_Experiments/assets/103360091/69a0e2a9-170f-4985-a502-60bd480c727e)

# Now Anyone Can Pull The Images And Can Run The Container Locally ...... 
