Peristent Mobile Foundation
===
## ResourceRequestWeb
A sample application demonstrating the use to the WLResourceRequest API in JavaScript.

### Tutorials
https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/application-development/resource-request/javascript

### Usage
1. Use either Maven, MobileFoundation CLI or your IDE of choice to build and deploy the `JavaAdapter` adapter.

  The `JavaAdapter` adapter can be found in https://github.com/Persistent-Mobile-Foundation/Adapters.

2. From a command-line window, navigate to the project's root folder and run the command: `pmfdev app register web com.sample.resourcerequestweb`.

3. You can either set-up a [Web development environment](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/installation-configuration/development/web/) that fits your needs, or use the provided Node.js-based reverse proxy.

4. Download PMF Web SDK from PMF Console and Install PMF web SDK using npm i(path of web SDK).

#### WebSphere Liberty or Node.js
Follow the [Setting up the Web development environment](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/installation-configuration/development/web/) tutorial.

#### Using the provided Node.js-based reverse proxy
1. Make sure you have Node.js installed.
2. Navigate to the sample's root folder and run the command: `npm install` followed by: `npm start`.
3. In a browser, load the URL [http://localhost:9081/sampleapp](http://localhost:9081/sampleapp).

### Supported Levels
Peristent Mobile Foundation 9.X

License

Licensed Materials - Property of Persistent © Copyright 2023 Persistent Systems. Portions of this code are derived from IBM Corp © Copyright IBM Corp. 2006, 2016.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
### Third Party
This sample makes use of:

* Nodejs to load RequireJS
* RequireJS to load the MobileFirst SDK
