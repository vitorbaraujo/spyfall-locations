# Spyfall locations

This repository maintains a list of custom locations for the spyfall game: https://spyfall.adrianocola.com/

## Adding a new location

To add a new location, follow these steps:
- Create a object inside `custom_locations` with the key as the location identifier (you will use this later) and a dictionary with the location name and the roles.
- Enable the location adding the location identifier to the list of selected locations

The final result would be like this:
```txt
diff --git a/locations.json b/locations.json
index 7065321..e8f8158 100644
--- a/locations.json
+++ b/locations.json
@@ -1,5 +1,18 @@
 {
   "custom_locations": {
+    "sample1": {
+      "name": "Sample 1",
+      "role1": "role 1",
+      "role2": "role 2",
+      "role3": "role 3",
+      "role4": "role 4",
+      "role5": "role 5",
+      "role6": "role 6",
+      "role7": "role 7",
+      "role8": "role 8",
+      "role9": "role 9",
+      "role10": "role 10"
+    }
   },
   "selected_locations": {
     "airplane": true,
@@ -28,6 +41,7 @@
     "space_station": true,
     "submarine": true,
     "supermarket": true,
-    "university": true
+    "university": true,
+    "sample1": false
   }
 }

