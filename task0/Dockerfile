# Use the latest version of Ubuntu as parent image
FROM ubuntu:latest

# Update the package lists for upgrades - for packages that need upgrading
RUN apt-get update

# Upgrade all installed packages
RUN apt-get upgrade -y

# When Docker container is run, echo "Hello, World!"
CMD echo "Hello, World!"
