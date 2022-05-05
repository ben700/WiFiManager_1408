# WiFiManager_1408
Issue 1408

Solution 1
Works 

Add include to string_en

#ifdef WIFI_MANAGER_OVERRIDE_STRINGS
    #include WIFI_MANAGER_OVERRIDE_STRINGS
#endif
