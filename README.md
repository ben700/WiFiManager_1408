# WiFiManager_1408
Issue 1408

use -iquote to give access to include dir 
set WIFI_MANAGER_OVERRIDE_STRINGS with file name of custom strings

Solution 1
Works 

Add include to string_en

#ifdef WIFI_MANAGER_OVERRIDE_STRINGS

    #include WIFI_MANAGER_OVERRIDE_STRINGS

#endif
