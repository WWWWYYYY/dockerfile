FROM jenkins/jenkins:lts
# put nginx-1.13.2.tar.gz 将宿主机上的nginx-1.13.2.tar.gz复制到容器中的/usr/local/src （对于压缩包会复制过程中自动解压）
ADD apache-maven-3.6.3-bin.tar.gz /opt
COPY settings.xml /opt/apache-maven-3.6.3/conf
ENV PATH /opt/apache-maven-3.6.3/bin:$PATH