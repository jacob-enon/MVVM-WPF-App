## MVVM-WPF-App
A template for an MVVM WPF App. This uses a private Nuget so will not work externally.

#Contains:
- Folders for Model, View, ViewModel
- A reference to BigJacob.MVVM
- A MainViewModel.cs (that implements BigJacob.MVVM.BaseViewModel)
  - This contains regions for Properties, Commands, and Methods (I find I seldom have more than 1 ctor so didn't want a region for it)
- A MainWindow.xaml that has predefined "border" rows and columns (20px each border) and a single row and column to use

#Note:
This repo contains a .zip file containing the template ready to import to Visual Studio (WPF MVVM App.zip)
This can be imported as follows:
1. Download the .zip file. Do not unzip it
2. Navigate to the Visual Studio settings directory in File Explorer (this is often in Documents)
3. Navigate to ...\Templates\ProjectTemplates\Visual C#
4. Copy "WPF MVVM App.zip" into the template directory. This can now be used as a project template in Visual Studio
