# Use an official microsoft/dotnet runtime as a parent image
FROM microsoft/dotnet

# Set the working directory to /home
WORKDIR /home

#Define the host directory to share with the container 
#VOLUME /home

# Make port 5000 available to the world outside this container
EXPOSE 5000

# Run the command when the container launches
CMD dotnet restore
CMD dotnet run