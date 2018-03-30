FROM centos
 RUN rpm --import https://packages.microsoft.com/keys/microsoft.asc
RUN  sh -c 'echo -e "[packages-microsoft-com-prod]\nname=packages-microsoft-com-prod\nbaseurl=https://packages.microsoft.com/yumrepos/microsoft-rhel7.3-prod\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/dotnetdev.repo'

RUN yum update
#RUN yum install dotnet-sdk-2.0.3
#RUN yum install centos-release-dotnet
#RUN yum install rh-dotnet20