FROM nvidia/cuda:8.0-runtime

RUN apt-get update
RUN apt-get install apt-transport-https -y
RUN sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet-release/ xenial main" > /etc/apt/sources.list.d/dotnetdev.list'
RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 417A0893
RUN apt-get update
RUN apt-get install dotnet-sharedframework-microsoft.netcore.app-1.1.1 -y