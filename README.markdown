# Accessing the Build Server
http://jenkins.cyanogenmod.com/

# Authenticating to the Build Server
You must be a member of the CyanogenMod organization, and your
membership must be public at https://github.com/CyanogenMod  

Jenkins will authorize using OAuth to GitHub.

# Using the Build Server
Click the "android" job.  
Configure what you want to build.  
Build it. Note that regular builds (nightly/snap/whatever) can only
be produced by the automated processes. Manually triggered builds will
always be labeled as EXPERIMENTAL

# Adding or updating a device

Edit cm-build-targets and submit a pull request. The syntax for that file
is documented in its first few lines
