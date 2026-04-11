# FTP Server för test från t ex integrationsplattform

Endast ett workflow med deploy av pure-ftpd genom github actions.  
Skapar om volymen ftpdata vid varje deploy, för att rensa eventuella gamla överblivna testfiler
Körs schemalagt på söndagar för att ha en fräsch testmiljö inför veckan.

