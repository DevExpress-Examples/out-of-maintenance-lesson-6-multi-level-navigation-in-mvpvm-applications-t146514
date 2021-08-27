<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128615474/14.1.6%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T146514)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[Form1.cs](./CS/MvpvmNavigation/Form1.cs) (VB: [Form1.vb](./VB/MvpvmNavigation/Form1.vb))**
* [Interfaces.cs](./CS/MvpvmNavigation/Interfaces.cs) (VB: [Interfaces.vb](./VB/MvpvmNavigation/Interfaces.vb))
* [Model.cs](./CS/MvpvmNavigation/Model/Model.cs) (VB: [Model.vb](./VB/MvpvmNavigation/Model/Model.vb))
* [MainFormPresenter.cs](./CS/MvpvmNavigation/Presenter/MainFormPresenter.cs) (VB: [MainFormPresenter.vb](./VB/MvpvmNavigation/Presenter/MainFormPresenter.vb))
* [Program.cs](./CS/MvpvmNavigation/Program.cs) (VB: [Program.vb](./VB/MvpvmNavigation/Program.vb))
* [DocumentManagerServiceBase.cs](./CS/MvpvmNavigation/Services/DocumentManagerServiceBase.cs) (VB: [DocumentManagerServiceBase.vb](./VB/MvpvmNavigation/Services/DocumentManagerServiceBase.vb))
* [EditFormService.cs](./CS/MvpvmNavigation/Services/EditFormService.cs) (VB: [EditFormService.vb](./VB/MvpvmNavigation/Services/EditFormService.vb))
* [ModuleActivator.cs](./CS/MvpvmNavigation/Services/ModuleActivator.cs) (VB: [ModuleActivator.vb](./VB/MvpvmNavigation/Services/ModuleActivator.vb))
* [ModuleLocator.cs](./CS/MvpvmNavigation/Services/ModuleLocator.cs) (VB: [ModuleLocator.vb](./VB/MvpvmNavigation/Services/ModuleLocator.vb))
* [ModuleTypeResolver.cs](./CS/MvpvmNavigation/Services/ModuleTypeResolver.cs) (VB: [ModuleTypeResolver.vb](./VB/MvpvmNavigation/Services/ModuleTypeResolver.vb))
* [TransitionService.cs](./CS/MvpvmNavigation/Services/TransitionService.cs) (VB: [TransitionService.vb](./VB/MvpvmNavigation/Services/TransitionService.vb))
* [EditFormViewModel.cs](./CS/MvpvmNavigation/ViewModels/EditFormViewModel.cs) (VB: [EditFormViewModel.vb](./VB/MvpvmNavigation/ViewModels/EditFormViewModel.vb))
* [MainFormViewModel.cs](./CS/MvpvmNavigation/ViewModels/MainFormViewModel.cs) (VB: [MainFormViewModel.vb](./VB/MvpvmNavigation/ViewModels/MainFormViewModel.vb))
* [ModuleAEditFormViewModel.cs](./CS/MvpvmNavigation/ViewModels/ModuleA/ModuleAEditFormViewModel.cs) (VB: [ModuleAEditFormViewModel.vb](./VB/MvpvmNavigation/ViewModels/ModuleA/ModuleAEditFormViewModel.vb))
* [ModuleAViewModel.cs](./CS/MvpvmNavigation/ViewModels/ModuleA/ModuleAViewModel.cs) (VB: [ModuleAViewModel.vb](./VB/MvpvmNavigation/ViewModels/ModuleA/ModuleAViewModel.vb))
* [ModuleBEditFormViewModel.cs](./CS/MvpvmNavigation/ViewModels/ModuleB/ModuleBEditFormViewModel.cs) (VB: [ModuleBEditFormViewModel.vb](./VB/MvpvmNavigation/ViewModels/ModuleB/ModuleBEditFormViewModel.vb))
* [ModuleBViewModel.cs](./CS/MvpvmNavigation/ViewModels/ModuleB/ModuleBViewModel.cs) (VB: [ModuleBViewModel.vb](./VB/MvpvmNavigation/ViewModels/ModuleB/ModuleBViewModel.vb))
* [ViewModelHelper.cs](./CS/MvpvmNavigation/ViewModels/ViewModelHelper.cs) (VB: [ViewModelHelper.vb](./VB/MvpvmNavigation/ViewModels/ViewModelHelper.vb))
* [BaseModuleControl.cs](./CS/MvpvmNavigation/Views/BaseModuleControl.cs) (VB: [BaseModuleControl.vb](./VB/MvpvmNavigation/Views/BaseModuleControl.vb))
* [View1.cs](./CS/MvpvmNavigation/Views/ModuleA/View1.cs) (VB: [View1EditForm.vb](./VB/MvpvmNavigation/Views/ModuleA/View1EditForm.vb))
* [View1EditForm.cs](./CS/MvpvmNavigation/Views/ModuleA/View1EditForm.cs) (VB: [View1EditForm.vb](./VB/MvpvmNavigation/Views/ModuleA/View1EditForm.vb))
* [View2.cs](./CS/MvpvmNavigation/Views/ModuleB/View2.cs) (VB: [View2EditForm.vb](./VB/MvpvmNavigation/Views/ModuleB/View2EditForm.vb))
* [View2EditForm.cs](./CS/MvpvmNavigation/Views/ModuleB/View2EditForm.cs) (VB: [View2EditForm.vb](./VB/MvpvmNavigation/Views/ModuleB/View2EditForm.vb))
<!-- default file list end -->
# Lesson 6 - Multi-level navigation in MVPVM applications


<strong>The described approach is related to the <em>preview</em> version of our MVVM Frameworks for WinForms. We've significantly improved its API. Please refer to the new documentation (<a href="https://documentation.devexpress.com/#WindowsForms/CustomDocument113955">WinForms MVVM</a>) and the code example (<a href="https://www.devexpress.com/Support/Center/p/T228317">MVVM Best Practices</a>).</strong><br />______________________________<br /><br />This example demonstrates how to implement a multi-level navigation in MVPVM application.<br /><br />Lesson 1 - Create a Simple MVPVM Application <strong>(<a href="https://www.devexpress.com/Support/Center/p/T127068">Example</a>)</strong><br />Lesson 2 - Commands. Presenter. <strong>(<a href="https://www.devexpress.com/Support/Center/p/T127997">Example</a>)</strong><br />Lesson 3 - Interaction Between Views. Services. <strong>(<a href="https://www.devexpress.com/Support/Center/p/T128579">Example</a>)</strong><br />Lesson 4 - Navigation in MVPVM Applications <strong>(<a href="https://www.devexpress.com/Support/Center/p/T136045">Example</a>)</strong><br />Lesson 5 - Advanced MVPVM Application<strong> <strong>(<a href="https://www.devexpress.com/Support/Center/p/T136053">Example</a>)</strong><br />>></strong> Lesson 6 - Multi-level navigation in MVPVM applications

<br/>


