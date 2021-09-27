# Matthew Hawley
https://brave-tree-02f4fbe10.azurestaticapps.net/

![MyBlazorApp2](https://user-images.githubusercontent.com/62121542/134992332-13258033-ff8e-40a1-ac19-19adcc7c3798.png)

# Modify a project in Visual Studio
Prerequisite: a project on GitHub that runs with Azure

Open Visual Studio and (one time only) choose Clone repository from the start screen or the File menu.

  Paste the address of your GitHub repository containing your Blazor web app

Open NavMenu.razor from the Client/Shared folder. 

  Change "Blazor Starter" to your name. 

Open Index.razor from the Client/Pages folder

  Change "Welcome to your new app." to an introduction to you and/or your project. Carefully make any other changes you would like by adding html elements (reference w3schools) and save the file. This can be anything you would want a potential employer to see. 

From the Git menu, click Commit, the click Push, enter a message describing what you changed like "changed Hello World", click Commit All

  When you refresh your repository home page on GitHub you should see evidence of your commit and push

  In the Actions tab in your repository you should see that the workflow is running. Once it turns green 

Open Counter.razor and figure out how it works

  Update to match the code at https://dotnet.microsoft.com/learn/aspnet/blazor-tutorial/modify if necessary

Add a new page to do input, processing, and output. (You could copy and paste an existing page then rename it.)

  You can test processing with a regular C# project or with a site like ideone.

Output with code like Console.WriteLine(num.ToString());

  See Sample code for a page that does input, processing, and output below

Add the new page to the navigation menu.

  See code to add to NavMenu below

Commit and push

Submit a link to your live page through Azure that does IPO 
