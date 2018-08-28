FROM rychukarter/oai_oaisim:0.0.1
RUN apt-get install linux-headers-4.13.0-45 -y
RUN apt-get install kmod nano -y
ADD config /home/config
ADD start_services_enb /home/start_services_enb
CMD /home/start_services_enb
