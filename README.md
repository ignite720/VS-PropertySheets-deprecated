# VS-PropertySheets-deprecated
This repository uses an additional Property Sheet file (_dll-bin-add-last.props) to ensure that multiple Dynamic-link library can be used in Visual Studio project.
##### Because this method requires an additional file, it was deprecated, keep it here for archival purposes only.


> How to use:
> 1. Clone the repository to an absolute path, e.g. D:\\dev2 (assuming your .props are stored in this directory, the main purpose is to reuse the same library in multiple projects)
> 2. In the Property Manager, right-click your project and select `Add Existing Property Sheet...`.
> 3. Add any number of .props files. (Static library or dynamic library)
> 4. Optional: If the .props you added earlier contain a Dynamic-link library, you need to add this file at last. (_dll-bin-add-last.props)
