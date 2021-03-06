---
title: "What's new in Visual Studio 2019 Preview"
titleSuffix: ""
description: "Learn about the new features in the preview release of Visual Studio 2019."
ms.date: 12/04/2018
ms.prod: visual-studio-dev16
ms.technology: vs-acquisition
ms.custom: "seodec18"
ms.topic: conceptual
f1_keywords:
  - "VS.StartPage.WhatsNew"
helpviewer_keywords:
  - "Visual Studio, what's new"
  - "what's new [Visual Studio]"
author: TerryGLee
ms.author: tglee
manager: douge
ms.workload:
  - "multiple"
---
# What&#39;s new in Visual Studio 2019 Preview

**Updated for the [16.0 Preview 1 release](/visualstudio/releases/2019/release-notes-preview?context=visualstudio/default&contextView=vs-2017)**

Visual Studio 2019 Preview includes many general improvements along with new features that optimize developer productivity and team collaboration. Whether you are using Visual Studio for the first time or you've been using it for years, you'll be able to take advantage of its features for all aspects of the development lifecycle&mdash;from simplified project creation and code health management, to team- and open-source collaborative workflows.

Here's a high-level recap of what Visual Studio has to offer:

* **[Personal and team productivity](#personal-and-team-productivity)**. Productivity for everyone where it matters most.
* **[Modern development support](#modern-development-support)**. Support for your current projects and future solutions.
* **[Continuous innovation](#continuous-innovation)**. Code smart with intelligent, cloud-powered support.

> [!NOTE]
> For a complete list of new features and functionality in Visual Studio 2019 Preview, see the [release notes](/visualstudio/releases/2019/release-notes-preview?context=visualstudio/default&contextView=vs-2017).

## Personal and team productivity

It's a given that performance improvements are top of mind with every release of Visual Studio, but right up there with it is improving your productivity. Here's how we can help with that.

### New start window

The first thing you'll notice when you open Visual Studio 2019 is its new start window.

   ![The new start window in Visual Studio 2019](../ide/media/start-window.png)

This new start window presents you with options to clone or check out code, open a project or solution, open a local folder, or create a new project. Having these options presented in a simple dialog helps both beginners and advanced Visual Studio users get to code quickly.

### Better search

Formerly known as Quick Launch, our new search experience is faster and more effective. Now, search results appear dynamically as you type. And, search results include keyboard shortcuts for commands, so that you can more easily memorize them for future use.

   ![The new search feature in Visual Studio 2019](../ide/media/search-feature.png)

Whether you are looking for commands, settings, documentation, or other useful things, the new search feature makes it easier to find what you're looking for.

### One-click code cleanup

Paired with a new document health indicator is a new code cleanup command. You can use this new command to identify and then fix both warnings and suggestions with the click of a button.

   ![The new code cleanup feature in Visual Studio 2019](../ide/media/code-cleanup.png)

The cleanup will format the code and apply any code fixes as suggested by the [current settings](../ide/code-styles-and-quick-actions.md), [.editorconfig files](../ide/create-portable-custom-editor-options.md), or [Roslyn analyzers](../code-quality/roslyn-analyzers-overview.md).

### Debugger improvements

#### Search within a Watch window, and format Watch values

You've probably been there before, looking in the Watch window for a string amongst a set of values. In Visual Studio 2019 Preview, we've added search in the Watch, Locals, and Autos windows to help you find the objects and values you're looking for.

You can also format how a value is displayed within the Watch, Locals, and Autos windows.  Double-click one of the items in any of the windows and add a comma (",") to access the drop-down list of possible format specifiers, each of which includes a description of its intended effect.

   ![The new Watch window and format values feature in Visual Studio 2019](../ide/media/search-watch-window.png)

### Visual Studio Live Share

[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) is a developer service that allows you to share a codebase and its context with a teammate and get instant bi-directional collaboration directly from within Visual Studio. With Live Share, a teammate can read, navigate, edit, and debug a project that you've shared with them, and do so seamlessly and securely.

And with Visual Studio 2019 Preview, this service is installed by default.

## Modern development support

### Manage pull requests (PRs) from the IDE

We're introducing a new extension that you can download to use with Visual Studio 2019 Preview. With this new extension, you can review, run, and even debug pull requests from your team without leaving the Visual Studio IDE [(integrated development environment)](../get-started/visual-studio-ide.md). We support code in Azure Repos today, but are expanding to support GitHub and improve the overall experience.

To get started now, download the [Pull Requests for Visual Studio](https://aka.ms/pr4vs) extension from the Visual Studio Marketplace.

### Develop with .NET Core 3 Preview 1

The preview release of Visual Studio 2019 supports building [.NET Core 3](http://aka.ms/netcore3preview1) applications for any platform. We'll continue to support and improve cross-platform C++ development, as well as .NET mobile development for iOS, and Android with Xamarin.

   ![Develop apps with .NET Core 3 Preview 1 in Visual Studio 2019](../ide/media/dot-net-core-three-dev.png)

## Continuous innovation

### Per-monitor aware (PMA) rendering

If you use monitors that are configured with different display scale factors, or connect remotely to a machine with display scale factors that are different from your main device, you might notice that Visual Studio looks blurry or renders at the wrong scale.

With the release of Visual Studio 2019 Preview 1, we are taking the first steps towards making Visual Studio a per-monitor aware (PMA) application. We're laying the foundational work that will allow Visual Studio to render correctly regardless of what display scale factors you use.

   ![Per-monitor aware (PMA) rendering in Visual Studio 2019](../ide/media/per-monitor-aware-dpi-scaling.png)

### Visual Studio IntelliCode

[Visual Studio IntelliCode](/visualstudio/intellicode/) is an extension that enhances your software development efforts by using artifical intelligence (AI). IntelliCode trains across 2,000 open-source projects on GitHub&mdash;each with over 100 stars&mdash;to generate its recommendations.

Here are a few ways that Visual Studio IntelliCode can help enhance your productivity:

* Deliver context-aware code completions
* Guide developers to adhere to the patterns and styles of their team
* Find difficult-to-catch code issues
* Focus code reviews by drawing attention to areas that really matter

We initially supported only C# when we first previewed the IntelliCode extension for Visual Studio. Now, we've added support for C++ and XAML in Visual Studio, too.

And if you're using C#, we've also added the ability to train a custom model on your own code.

For more information about the extension and to download it, see the [Visual Studio IntelliCode - Preview](https://go.microsoft.com/fwlink/?linkid=872707) page on Microsoft DevLabs.

## Give us feedback

Why send feedback to the Visual Studio team? Because we take customer feedback seriously. It drives much of what we do.

* If you want to make a suggestion about how we can improve Visual Studio, you can do so by using the [Provide a Suggestion](../ide/talk-to-us.md#i-want-to-make-a-suggestion-about-visual-studio-features) tool.

* If you experience a hang, crash, or other performance issue, you can easily share repro steps and supporting files with us by using the [Report a Problem](../ide/talk-to-us.md#i-want-to-report-a-problem-with-visual-studio) tool.

## See also

* [Visual Studio 2019 release notes](/visualstudio/releases/2019/release-notes-preview?context=visualstudio/default&contextView=vs-2017)
* [What's new in Visual Studio 2017](whats-new-in-visual-studio.md)
