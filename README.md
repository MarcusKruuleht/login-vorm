1. Tuleb luua rakendus samal masinal millel jookseb XAMPP koos MySQL ja Apache teenusega.

2. Automaatse Node käivituse jaoks on vaja <projekti_nimi>.bat file luua millesse tuleb kirjutada:

@echo off  
start npm start


3. win + r, et avada RUN command ja sinna sisestada:

shell:common startup


4. Kopeerida <projekti_nimi>.bat fail shortcut'ina "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp"

5. Taaskäivitada arvuti

6. XAMPP tuleb manuaalselt käivitada

7. Paned otsingusse http://<IP_address>:<port_number>
