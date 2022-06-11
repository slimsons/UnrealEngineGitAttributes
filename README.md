# Unreal Engine community `.gitattributes`
### An ever growing `.gitattributes` for Unreal Engine!
#### Please feel free to contribute additional file types you encounter in the following format:

`*.[aA][bB][cC] filter=lfs diff=lfs merge=lfs -text`

# About this File:

A repository for tracking GitLFS file types associated with Unreal Engine projects via `.gitattributes` 

## `RawContent` Folder:
I've seen a few examples around of a `RawContent` folder, this .gitattributes will automatically add anything under a folder in your project directory called `RawContent`. 

Example: `UEProjectRoot/RawContent` 

![image](https://user-images.githubusercontent.com/64511782/173206779-aa8d58be-f5eb-4fa7-809c-1f825be7d4a6.png)

You can delete this if it's unwanted, or change the name.

## Catch all files regardless of capital or lower case letters:
To ensure we get `NormalMap.png`, `NormalMap.PNG`, `NormalMap.PnG` and `NormalMap.pNg`, we add the file type as:

`*.[pP][nN][gG] filter=lfs diff=lfs merge=lfs -text`

## Contributing a new filetype:
You can help make this community resource better, right here in GitHub! 

If you have a new filetype to add, you can go to the `.gitattributes` > edit > make your addition and submit a pull request, all in browser!

![v3SGrnu07d](https://user-images.githubusercontent.com/64511782/173207457-1777ef89-6aa4-4144-a179-3a8654fbb197.png)

## Contribution Format:

`*.[aA][bB][cC] filter=lfs diff=lfs merge=lfs -text`

This can be done for as many letters as needed

`*.[aA][bB][cC][dD][eE] filter=lfs diff=lfs merge=lfs -text`

###### Use however you wish no credit needed, this is not my work I've only added some filetypes to another .gitattributes I found online. 

###### If you must credit someone please credit the Unreal Engine Community.
