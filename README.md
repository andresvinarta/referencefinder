# Reference Finder

This tool allows you to easily find references to GameObjects and their components within a scene in your Unity project.

## Features
- Find GameObjects in the scene that reference a given GameObject or its components.
- Obtain information of what components and fields the GameObject is referenced in.
- Easily navigate to the GameObjects that have the references.

## How to use
1. **Install The Package**:
   - Add the Reference Finder package to your project by using the Package Manager and adding it via the GitHub repository URL.

2. **Access The Tool**:
   - Open your Unity project with the package installed.
   - Navigate to the **GameObject** menu at the top of the Unity editor.
   - Under the **GameObject** menu, you will find the option **Find GameObject References**.
   - Click on **Find GameObject References** to open the tool window.
  
3. **Use The Tool**:
   - In the **Target GameObject** field, select or drag and drop the GameObject you want to find the references for.
   - Click on **Find References** to show all the references found for the given GameObject.

4. **The references found are formatted as follows**:
    - GameObject with references' name 1
        - Component's name 1 -> Field's name (Type of field)
 
    - GameObject with references' name 2
        - Component's name 1 -> Field's name (Type of field)
        - Component's name 2 -> Field's name (Type of field)

**If no references have been found, it will say so.**
