# Wisconsin-Bureau-of-Structures-Computer-Navigator
The Bureau of Structures (BOS) in-house tool for monitoring, accessing, and distributing computer resources.

Project Description:

The Wisconsin Department of Transportation’s (WisDOT) Bureau of Structures maintains a large inventory of computer resources for use by employees in the service of various department projects. As each computer requires both regular maintenance and upkeep, a cost is incurred upon the Bureau in accordance to the inventory. For this purpose, it is necessary that the Bureau of Structures maintain accurate records and data for all active devices.

The WiBS Computer Navigator tool presents a simple UI for BoS employees to view and make use of this computer resources inventory. The goal of this project was to present the extensive active inventory information in a manner that was easily navigable and minimally complex. In addition, the tool now serves as a gateway to the WiBS Remote Access tool. Especially throughout the pandemic, many BoS employees worked remotely. As such, in order to make use of certain resources, they needed a tool by which they could remotely access either their computers or the shared, specially dedicated remote work PC's. In addition to this functionality, the laptop checkout tab is used to maintain the computer inventory in the event that a laptop or other device needs to be temporarily distributed.


My Role:

For this project, I functioned as the primary developer in order to refactor and update the application focusing mainly on refactoring the overall structural architecture of the application's code into a version of MVC framework designed for Windows Forms Apps along with updating existing and adding additional functionality.

The goal of reorganizing the code structure in this update was to divide the concerns of the project into the MVC components. By doing this, we allow for simplification of simultaneous development through separation of components with the hope of improving scalability as we further expand the application's functionality going forward.

Beyond refactoring the application into a more scalable model, I rebuilt the app to streamline its functionality and appearance into what exists today. I simplified its UI and divided its components into more specialized tabs. In addition, I added a number of new functionalities including remote connect functionality, improved resource querying, updated XML file reading, general quality of life improvements.

General Technical Information:

Project Type:
Windows Forms Application

Primarily Used Language(s):
C#
XML (Markup language for the computer inventory logs)


*Note: All code available is not intended for reuse but rather only as informative material. Any and all sensitive information contained in the solution including, but not limited to, security keys, authentication details, user information/data, and database or gateway logins necessary for normal function have been removed for the sake of security and privacy. 

Other Resources:
MVC Architecture Pdf Download and MVC Architecture Presentation included in repository.

If you have any further questions, please contact me at lukedbreyer@gmail.com or by any method found on the "About Me" page.
