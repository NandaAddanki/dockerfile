From alamlinux:9

 #CMD can be overriden at run time. If we pass some other value/website at runtime google.com can overridden
CMD [ "ping" "google.com"]

#Entrypoint can't be overriden
ENTRYPOINT ["ping" "google.com"]
 
#we can use CMD and ENTRYPOINT togeather for better results and best practice.
#CMD can pass arguments to ENTRYPOINT. we can mention defalut args in CMD and we can override at run time
CMD ["google.com"]
ENTRYPOINT ["ping"]
