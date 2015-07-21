# ionic-sidemenu-vstools
This sample provides a version of the Ionic Starter Template for SideMenu that works with Visual Studio Tools for Apache Cordova, Android, iOS, and Windows targets.

This sample is based on the original Ionic sample at https://github.com/driftyco/ionic-starter-sidemenu

Some changes were made to support Windows targets. For info on changes made to the project to support Windows,
see this blog post: http://blogs.msdn.com/b/msdn_answers/archive/2015/02/10/running-cordova-apps-on-windows-and-windows-phone-8-1-using-ionic-angularjs-and-other-frameworks.aspx

### Requirements
Visual Studio 2015 RTM with optional cross-platform components for HTML/JavaScript installed.

Note: In VS 2015 RC/RTM, project structure is updated for compatibility with 3rd party tools and CLIs. If you need to migrate an older version of an app based on this template to VS 2015 RTM, see Known Issues (http://go.microsoft.com/fwlink/?LinkID=398782).

### Running The App
After you finish downloading and installing VS Tools for Apache Cordova (http://go.microsoft.com/fwlink/?LinkId=524433), open up the project in Visual Studio.

### Updates
- 05/04/15: Project structure updated for VS 2015 RC. This makes the project interoperable with the Ionic CLI.

### Known Issues
- When debugger is attached on Windows targets, you can get a WWAHost.exe runtime error in some cases when you navigate between pages.
   Issue is currently under investigation.
   Workarounds: 
   1. When you start the app, close the DOM Explorer window before you hit the error. This will allow you to debug by hitting breakpoints, viewing the call stack, etc. Or:
   2. When targeting Win/WinPhone, use Start without Debugging (Alt+F5)
- The Android 4.3 browser has some known limitations, and so the sample may not work perfectly on such devices


## Terms of Use
By downloading and running this project, you agree to the license terms of the third party application software, Microsoft products, and components to be installed. 

The third party software and products are provided to you by third parties. You are responsible for reading and accepting the relevant license terms for all software that will be installed. Microsoft grants you no rights to third party software.


## Important links
1. AngularJS License (https://github.com/angular/angular.js/blob/master/LICENSE)
1. winstore-jscompat.js License (https://github.com/MSOpenTech/winstore-jscompat/blob/master/License.txt)


## License
```
The MIT License (MIT)

Copyright (c) Microsoft Corporation

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```



