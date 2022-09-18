## Package Name Changing Do it Serially.
###### AndroidManifest.xml
* package="com.**companyname.packagename**"
* Change Company name by Pressing **Shift+F6**
* Example: Select  **companyname** and press **Shift+F6** change it to **earningaide**
* then Change Package name by Pressing **Shift+F6**
* Example: Select  **packagename** and press **Shift+F6** change it to **embedplayer**
* it will look like bellow
* package="**com.earningaide.embedplayer**"

###### Gradle Scripts > build.gradle (Module:App Name.app)
- go to **build.gradle (Module:App Name.app)**
- applicationId "**com.companyname.packagename**"
- change it to bellow 
- applicationId "**com.earningaide.embedplayer**"
- then click **Sync Now** and wait

###### settings.gradle (Project Settings)
- rootProject.name = "**App Name**"
- Change **App Name**
- then click **Sync Now** and wait
