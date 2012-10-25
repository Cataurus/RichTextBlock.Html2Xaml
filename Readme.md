NuGet package: [http://nuget.org/packages/RichTextBlock.Html2Xaml](http://nuget.org/packages/RichTextBlock.Html2Xaml)

DocumentUp version of the documentation: http://macawnl.github.com/RichTextBlock.Html2Xaml/

# RichTextBlock.Html2Xaml

## Introduction

The WinRT RichTextBlock control serves to display read-only rich formatted text.
However, it supports a limited subset of XAML, and no HTML.

In scenario's where you want to display a field that contains HTML rich 
formatted text (e.g. when you have clients on multiple platforms, such as 
web, WinRT, iOS and Android), this package offers an alternative to 
using an embedded browser control. Using a browser control impacts 
performance and limits the UI experience (e.g. the WebView 
control does not support transparency).

**RichTextBlock.Html2Xaml** adds an Html extension property to RichTextBlock 
controls, that you can set (or data bind) to a string containing an Html 
snippet.

## Functionality
The RichTextBlock control only supports a limited set of XAML; this package
supports translating an equivalent limited set of HTML markup via an XSLT. 
The XSLT allows for simple modification or extension of the XAML to HTML
conversion. Any unsupported HTML tags will be discarded, but their text content
will be displayed.

The extension property is implemented in two simple source files that can be 
modified easily: one C# and one XSLT source file, no binaries.

## Distribution: NuGet
**RichTextBlock.Html2Xaml** is distributed as a [NuGet](http://nuget.org/packages/RichTextBlock.Html2Xaml) 
package. The package is named **RichTextBlock.Html2Xaml**. The 
**RichTextBlock.Html2Xaml** NuGet package places two files in your Windows 
Store project, in the Common folder:

- `Common\RichTextBlockHtml2Xaml.xslt`
- `Common\RichTextBlockProperties.cs`

## Usage

TODO: Add XAML snippets, html and data bound examples.

## Dev tips

TODO: add XSLT debugging and XAML result preview tips