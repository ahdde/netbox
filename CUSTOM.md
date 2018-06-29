postgres=# \c netbox
Sie sind jetzt verbunden mit der Datenbank »netbox« als Benutzer »postgres«.
netbox=# ALTER TABLE public.dcim_interfaceconnection ADD COLUMN connection_comments text;
ALTER TABLE public.dcim_consoleport ADD COLUMN connection_comments text;
ALTER TABLE public.dcim_powerport ADD COLUMN connection_comments text;

