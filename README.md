# H3VR BepInEx Plugin Template
A new, simpler, and easy to use template for making BepInEx plugins for H3VR.

## Using this template
1. Get a copy of this project. 
   - If you intend to publish your plugin on GitHub, use the green 'Use this template' button on the repository page, then clone that new repository.
   - Otherwise click the 'Code' button and download as zip, then extract.
2. Open the `plugin/` folder in a C# IDE such as Visual Studio, Rider, or Visual Studio Code.
3. In the files `plugin/plugin.csproj` and `plugin/src/Plugin.cs` locate the TODO comments (there should be 3 total) and use them to change the name, author, and version of your plugin.
4. Done! The plugin is your own now and you're good to start writing some code.

## Using your plugin
1. After a successful build, your plugin should be output to `plugin/bin/[Debug|Release]/net35/your_name.mod_name.dll`.
2. Copy this dll to your r2mm profile's `BepInEx/plugins` folder and it should load!

## Extra TODOs:
* If you are publishing your project on GitHub, you will likely want to replace this `README.md` file and the `LICENSE` file with those appropriate for your project. If you are unsure which license to choose you can visit https://choosealicense.com/ for more info, or just remove the license all together.
