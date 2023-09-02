FROM            centos:7
RUN             yum install epel-release -y
RUN             yum install nginx -y  
COPY            index.html    /usr/share/nginx/html/index.html  
EXPOSE          80 
ENV             environment=dev 
CMD             ["nginx", "-g", "daemon off;"]

# FROM            centos:7
# # Startup Script, whatever you mention here can be over ridder and this will be an argument to the ENTRYPOINT
# CMD             ["google.com"]    
# # ENTRYPOINT can never be overridden    
# ENTRYPOINT      ["echo"]

# To build the DOcker iages go to that direrety or navigate where this poath in the mechine run this commnad Kubernetes1/docker-imaging ]#   docker build .