# Xcodegen issue

* MRE for https://github.com/yonaskolb/XcodeGen/issues/1554

1. execute xcodegen
2. Add a developer team
3. Compile the app (should compile fine)
4. execute xcodegen again
5. Compile the app 
	* should cause an issue that the package can't be found anymore
	* Have to restart xcode, then compilation works again
