# Contributing
Contributions to this repository are accepted by pull request only.  If you are new to Git or Github, you can start [here](https://docs.github.com/en/github/getting-started-with-github/quickstart)

## Conventions
All contributions should use the following conventions:
- the repository file structure follows that of The Dark Mod.  This is hopefully familiar to mappers and should help when choosing a location to put your assets.  Please follow the same convention.
- place your files in a new folder in the appropriate location.  This allows a separate README.md file to be automatically displayed for your contribution
- provide a JPEG preview of your model by including a 1280x720 image in the root of your folder
- include a .stl export of your model in the root of your folder for the 3D image preview
- provide a README.md with a brief description of your contribution, any installation instructions and links to the preview files.  Please use the [template](README.template.md) provided for the README.

See any of the existing asset folders for examples of how this should look.

## Files

Contributors are encouraged to approach this repository as not only a place to share assets, but to also _discover_ how they are put together.  Visibility of the materials files for example provides a wealth of information about how a certain appearance was achieved.

It's also very useful for quick reference.  Can't remember exactly how you put together that shader for your boat model 5 years ago and you don't have the files handy?  It's only a couple of clicks away...

As for the files themselves, you can either:
- place all required files (models, materials, skins, etc.) in the root of your folder.  This allows consumers to easily browse all files that make up your contribution
- place all files within subfolders as you would in your FM directory.  For example, folders for `skins`, `materials`, `models`, etc.  This helps a potential mapper understand how to deploy your files
- include only a .pk4 of all your files, and additionally the README.md and preview files.  This might be suitable for very large contributions, but removes the ability for users to browse through the files on the web.
- a combination of the above, where you include the individual files _and_ the .pk4.  This allows for easy discovery and download for installation.  Remember though that if you change a file in an update, you need to also provide a new version of the .pk4 file
