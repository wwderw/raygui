<img align="left" src="logo/raygui_256x256.png" width=256>

**raygui** is a simple and easy-to-use immediate-mode-gui library.

raygui was initially inspired by [Unity IMGUI](https://docs.unity3d.com/Manual/GUIScriptingGuide.html) (immediate mode GUI API).

raygui was originated as an auxiliar module for [raylib](https://github.com/raysan5/raylib) to create simple GUI interfaces using raylib graphic style (simple colors, plain rectangular shapes, wide borders, raylib default font...).

raygui is intended for **tools development**; it has already been used to develop the following tools: [rFXGen](https://github.com/raysan5/rfxgen), [rTexViewer](https://raylibtech.itch.io/rtexviewer), [rGuiStyler](https://raylibtech.itch.io/rguistyler) and [rGuiLayout](https://raylibtech.itch.io/rguilayout).

<br>

## raygui styles

raygui comes with a [default](styles/default) style automatically loaded at runtime:

![raygui default style](styles/default/style_table.png)

Some additional styles are also provided for convenience, just check [styles directory](styles).

Custom styles can also be created very easily using [rGuiStyler](https://raylibtech.itch.io/rguistyler) tool. 

Styles can be loaded at runtime using raygui `GuiLoadStyle()` function. Simple and easy-to-use.

## raygui history

raygui development started on December 2014 by two internship students (Kevin and Daniel) guided by me, objective was creating a simple and easy-to-use immediate-mode-gui module for raylib, intended for tools development. On June 2015, library was mostly functional (including basic controls) and we started working in the styling posibilities for the library, focusing on an easy way to style controls properties. Consequently, development of [rGuiStyler](https://raylibtech.itch.io/rguistyler) also started at that point... but resources were quite limited and project was stopped for several months, most of the time was invested in [raylib](https://github.com/raysan5/raylib) development.

On June 2016, project was picked up again and raygui 1.0 was released by the end of that month. During August 2016, raygui was used to develop [rFXGen](https://github.com/raysan5/rfxgen) and also an early protoype of [rGuiLayout](https://raylibtech.itch.io/rguilayout), those tools were a testbed for the library. By the end of 2016, raygui project development was stopped again for several months.

On June 2017, a complete redesign of the library started, almost from scratch, all functions were reviewed and mostly rewritten and a brand new styling system was developed. The objective was using raygui professionally in several tools. It was the beginning of raygui 2.0.

On January 2018, two students (Adria and Jordi) started working on raygui and related tools; library evolved considerably in the following months. [rGuiStyler](https://raylibtech.itch.io/rguistyler) was completely redesigned and rewritten from scratch (rGuiStyler v2.0). [rGuiLayout](https://raylibtech.itch.io/rguilayout) turned from a protoype into a professional software and raygui reached version 2.0 with plenty of new controls and features.

On July 2018, I started working full time on raygui and its tools, improving the library considerably. On October 2018 [Sergio](https://github.com/anidealgift) joined the project and focused efforts on [rGuiLayout](https://raylibtech.itch.io/rguilayout) tool redesign. We reached 2019 with continuous improvement and redesigns of mostly all raygui functions along rGuiLayout 2.0 and rGuiStyler 3.0.

On March 2019, the first set of new raygui tools was published: [rFXGen 2.0](https://raylibtech.itch.io/rfxgen), [rTexViewer 1.0](https://raylibtech.itch.io/rtexviewer) and [rIconPacker 1.0](https://raylibtech.itch.io/riconpacker).

From March 2019 to June 2019 raygui development decelerated, Sergio left the project and efforts were focused on raylib 2.5, during this time one external contributor, [Vlad Adrian](https://github.com/Demizdor), completely redesigned `GuiTextBox()` and related controls and version was bumped to raygui 2.5.

During summer 2019 lots of raygui functions were reviewed, breaking compatibility to any previous version and pointing to a **raygui 2.6** update.


## raygui 2.6 provided controls

#### Container/separator controls, useful for controls organization

<img align="right" src="images/raygui_messagebox.png">

 - WindowBox
 - GroupBox
 - Line
 - Panel

#### Basic controls

<img align="right" src="images/rguistyler_v210_light_shot01.png">

 - Label
 - Button
 - LabelButton
 - ImageButton
 - Toggle
 - ToggleGroup
 - CheckBox
 - ComboBox
 - DropdownBox
 - TextBox
 - TextBoxMulti
 - ValueBox
 - Spinner
 - Slider
 - SliderBar
 - ProgressBar
 - StatusBar
 - ScrollBar
 - ScrollPanel
 - DummyRec
 - Grid

#### Advance controls
 - ListView
 - ColorPicker
 - MessageBox
 - TextInputBox

license
-------

raygui is licensed under an unmodified zlib/libpng license, which is an OSI-certified, BSD-like license that allows static linking with closed source software. Check [LICENSE](LICENSE.md) for further details.
