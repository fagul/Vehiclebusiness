FROM nijisha/mt-vr-env

MAINTAINER M1018339

# Load JDBC Connector and deploy business application 
#RUN cd /usr/share/tomcat7/lib;  cd /webapps && wget https://s3.amazonaws.com/vikesh-vehicle-rental/business/2.1.1/VehicleBusiness.war

ADD VehicleBusiness.war /webapps/ 

ADD start_up.sh /

CMD bash start_up.sh
