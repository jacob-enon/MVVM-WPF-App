# MVVM-WPF-App
A template for an MVVM WPF App. This uses a private Nuget so will not work externally.

Contains:
- Folders for Model, View, ViewModel
- A reference to BigJacob.MVVM
- A MainViewModel.cs (that implements BigJacob.MVVM.BaseViewModel)
  - This contains regions for Properties, Commands, and Methods (I find I seldom have more than 1 ctor so didn't want a region for it)
- A MainWindow.xaml that has predefined "border" rows and columns (20px each border) and a single row and column to use
