# SysML v2 support for Visual Studio Code

<table>
<tr>
<td>
    <p>
      <b>This extension is in active development and follows the monthly release of the <a href="https://github.com/Systems-Modeling/SysML-v2-Release">SysML v2 specification</a>.</b>
    </p>
    <p>
    Edit your SysML v2 model with the Visual Studio Code SysML v2 extension.
    </p>
    <p>
    This extension adds full textual support for SysML v2 files into Visual Studio Code, including features such as syntax highlighting, error detection, reference navigation. It supports the release 2022-08 release of the <a href="https://github.com/Systems-Modeling/SysML-v2-Release">SysML v2 specification</a>.
    </p>
    <p>
    This extension is provided free of charge by <a href="https://www.ellidiss.com">Ellidiss Technologies</a>.
    </p>
    <p>
    For any question, problem or new requirements, please contact us at <a href="mailto:support@ellidiss.com">support@ellidiss.com</a>.
</td>
<td width="30%"> <img width="100%" src="https://www.ellidiss.fr/public/chrome/site/logoEllidiss.png" alt="Ellidiss logo"/> </td>
</tr>
</table>

![Syntax](assets/syntax.webp)

## Content

- [Features](#Features) 
- [Release Notes](#Release-Notes)
  - [0.1.0](#010)

## Features

This extension contains a full SysML v2 textual parser allowing error detection. It detects syntax parsing errors and presents them. It parses and checks errors in all opened files and files in the current workspaces. The reference resolution works across files and uses all parsed files in the workspaces.

![Error](assets/errors.webp)

The resolved references by the parser are navigable in Visual Studio Code. Both by `Ctrl+Click` (or `Cmd+Click` on MacOS) to go to the definition or using *Go to References* or *Find all References*

![Navigation](assets/navigation.webp)

## Under development features

This extension is in active development and follows the monthly release of the [SysML v2 specification](https://github.com/Systems-Modeling/SysML-v2-Release). Many features are under development:

- [x] Support for SysML textual syntax.
  - [x] syntax highlighting.
  - [x] parsing and error detection.
  - [x] reference resolution and navigation.
- [ ] Support for KerML textual syntax.
  - [ ] syntax highlighting.
  - [ ] parsing and error detection.
  - [ ] reference resolution and navigation.
- [ ] Full list of symbol presentation and files outline. 
- [ ] Support for documentation presentation in a hover popup.
- [ ] Reference resolution error presentation.
- [ ] Rename symbol action.
- [ ] Prolog facts generation.

## Release Notes

### [0.1.0]

Initial release of `sysml-ellidiss`
