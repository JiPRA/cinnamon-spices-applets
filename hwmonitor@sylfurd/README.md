Graphical Hardware Monitor
==========================

**Graphical Hardware Monitor** is an applet that displays realtime CPU and memory load.

The code for this applet can be found under hwmonitor@sylfurd here : [cinnamon-spices-applets](https://github.com/linuxmint/cinnamon-spices-applets/)

Issues can be reported here : [Issues](https://github.com/linuxmint/cinnamon-spices-applets/issues)

### Changes

You can open the configuration dialog by right-clicking the applet and selecting **Configure...**.

* **NEW** Configuration dialog has been cleaned up and divided into pages.
* **NEW** Some new themes have been implemented. (Thanks to **@cgvirus**)
* There are two new graphs showing internet traffic in and out. Note that you might need to adjust the values for your Internet speed in the configuration dialog, both in and out, for the graphs to look good. The default value is 100 Mbit/s. You might want to set the values to slightly higher or than the Internet speed you have paid for. You can show the graphs in a linear or logarithmic scale.
* You can now turn on or off each individual graphs.
* You can now choose the width (horizontal panels) or the height (vertical panels) of each individual graph.
* You can now show or hide a detail label, which show for example CPU usage %, or used memory etc.
* You can now control the font size of both the main label and the detail label.
* Select the update frequency for the graph, by selecting the number of seconds between updates in the Update frequency combo.
* Select theme : If you select **dark theme**, the graph will be drawn in dark colors and vice versa for **light theme**. If you select **custom theme** you can customize the colors so that they match your desktop theme perfectly.
* You can set a custom label for each graph. By doing this you will override the labels from the language files.
* You can now add more than one **Graphical Hardware Monitor** to your panels. Might be useful for people with more than one monitor.
* The applet now works in both vertical and horizontal panels.

### Requirements

**Graphical Hardware Monitor** requires the **Gtop** package to collect system information. It might allready be installed on your system, but if the applet or graph is not shown, you might need to install the **Gtop** package manually.

* **Ubuntu/Mint**: install the package **gir1.2-gtop-2.0**
* **Fedora**: install the package **libgtop2-devel**
* **Arch/Manjaro**: install the package **libgtop**

### Example

Horizontal pane example:

![screenshot](https://raw.githubusercontent.com/linuxmint/cinnamon-spices-applets/master/hwmonitor%40sylfurd/horizontal.png)

Vertical pane example:

![screenshot](https://raw.githubusercontent.com/linuxmint/cinnamon-spices-applets/master/hwmonitor%40sylfurd/vertical.png)

### Contributing

*  Sylfurd
*  Hultan (SoftTeam AB)
*  Claudiux
*  D1ceWard
*  kelebek333
*  Jason Hicks
*  spacy01
*  brownsr
*  Alan01
*  eson57
*  renepavlik
*  colinss
*  MrElectroNick
*  NikoKrause
*  giwhub
*  andreevlex
*  clefebvre
