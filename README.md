# Unity3dRider

##How to:
1. Open Unity Edit -> Preferences ->External Tools
2. Browse -> Select Rider.exe / .lnk or rider.sh or Rider.app depending on the OS
3. Put the file to Assets\Plugins\Editor
4. Double click to file or error message in Unity should open Rider and navigate to file or file and line.

I have tried it in Windows, Ubuntu and MacOs

##Common problems solved by plugin
1. Basic Open Solution and Navigate to file and line
2. RIDER-1261 Symbols are not resolved across projects in a single solution (i.e. Unity Editor scripts do not see symbols in main project)
3. 'Go To Declaration' problem. Details here https://rider-support.jetbrains.com/hc/en-us/community/posts/207243685-Unity3D-support
4. RIDER-573 System.Linq can not be found in a new Unity project
5. Simple Debugging UnityEditor is implemented within the plugin, but better debugging support is planned in Rider itself- follow https://youtrack.jetbrains.com/issue/RIDER-485
6. LangVersion is set to 5.0, which prevents Rider to suggest C# 6 language improvements
