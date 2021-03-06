# Create a template User Interface for an Entity Service

This guide will show you how to manage the user interface of your Dirigible project.
</br>
The goal of the guide is to create a page, that contains a list with data from a database table in our project.
</br>The data is obtained from an Entity Service and is structured by the given metadata in a *.entity file.

## Prerequisites
You must have an Entity Service created.</br>
Check out the [Create an Entity Service for the Database Table](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateEntityService.md) task to find out how to create one.

## Steps

**1.**  In the **Workspace** _right-click_ on the desired entity file.

**2.** From the dropdown menu _select_ **Generate/User Interface for Entity Service**.

**3.**  From the popup _select_ a template. 

> For the following example _select_ **List Entities** and then _click_ **Next**.

**4.**  _Select_ the data fields that you want your list to contain and _click_ **Next**.

> The fields shown are described in the .entity metadata.

**5.**  _Select_ the name and location of the target *.html file and _click_ **Next**.

> The file should be placed in the **Web Content** of your project.

**6.**  Give the Page a Title and _click_ **Finish**.

Results
----
###

 When all of the steps are completed, in the *Web Content* of your project, you should have a *.html file,
 which contains a list with the Entity Service's data. It can be hyperlinked via a main menu, for example.

_For more information see:_ 
</br> [Scripting Service](http://www.dirigible.io/help/scripting_services.html)
</br> [Entity Service](http://www.dirigible.io/help/entity_service.html)
</br> [Entity Service Creation](http://www.dirigible.io/samples/entity_service.html)


## Navigation
Guide: [Understanding Dirigible](https://github.com/dirigiblelabs/curriculum/edit/master/IvoYakov/DirigibleDoc)
</br>
1. [Create a Project in Dirigible](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateProject.md)
2. [Create a Database Table](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateDatabaseTable.md)
3. [Create an Entity Service for the Database Table](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateEntityService.md)
4. [Create a User Interface for the Service](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateUserInterface.md)
