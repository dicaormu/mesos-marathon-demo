FROM dockerfile/java:oracle-java7

EXPOSE 8080

#WORKDIR /app
#RUN virtualenv /env
ADD . /


CMD []
#ENTRYPOINT ["/env/bin/python", "-m", "SimpleHTTPServer", "8080"]
ENTRYPOINT ["java" , "-jar", "/pio-pio-assembly-1.0.jar", "8080"]

