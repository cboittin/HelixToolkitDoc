# HelixToolkitDoc

Quick and dirty documentation for Helix Toolkit generated with docfx.

Generated from release 2.20.2 (Feb 01, 2022) for SharpDX.Wpf

## Usage

Clone or download this repository, then open _site/index.html.

## How to generate up to date documentation

- Clone the Helix Toolkit repository
- Open the HelixToolkit.SharpDX solution
- Remove all UWP, WinUI, Tests and examples projects
- Build the solution
- Add a new Class Library project (C#)
- Add the nuget package docfx.console to that project
- Delete the auto-generated .cs file
- Build the project
  - if necessary, remove the auto-generated AssemblyInfo.cs file from the Properties folder and build again
- Docfx' default configuration files should appear in your project. Delete the articles folder
- Copy the docfx.json and index.md files, and the templates and api folders from this repo into your newly created docfx project
- Build your docfx project. It might take a little while and complain a lot about duplicate elements, but it should work anyway.
