Auditap

Created by Stanislav Kadl��k

Basic functions:

audio input
scrolling audio
contraction, expansion
create new tracks
Support CTRL + C, CTRL + V, CTRL + X
view audio transcript (*.lbf files)
audio Playback
drag & drop

Start the server:
The server part is dependent on MongoDB and NodeJS. NodeJS is needed to start up when running MongoDB
start MongoDB: mongod (if there is a folder /data/db or c:\data\db)
start node.js: node node-server.js
The application listens on port 8090


Third party libraries:

Blueimp jquery file upload
Socket.io
Backbone
Underscore
JQuery
Require.js

Node-ffprobe
PCM
Express
MongoDB


Preparation of client:

Need to change the server address in the file index.html (lines 14, 16 and 28)





AUDITAP

Vytvo�il: Stanislav Kadl��k

Z�kladn� funkce: 

vkl�d�n� audia
posouv�n� audia
zkracov�n�, roz�i�ov�n�
vytv��en� nov�ch stop
podpora CTRL + C, CTRL + V, CTRL + X
zobrazen� p�episu
p�ehr�v�n� audia
drag & drop

Spu�t�n� serveru: 
Serverov� ��st je z�visl� na mongoDB a na NodeJS. NodeJS je pot�eba spustit a� kdy� b�� mongoDB
spu�t�n� mongoDB:  mongod (pokud existuje slo�ka /data/db nebo c:\data\db)
spu�t�n� node.js: node node-server.js
Aplikace poslouch� na portu 8090 


P��prava klientsk� ��sti:
pot�eba zm�nit adresu serveru v souboru index.html
a to konkr�tn� na ��dc�ch 14, 16, 28. 