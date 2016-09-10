This is a template file that can be used side-by-side with Tableau Public executable file in the BIN directory of Tableau Program Files directory "Windows".

Just copy the file and configure Windows Registery as the following:

* HKEY_LOCAL_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > SideBySide
* NEW > DWORD (32-bit) Value
* Type the name PreferExternalManifest
* Right-click the new entry and hit Modify
* In the Value Data field, replace the 0 with a 1 and change the Base value to Decimal * Hit OK and you can now close the registry.