<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128654133/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2258)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/LabelStyle/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/LabelStyle/MainWindow.xaml))
<!-- default file list end -->
# How to change styles of labels for individual layout items


<p>The following code shows how to change the styles of labels for individual layout items, or all of them. The style is changed via the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutItem_LabelStyletopic">LayoutItem.LabelStyle</a> property.</p>
<p>Styles of layout items' labels can be customized via the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutItem_LabelStyletopic">LayoutItem.LabelStyle</a> property. This example demonstrates two approaches to changing the LabelStyle property

* for all layout items belonging to a container - via the container's <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutGroup_ItemStyletopic">LayoutGroup.ItemStyle</a> property. In this example, this style specifies the blue foreground color for labels
* for individual layout items - directly via their <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfLayoutControlLayoutItem_LabelStyletopic">LayoutItem.LabelStyle</a> properties. In the example, this style, applied to the first layout item (Model), paints the item's label in red.</p>

<br/>


