# Acumatica Code Snippets
Code snippets are small blocks of reusable code that can be inserted in a code file.
Acumatica Code Snippets is a collection of Visual Studio code snippets designed for Acumatica.
It provides templates for:
* DACs and DAC fields
* Graph event handlers with different signature styles:
   * Classic Name Convention signature
   * Generic signature
   * Short generic signature for graph field events

# How to Install Code Snippets
* Download snippets from the [src](src) folder
* In your Visual Studio open "Code Snippets Manager" window ("Tools" -> "Code Snippets Manager")
* Add folders with downloaded code snippets. See links in the "Details on Visual Studio Code Snippets" for more details.
* If you don't see code snippets in IntelliSense suggestions make sure that IntelliSense settings are configured correctly. Open C# IntelliSense options ("Tools" -> "Options" -> "Text Editor" -> "C#" -> "IntelliSense") and configure "Snippets behavior" option to always include code snippets:
![image](https://user-images.githubusercontent.com/7687400/170328213-319a7e29-7de5-4a19-be0a-c277fb2bb29e.png)


# How to Use Code Snippets
* Type a shortcut for code snippet
    * Acumatica Code Snippets shortcuts for DAC and DAC fields start with "dac":
    ![image](https://user-images.githubusercontent.com/7687400/170328654-d343c2da-9659-4e6c-b1c8-c894dad99292.png)
    * Acumatica Code Snippets shortcuts for graph events start with underscore:
    ![image](https://user-images.githubusercontent.com/7687400/170328832-e7b23426-4a9e-4298-b53a-434a82501896.png)
* Select a shortcut from IntelliSense suggestions and press Tab key.
    *  For graph events Visual Studio will show you a list of available templates and you can select a template with a suitable signature type: 
  ![image](https://user-images.githubusercontent.com/7687400/170329005-2e854976-2a4b-4c58-bb08-ebcd66df0931.png)
* The inserted code contains placeholders like DAC and DAC Field names. You should replace them with your code. You can switch between placeholders by pressing Tab key:


![image](https://user-images.githubusercontent.com/7687400/170331206-ee2f35b8-028f-4d9c-be44-f489783ac4c5.png)

# Details on Visual Studio Code Snippets
* [Code snippets](https://docs.microsoft.com/en-us/visualstudio/ide/code-snippets?view=vs-2022)
* [Walkthrough: Create a code snippet](https://docs.microsoft.com/en-us/visualstudio/ide/walkthrough-creating-a-code-snippet?view=vs-2022)

# Contributing
You can share your code snippets with other developers by suggesting new code snippets for Acumatica. 
Please create a separate branch with your snippets and make a pull request into the `main` branch. 

Add @SENya1990 (Sergey Nikomarov) to reviewers
