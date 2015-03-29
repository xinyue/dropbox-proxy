# Dropbox Proxy

With Dropbox Proxy you can use your own domain to serve the files published in your [Dropbox](http://www.dropbox.com) public folder.
Before:
  URL'http://dl.dropboxusercontent.com/u/YOUR-DROPBOX-NUMBER/file-name.zip'.
After:
  URL 'http://dl.YOUR-DOMAIN.com/file-name.zip'

# Instructions
* Download this files. 
* Create a new GAE app.
* Edit 'application: ' in app.yaml with your app ID.
* Edit 'DROPBOX_USER' in mirror.py with your dropbox user ID.
* Push changes to GAE using GAE SDK.
* Optional: Go to GAE -> proyect -> Compute -> App Engine -> configuration and add your personal domain.
(you can use your-app-id.appspot.com instead)

# Credits
This script is a reduction from a great proxy [mirrorrr](https://github.com/bslatkin/mirrorrr) created by [Brett Slatkin](http://www.onebigfluke.com). It is also based on [dropbprox](http://code.google.com/p/dropbprox) by [Paulo Jerônimo] (http://paulojeronimo.com) for an older version of python.

# License
Copyright 2015 Alex Fermon

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
