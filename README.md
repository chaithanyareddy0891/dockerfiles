# dockerfile
FROM
----
FROM should be the first instruction in Dockerfile. It represents base OS.

RUN
---
Run instruction is used to configure image like installing packages, configure etc ..RUN instruction runs at the time of image building.

CMD
--
CMD instruction runs at the time of conatiner creation. it keeps container running

LABEL
----
LABEL adds metadata to the image, description, who sis the owner, which projects. 

EXPOSE
------
is used to let the users know what all the ports conatiner will open when it runs.(just for documentation it will not add the functionality)