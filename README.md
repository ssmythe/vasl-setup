# vasl-setup
Scripts to create Patrick Ireland's standard VASL directory structures, and download VASL vmod, enhanced scenarios, boards, and extensions

## On Windows
These instructions were verified on VASSAL 3.2.15 and VASL 6.2.2

### Download and run the script
1. Right-click on the link [vasl_setup.bat](https://raw.githubusercontent.com/ssmythe/vasl-setup/master/vasl_setup.bat), and chose "Save as..." the file to your Downloads folder
  * **(IMPORTANT: Make sure to rename the file from "vasl_setup.bat.txt" to "vasl_setup.bat" in your Save As dialog)**
2. Open Windows Explorer, and navigate to your Downloads folder
3. Double-click "vasl_setup.bat"
4. The script will finish in about a minute, depending on your Internet connection speed

### Setup VASL module and preferences
1. Launch VASSAL
2. In the "VASSAL" window, choose the "File > Open Module..." menu option
3. Navigate to "C:\ASL\VASL"
4. Click the "vasl-X.Y.Z.vmod" where X.Y.Z is the version (e.g. "vasl-6.2.2.vmod")
5. Click the "Open" button
6. A "Processing Image Tiles" window will pop up and show some processing.  It will close that window and launch VASL "Welcome" dialog when it's done
  * **(NOTE: The Welcome dialog may be behind other applications, like your web browser, so you may need to minimize applications until you see it.)** 
7. Click the "Cancel" button
8. In the "VASL controls" window, chose the "File > Preferences..." menu option
9. In the "Preferences" window, in the "General" tab, click the "Select" button next to "Board Directory"
10. Navigate to "C:\ASL\VASL\boards"
11. Click the "Open" button
12. In the "Preferences" window, in the "Extensions" tab, click the "Select" button next to "Extensions Directory"
13. Navigate to "C:\ASL\VASL\extensions-ssmythe"
14. Click the "Open" button
15. In the "Preferences" window, Click the "OK" button

### Test VASL setup by loading an Enhanced Scenario
1. In the "VASL controls" window, chose the "File > Load Game..." menu option
2. Navigate to "C:\ASL\Scenarios\MMP\StarterKit\Enhanced"
3. Click on the "S 001 Retaking Vierville - Enhanced.vsav" scenario file
4. Click the "Open" button
5. The scenario should load just fine with no error messages in the "VASL controls" window
