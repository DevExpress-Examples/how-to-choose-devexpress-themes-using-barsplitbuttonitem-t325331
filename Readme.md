<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/ThemeSplitButtontem/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/ThemeSplitButtontem/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/ThemeSplitButtontem/MainWindow.xaml.cs) (VB: [MainWindow.xaml](./VB/ThemeSplitButtontem/MainWindow.xaml))
<!-- default file list end -->
# How to: Choose DevExpress Themes Using BarSplitButtonItem


<p>This example demonstrates how to use the BarSplitButtonItem to select <a href="https://documentation.devexpress.com/#WPF/CustomDocument7407">themes</a>. All logic is incorporated into BarSplitItemThemeSelectorBehavior. So, to activate this functionality, assign the behavior to the item:</p>


```xaml
<dxb:BarSplitButtonItem>
    <dxmvvm:Interaction.Behaviors>
        <dxb:BarSplitItemThemeSelectorBehavior />
    </dxmvvm:Interaction.Behaviors>
</dxb:BarSplitButtonItem>
```



<br/>


