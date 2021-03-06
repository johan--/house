CHANGELOG
===

Alternately, the _Daily Diary of my Programming Dreams_.

### 201503301950

* Added **fiddles/jquery/fiddle-0006-VideoPlayer** ~ [js fiddle](http://jsfiddle.net/bradyhouse/mszj46cf/)
* Added **fiddles/extjs/fiddle-20150330-BufferedDataGrid** ~ [sencha fiddle](https://fiddle.sencha.com/#fiddle/kh9)
* Added Updated LICENSE
* Added .gitattributes
* Added .editorconfig

### 201503311810

* Added **fiddles/extjs/fiddle-20150331-ExtJS4ColumnFiltering** ~ [sencha fiddle](https://fiddle.sencha.com/#fiddle/kie)
* Added **fiddles/extjs/fiddle-20150331-ColumnFiltering** ~ (under construction)
* Added **fiddles/jquery/fiddle/fiddle-0007-BootstrapVideoCarousel** ~ [js fiddle](http://jsfiddle.net/bradyhouse/86mp2t4q/)

### 201504031810

* Updated **fiddles/extjs/fiddle-20150331-ColumnFiltering** ~ [sencha fiddle](https://fiddle.sencha.com/#fiddle/km0)
    * This fiddle illustrates how to enable column filter on a grid panel bound to a Ext.data.JsonStore--ie an "unbuffered" store. It combines the structure from fiddle-20150331-ExtJS4ColumnFiltering with the json data file (781 records) from fiddle-20150330-BufferedDataGrid.
    * Additionally, this fiddle introduces an alternate (or new) "template" style.  The fiddle is rendered using a pop-up window.  In the app.js, the actual fiddle code ends when the win.show() call.  At run time, the fiddle code runs in the modal pop-up (foreground). The boiler plate code appears behind it (background).
* Added **scripts/bin/house-disk-space.sh**
    * This script can be used to determine how much disk space is available on your machine.  I created it because my Mac is constantly running out of space and I am sick of having to open the "Macintosh HD Info" dialog.  This script tells me how much space I have straight from the command line.
* Added **fiddles/extjs/fiddle-20150401-BufferedColumnFiltering** ~ (Doesn't work)
    * This fiddle illustrates how to enable column filter on a grid panel bound to a Ext.data.BufferedStore.  It combines the structure from fiddle-20150331-ExtJS4ColumnFiltering with the json data file (781 records) from fiddle-20150330-BufferedDataGrid using a BufferedStore. Similar to the kitchen sink example [sencha 5.1.0 buffered store example](http://dev.sencha.com/ext/5.1.0/examples/grid/buffered-store.html), column filtering doesn't work.
* Added **fiddles/extjs/fiddle-20150402-UnBufferedColumnFiltering** ~ [Sencha Fiddle](https://fiddle.sencha.com/#fiddle/ko5)
    * This fiddle is a response to fiddle-20150401-BufferedColumnFiltering. It illustrates how to enable column filter on a grid panel bound to a vanilla data store--i.e. Ext.data.Store.  It combines the structure from fiddle-20150331-ExtJS4ColumnFiltering with the json data file (781 records) from fiddle-20150330-BufferedDataGrid using a DataStore.  Additionally, its an example of using the "bufferedrender" plugin as per the forum post ~ http://www.sencha.com/forum/showthread.php?259314.
* Added **fiddles/extjs/fiddle-20150402-CustomColumnHeaderMenu** ~ (Under Construction)
    * Fiddle exploring how to override the default menu exposed by the column collection of the Ext.grid.Panel.
* Added **fiddles/three/fiddleParabola**
    * Fiddle used to rewrite the fiddles/three/template/app.js template using a global window.app variable.
* Added **fiddles/extjs/fiddle-20150403-SpreadSheetSelection** ~ [Sencha Fiddle](https://fiddle.sencha.com/#fiddle/kqj)
    * Fiddle exploring how to leverage the spreadsheet selection model and clipboard plugin introduced in 5.1.
* Enhanced **scripts/fiddle-fork.sh**
    1. Added support for all fiddle types
    2. Added call to the fiddle-index script
    3. Enhanced the ReadMe.Markdown update logic to append a "Forked from" section
    4. Added validation to insure that the new fiddle includes "fiddle" or "Fiddle" in the name.  NOTE - This is necessary to insure that the new fiddle is picked-up by the fiddle-index.sh script

### 201504041810

* Added [fiddles/exts/fiddle-20150405-fiddle3DPieChart](fiddles/extjs/fiddle-20150405-fiddle3DPieChart/README.markdown)
    * Fiddle adapted from Sencha's Chart Kitchen Sink's "Basic Pie Chart" example. The second pie chart is identical to the first except for the series type attribute, which has been changed to the new pie3d series type. This series type was introduced in ExtJS 5.1.

### 201504091810

* Refactored scripts/fiddle.sh
    * This script is now the master fiddle-*.sh script. It can be used as the single entry point interacting with the other "fiddle" prefixed scripts.
* Added scripts/fiddle-create.sh
    * This script replaces the scripts/fiddle.sh script. It can be used to create a specific type of fiddle.
* Enhanced scripts/bin/house-node-fs.sh to support an optional port parameter.  When supplied, the port number will override the default (hard coded) 8889 port number.
    * Similar enhancement made to--
        1. scripts/bin/house-node-fs-start.sh
        2. scripts/fiddle-start.sh
        3. scripts/fiddle-stop.sh
        4. scripts/fiddle.sh
    * Note - This change was made because I ran into a situation today where I needed to use the default port 8889 for something else.  Plus, having flexibility to startup the fiddle server on an alternate port makes sense-- its a good to have.
* Added [fiddles/extjs/fiddle-20150408-GridDynamicFieldFilter](fiddles/extjs/fiddle-20150408-GridDynamicFieldFilter/README.markdown)
* Added [fiddles/extjs/fiddle-20150407-GridFilteringToolBar](fiddles/extjs/fiddle-20150407-GridFilteringToolBar/README.markdown)
* Added [fiddles/extjs/fiddle-20150407-ChainedStoreFiltering](fiddles/extjs/fiddle-20150407-ChainedStoreFiltering/README.markdown)
* Added [fiddles/three/fiddle-0003-18Spheres](fiddles/three/fiddle-0003-18Spheres/README.markdown)

### 201504121810

* Added [fiddles/jquery/fiddle-0008-CanvasMouseCapture](fiddles/jquery/fiddle-0008-CanvasMouseCapture)
* Added [fiddles/jquery/fiddle-0009-CanvasMouseRecordRestore](fiddles/jquery/fiddle-0009-CanvasMouseRecordRestore)
* Added [fiddles/extjs/fiddle-20150412-GridFieldFilterContext](fiddles/extjs/fiddle-20150412-GridFieldFilterContext)

### 201504151810

* Added [fiddles/extjs/fiddle-20150412-GridItemContextFilterPlugin](fiddles/extjs/fiddle-20150412-GridItemContextFilterPlugin)
* Added [fiddles/extjs/fiddle-20150414-GridDynamicTagFilter](fiddles/extjs/fiddle-20150414-GridDynamicTagFilter)
* Added [fiddles/extjs/fiddle-20150414-HTMLEditor](fiddles/extjs/fiddle-20150414-HTMLEditor)
* Added [fiddles/chrome](fiddles/chrome)
* Added [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
    * Reflected changes:
        1. [scripts/fiddle.sh](scripts/fiddle.sh)
* Added [scripts/fiddle-chrome.sh](scripts/fiddle-chrome.sh)
    * Reflected changes:
        1. [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        2. [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
* Added [fiddles/extjs/fiddle-20150415-SpreadsheetClipBoardMixin](fiddles/extjs/fiddle-20150415-SpreadsheetClipBoardMixin)
* Added [fiddles/chrome/fiddle-0001-templateTest](fiddles/chrome/fiddle-0001-templateTest)
* Added [fiddles/extjs/fiddle-20150415-MixinBeforeConstructorSetPlugins](fiddles/extjs/fiddle-20150415-MixinBeforeConstructorSetPlugins)
* Deleted fiddles/extjs/fiddle-20150402-CustomHeaderMenu
* Added [fiddles/extjs/fiddle-20150414-GridDynamicTagFilter](fiddles/extjs/fiddle-20150414-GridDynamicTagFilter)
* Added [fiddles/jquery/fiddle-0012-DifferentialInheritance](fiddles/jquery/fiddle-0012-DifferentialInheritance)

### 201504201810

* Added [fiddles/jquery/fiddle-0013-ConstructorInvocationPattern](fiddles/jquery/fiddle-0013-ConstructorInvocationPattern)
* Added [fiddles/extjs/fiddle-20150420-GridItemContextTagFilterMixin](fiddles/extjs/fiddle-20150420-GridItemContextTagFilterMixin)
* Added [fiddles/extjs/fiddle-20150421-GridItemContextDistinctTagFilterMixin](fiddles/extjs/fiddle-20150421-GridItemContextDistinctTagFilterMixin)
* Added [fiddles/extjs/fiddle-20150423-ComboBoxNumericFormatting](fiddles/extjs/fiddle-20150423-ComboBoxNumericFormatting)
* Added [fiddles/extjs/fiddle-20150423-VanillaClassDebugHook](fiddles/extjs/fiddle-20150423-VanillaClassDebugHook)
* Added [fiddles/php/fiddle-wpExtJSGrayTheme](fiddles/php/fiddle-wpExtJSGrayTheme)

### 201505011810

* Added [scripts/fiddle-node.sh](scripts/fiddle-node.sh)
    * Reflected changes:
        1. [scripts/fiddle.sh](scripts/fiddle.sh)
        2. [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        3. [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        4. [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
        5. [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
* Added [fiddles/jquery/fiddle-0011-Calculator](fiddles/jquery/fiddle-0011-Calculator)
* Added [fiddles/chrome/fiddle-0002-Calculator](fiddles/chrome/fiddle-0002-Calculator)
* Added [fiddles/node/fiddle-0001-SocketIoChat](fiddles/node/fiddle-0001-SocketIoChat)
* Added [fiddles/dojo/fiddleEnhancedGridPlugins](fiddles/dojo/fiddleEnhancedGridPlugins)

### 201505061810

* Added [fiddles/three/README.markdown](fiddles/three/README.markdown)
* Added [fiddles/extjs/fiddle-20150505-GridFilteringFloatBug](fiddles/extjs/fiddle-20150505-GridFilteringFloatBug)
* Added [fiddles/jquery/fiddle-0009-CanvasMouseRecordRestore](fiddles/jquery/fiddle-0009-CanvasMouseRecordRestore)
* Removed fiddles/phantomjs (unfinished)
* Added [fiddles/jquery/fiddle-0014-RequestAnimationFrameLimit](fiddles/jquery/fiddle-0014-RequestAnimationFrameLimit)
* Added [fiddles/jquery/fiddle-0015-xUnitTesting](fiddles/jquery/fiddle-0015-xUnitTesting)
* Enhanced [fiddles/jquery/template](fiddles/jquery/template) to include test.html, test.js files
    * Reflected changes:
        1. [scripts/fiddle-jquery.sh](scripts/fiddle-jquery.sh)
* Added [scripts/fiddle-tween.sh](scripts/fiddle-tween.sh)
    * Reflected changes:
        1. [scripts/fiddle.sh](scripts/fiddle.sh)
        2. [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        3. [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        4. [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
        5. [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        6. [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
        7. [fiddles/index.html](fiddles/index.html)
* Added [fiddles/tween/fiddle-0001-BouncingBall](fiddles/tween/fiddle-0001-BouncingBall)
* Added [fiddles/tween/fiddle-0002-100MovingDots](fiddles/tween/fiddle-0002-100MovingDots)
* Added [fiddles/tween/fiddle-0003-CreatejsEaseQuadIn](fiddles/tween/fiddle-0003-CreatejsEaseQuadIn)

### 201505210420

* Added [fiddles/extjs/fiddle-20150521-ClearStoreAndColumns](fiddles/extjs/fiddle-20150521-ClearStoreAndColumns)

### 201505310420

* Added [fiddles/jquery/fiddle-0016-BackgroundCover](fiddles/jquery/fiddle-0016-BackgroundCover)
* Added [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
    * Reflected changes:
        1. [scripts/fiddle.sh](scripts/fiddle.sh)
* Added [fiddles/extjs/fiddle-20150528-TableLayout](fiddles/extjs/fiddle-20150528-TableLayout)
* Added [fiddles/extjs/fiddle-20150528-GridSubColumns](fiddles/extjs/fiddle-20150528-GridSubColumns)
* Added [fiddles/java](fiddles/java)
* Added [fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleBinaryOperator.java](fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleBinaryOperator.java)
* Added [fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleFibonacci.java](fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleFibonacci.java)
* Added [fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleNoArguments.java](fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleNoArguments.java)
* Added [fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleStreamFilter.java](fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleStreamFilter.java)
* Added [fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleStreamMap.java](fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleStreamMap.java)
* Added [fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleReduceFilter.java](fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleReduceFilter.java)
* Added [fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleReduceMap.java](fiddles/java/src/io/bradyhouse/fiddles/java8/FiddleReduceMap.java)

### 201506020420

* Added [fiddles/jquery/fiddle-0017-DateSerialization](fiddles/jquery/fiddle-0017-DateSerialization)
* Added [fiddles/extjs/fiddle-20150602-GridRecordToolTip](fiddles/extjs/fiddle-20150602-GridRecordToolTip)
* Updated all index.html pages to include background carousel slider
    * Reflected changes:
        1. [fiddles/resources/css/custom.css](fiddles/resources/css/custom.css)
        2. [fiddles/dojo/resources/css/custom.css](fiddles/dojo/resources/css/custom.css)
        3. [fiddles/extjs/resources/css/custom.css](fiddles/extjs/resources/css/custom.css)
        4. [fiddles/jquery/resources/css/custom.css](fiddles/jquery/resources/css/custom.css)
        5. [fiddles/three/resources/css/custom.css](fiddles/three/resources/css/custom.css)
        6. [fiddles/tween/resources/css/custom.css](fiddles/tween/resources/css/custom.css)
        7. [fiddles/jquery/fiddle-0005-BootStrapCarousel/resources/css/custom.css](fiddles/jquery/fiddle-0005-BootStrapCarousel/resources/css/custom.css)
        8. [fiddles/jquery/fiddle-0006-BootStrapVideoControls/resources/css/custom.css](fiddles/jquery/fiddle-0006-BootStrapVideoControls/resources/css/custom.css)
        9. [fiddles/jquery/fiddle-0006-VideoPlayer/resources/css/custom.css](fiddles/jquery/fiddle-0006-VideoPlayer/resources/css/custom.css)
        10. [fiddles/jquery/fiddle-0007-BootstrapVideoCarousel/resources/css/custom.css](fiddles/jquery/fiddle-0007-BootstrapVideoCarousel/resources/css/custom.css)
        11. [fiddles/jquery/fiddle-0011-Calculator/resources/css/custom.css](fiddles/jquery/fiddle-0011-Calculator/resources/css/custom.css)
        12. [fiddles/jquery/template/resources/css/custom.css](fiddles/jquery/template/resources/css/custom.css)
* Migrated dojo fiddles to CDN
    * Reflected changes:
        1. [fiddles/dojo/fiddleDateTextBox/index.html](fiddles/dojo/fiddleDateTextBox/index.html)
        2. [fiddles/dojo/fiddleEnhancedGrid/index.html](fiddles/dojo/fiddleEnhancedGrid/index.html)
        3. [fiddles/dojo/fiddleEnhancedGridPlugins/index.html](fiddles/dojo/fiddleEnhancedGridPlugins/index.html)
        4. [fiddles/dojo/fiddleEpochTimeStamp/index.html](fiddles/dojo/fiddleEpochTimeStamp/index.html)
        5. [fiddles/dojo/fiddleObjectToQuery/index.html](fiddles/dojo/fiddleObjectToQuery/index.html)
        6. [fiddles/dojo/fiddleParsingDates/index.html](fiddles/dojo/fiddleParsingDates/index.html)
        7. [fiddles/dojo/fiddleTabContainer/index.html](fiddles/dojo/fiddleTabContainer/index.html)
        8. [fiddles/dojo/template/index.html](fiddles/dojo/template/index.html)

### 201506040420

* Added [fiddles/jquery/fiddle-0018-BootstrapDatagrid](fiddles/jquery/fiddle-0018-BootstrapDatagrid)
* Updated [fiddles/jquery/template/data.json](fiddles/jquery/template/data.json) ~ Overwrote with [fiddles/extjs/template/data.json](fiddles/extjs/template/data.json)
* Updated [fiddles/jquery/template/index.html](fiddles/jquery/template/index.html) ~ Added footer link to [fiddles/jquery/template/test.html](fiddles/jquery/template/test.html)
* Added [fiddles/extjs/fiddle-20150605-ExtendToolTip](fiddles/extjs/fiddle-20150605-ExtendToolTip)
* Added [fiddles/extjs/fiddle-20150605-LockedColumns](fiddles/extjs/fiddle-20150605-LockedColumns)
* Refactored [fiddles/jquery/template/test.html](fiddles/jquery/template/test.html)
    * Reflected changes:
        1. [scripts/fiddle-jquery.sh](scripts/fiddle-jquery.sh)
* Added [fiddles/jquery/resources/js/yui-min.js](fiddles/jquery/resources/js/yui-min.js)
    * Reflected changes:
        1. Updated [fiddles/jquery/template/test.html](fiddles/jquery/template/test.html)

### 201506200420

* Added [fiddles/bash](fiddles/bash)
     * Reflected changes:
        1. [scripts/fiddle-bash.sh](scripts/fiddle-bash.sh)
        2. [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        3. [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        4. [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        5. [fiddles/bash/README.markdown](fiddles/bash/README.markdown)
* Added [fiddles/bash/fiddle-0001-FunctionBasics](fiddles/bash/fiddle-0001-FunctionBasics)
* Refactored [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
    * Note - It now ignores fiddles whose relative path has been added to the .gitignore file.

### 201506210420

* Enhanced [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
    * Note - It now appends an entry to the CHANGELOG.markdown file.
* Enhanced [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
    * Note - If the target directory doesn't exist, it now throws an error.
* Added [fiddles/bash/fiddle-0003-SystemDate](fiddles/bash/fiddle-0003-SystemDate)
* Added [scripts/fiddle-test.sh](scripts/fiddle-test.sh)
    * Note - This allows for the running of the JsTestDriver library for a given fiddle.
    * Reflected changes:
        1. Added [fiddles/jquery/fiddle-0020-JsTestDriver](fiddles/jquery/fiddle-0020-JsTestDriver)
        2. Added [scripts/bin/house-jstestdriver-start.sh](scripts/bin/house-jstestdriver-start.sh)
        3. Added [scripts/bin/house-jstestdriver-stop.sh](scripts/bin/house-jstestdriver-stop.sh)
        4. Added [scripts/bin/house-jstestdriver-test.sh](scripts/bin/house-jstestdriver-test.sh)
        5. [scripts/fiddle.sh](scripts/fiddle.sh)
        6. Added [fiddles/jquery/template/jsTestDriver.conf](fiddles/jquery/template/jsTestDriver.conf)
        7. Deleted fiddles/jquery/template/test.js
        8. Deleted fiddles/jquery/template/test.html
* Added [fiddles/jquery/fiddle-0020-JsTestDriver](fiddles/jquery/fiddle-0020-JsTestDriver)
* Deleted scripts/bin/house-java-version.sh

### 201506230420

* Added [fiddles/extjs/fiddle-20150623-ButtonSetLocalX](fiddles/extjs/fiddle-20150623-ButtonSetLocalX)
* Added [fiddles/extjs/fiddle-20150623-jsTestDriver](fiddles/extjs/fiddle-20150623-jsTestDriver)
* Added [fiddles/bash/fiddle-0002-ListCommand](fiddles/bash/fiddle-0002-ListCommand)
* Added [fiddles/three/fiddle-0002-WebGlDetection](fiddles/three/fiddle-0002-WebGlDetection)
* Added [fiddles/bash/fiddle-0004-CurlDownload](fiddles/bash/fiddle-0004-CurlDownload)
* Added [fiddles/bash/fiddle-0006-SayCommand](fiddles/bash/fiddle-0006-SayCommand)
* Added [fiddles/bash/fiddle-0007-InstallUbuntuZfs](fiddles/bash/fiddle-0007-InstallUbuntuZfs)
* Added [fiddles/bash/fiddle-0008-ZfsFileVolume](fiddles/bash/fiddle-0008-ZfsFileVolume)
* Added [fiddles/bash/fiddle-0009-TrCommand](fiddles/bash/fiddle-0009-TrCommand)
* Added [fiddles/bash/fiddle-0010-SortCommand](fiddles/bash/fiddle-0010-SortCommand)
* Added [fiddles/bash/fiddle-0011-WcCommand](fiddles/bash/fiddle-0011-WcCommand)
* Added [fiddles/bash/fiddle-0012-PrCommand](fiddles/bash/fiddle-0012-PrCommand)
* Added [fiddles/bash/fiddle-0013-NlCommand](fiddles/bash/fiddle-0013-NlCommand)
* Added [fiddles/jquery/fiddle-0021-CanvasToDataURL](fiddles/jquery/fiddle-0021-CanvasToDataURL)

### 201506290420

* Refactored [scripts/fiddle-jquery.sh](scripts/fiddle-jquery.sh)
    * Note - Refactored based on the 201506210420 changes.  Now, it updates the tests/test.js based on the supplied fiddle name.
* Added [fiddles/extjs/fiddle-20150630-MsgBoxVariations](fiddles/extjs/fiddle-20150630-MsgBoxVariations)
* Added [fiddles/extjs/fiddle-20150702-SimplePromise](fiddles/extjs/fiddle-20150702-SimplePromise)
* Added [fiddles/extjs/fiddle-20150701-GMapRecursiveTree](fiddles/extjs/fiddle-20150701-GMapRecursiveTree)
* Added [fiddles/svg](fiddles/svg)
    * Reflected changes:
        1. added [scripts/fiddle-svg.sh](scripts/fiddle-svg.sh)
        2. added [fiddles/svg/README.markdown](fiddles/svg/README.markdown)
        3. updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        4. updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        5. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        6. updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
        7. updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor)
        8. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
* Added [fiddles/svg/fiddle-0001-Circle](fiddles/svg/fiddle-0001-Circle)
* Added [fiddles/bash/fiddle-0014-ReadCommand](fiddles/bash/fiddle-0014-ReadCommand)
* Added [fiddles/svg/fiddle-0002-Rectangle](fiddles/svg/fiddle-0002-Rectangle)
* Added [fiddles/svg/fiddle-0003-Ellipses](fiddles/svg/fiddle-0003-Ellipses)

### 201507060420

* Enhanced [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
    Note - Script now adds an entry to the CHANGELOG.markdown file.
* Added [fiddles/svg/fiddle-0006-PathLineSubCmd](fiddles/svg/fiddle-0006-PathLineSubCmd)
* Added [fiddles/svg/fiddle-0007-PathQuadCurveSubCmd](fiddles/svg/fiddle-0007-PathQuadCurveSubCmd)
* Added [fiddles/extjs/fiddle-20150706-AjaxRetryPopUp](fiddles/extjs/fiddle-20150706-AjaxRetryPopUp)
* Added [fiddles/svg/fiddle-0008-ReusablePattern](fiddles/svg/fiddle-0008-ReusablePattern)
* Added [fiddles/bash/fiddle-0015-BackgroundJobs](fiddles/bash/fiddle-0015-BackgroundJobs)
* Added [fiddles/svg/fiddle-0009-Text](fiddles/svg/fiddle-0009-Text)
* Added [fiddles/svg/fiddle-0010-DynamicShapeInjection](fiddles/svg/fiddle-0010-DynamicShapeInjection)
* Added [fiddles/extjs/fiddle-20150709-GridLayoutPersistence](fiddles/extjs/fiddle-20150709-GridLayoutPersistence)
* Added [fiddles/extjs/fiddle-20150710-DynamicColumnState](fiddles/extjs/fiddle-20150710-DynamicColumnState)
* Added [fiddles/extjs/fiddle-20150710-DynamicColumnState](fiddles/extjs/fiddle-20150710-DynamicColumnState)

### 201507110420

* Added [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
    * Note - Needed a way to list the fiddles of a given type from within the scripts directory.  This becomes useful when you want to "fork" or "refactor" an existing fiddle.
    * Reflected changes:
        1. Updated [scripts/fiddle.sh](scripts/fiddle.sh)
* Moved fiddles/extjs to [fiddles/extjs5](fiddles/extjs5)
    * Note - Response to the release of ExtJS version 6 this week.
    * Reflected changes:
        1. updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        2. updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        3. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        4. updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
        5. updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor)
        6. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        7. updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
        8. updated [fiddles/index.html](fiddles/index.html)
* Added [fiddles/extjs/6](fiddles/extjs6)
    * Note - Response to the release of ExtJS version 6 this week.
    * Reflected changes:
        1. updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        2. updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        3. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        4. updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
        5. updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor)
        6. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        7. updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
        8. updated [fiddles/index.html](fiddles/index.html)
* Added [fiddles/bash/fiddle-0016-ForLoops](fiddles/bash/fiddle-0016-ForLoops)
* Deleted all "sencha-*" scripts
    * Note - I have forgotten what these scripts do. I haven't used them and therefore, no point in maintaining.
    * Reflected changes:
        1. [scripts/README.markdown](scripts/README.markdown)

### 201507260420

* Added [fiddles/bash/fiddle-0017-InstallJoeEditor](fiddles/bash/fiddle-0017-InstallJoeEditor)
* Added [fiddles/svg/fiddle-0011-DeclarativeAnimiation](fiddles/svg/fiddle-0011-DeclarativeAnimiation)
* Added [fiddles/extjs6/fiddle-0002-Calculator](fiddles/extjs6/fiddle-0002-Calculator)
    * Note - This one is unfinished.
* Added [fiddles/svg/fiddle-0012-AnimatedTextPath](fiddles/svg/fiddle-0012-AnimatedTextPath)
* Added [fiddles/extjs6/fiddle-0003-Defect18720](fiddles/extjs6/fiddle-0003-Defect18720)
* Added [fiddles/bash/fiddle-0018-awkPrintStatements](fiddles/bash/fiddle-0018-awkPrintStatements)
* Added [fiddles/extjs6/fiddle-0004-BarChart](fiddles/extjs6/fiddle-0004-BarChart)
* Added [fiddles/extjs5/fiddle-20150721-BarChartPanZoom](fiddles/extjs5/fiddle-20150721-BarChartPanZoom)
* Added [fiddles/extjs6/fiddle-0005-LockedColumnState](fiddles/extjs6/fiddle-0005-LockedColumnState)
* Added [scripts/download-codekit.sh](download-codekit.sh)
    * Note - [CodeKit](http://incident57.com/codekit/) is web development tool intended for mac users.  If your mac is
    locked down like mine, this script can be used to download the executable using Curl.  This will allow you to open
    the zip without getting the annoying "Not from the App Store" error.
* Refactored [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
* Added [fiddles/compass](fiddles/compass)
    * Reflected changes:
        1. updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        2. updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        3. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        4. updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
        5. updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor)
        6. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        7. updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
        8. updated [fiddles/index.html](fiddles/index.html)
        9. updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
        10. added [scripts/fiddle-compass.sh](scripts/fiddle-compass.sh)
        11. added [fiddles/compass/README.markdown](fiddles/compass/README.markdown)
* Added [fiddles/svg/fiddle-0013-GradientCylinder](fiddles/svg/fiddle-0013-GradientCylinder)
* Added [fiddles/svg/fiddle-0014-TriColorGradients](fiddles/svg/fiddle-0014-TriColorGradients)
* Added [fiddles/svg/fiddle-0015-GradientWeave](fiddles/svg/fiddle-0015-GradientWeave)

### 201508010420

* Started [fiddles/jquery/fiddle-0024-AjaxJsonPYahooChartApi](fiddles/jquery/fiddle-0024-AjaxJsonPYahooChartApi)
* Added [fiddles/svg/fiddle-0016-getBBoxMethod](fiddles/svg/fiddle-0016-getBBoxMethod)
* Added [fiddles/extjs6/fiddle-0008-CandleStickChart](fiddles/extjs6/fiddle-0008-CandleStickChart)
* Added [fiddles/svg/fiddle-0017-SmilToScript](fiddles/svg/fiddle-0017-SmilToScript)
* Added [fiddles/extjs6/fiddle-0009-DjiComboChart](fiddles/extjs6/fiddle-0009-DjiComboChart)
* Added [fiddles/compass/fiddle-0002-Partials](fiddles/compass/fiddle-0002-Partials)
* Added [fiddles/compass/fiddle-0003-Mixins](fiddles/compass/fiddle-0003-Mixins)
* Added [fiddles/extjs5/fiddle-20150810-DjiComboChart](fiddles/extjs5/fiddle-20150810-DjiComboChart)
* Added [fiddles/bash/fiddle-0019-GitMergeCommand](fiddles/bash/fiddle-0019-GitMergeCommand)
* Added [fiddles/svg/fiddle-0018-DaileyClock](fiddles/svg/fiddle-0018-DaileyClock)
* Added [fiddles/svg/fiddle-0019-ClockFace](fiddles/svg/fiddle-0019-ClockFace)
* Added [fiddles/bash/fiddle-0020-GitBranchCommand](fiddles/bash/fiddle-0020-GitBranchCommand)
* Added [fiddles/jquery/fiddle-0025-ScrollableDiv](fiddles/jquery/fiddle-0025-ScrollableDiv)
* Started [fiddles/svg/fiddle-0022-Spirograph](fiddles/svg/fiddle-0022-Spirograph)
* Added [fiddles/bash/fiddle-0021-InstallPhantomJs](fiddles/bash/fiddle-0021-InstallPhantomJs)
* Added [fiddles/bash/fiddle-0022-OSVersion](fiddles/bash/fiddle-0022-OSVersion)
* Added [fiddles/jquery/fiddle-0026-ScrollableDatagrid](fiddles/jquery/fiddle-0026-ScrollableDatagrid)
* Added [fiddles/bash/fiddle-0023-GitAmendCommit](fiddles/bash/fiddle-0023-GitAmendCommit)
* Added [fiddles/extjs6/fiddle-0011-PageMapHasRange](fiddles/extjs6/fiddle-0011-PageMapHasRange)
* Added [fiddles/extjs6/fiddle-0012-DefectXXXX](fiddles/extjs6/fiddle-0012-DefectXXXX)
* Added [fiddles/bash/fiddle-0024-InstallBabel](fiddles/bash/fiddle-0024-InstallBabel)
* Added [fiddles/bash/fiddle-0025-InstallYuiCompressor](fiddles/bash/fiddle-0025-InstallYuiCompressor)

### 201508240420

* Added [fiddles/bash/fiddle-0026-BatchYuiCompressor](fiddles/bash/fiddle-0026-BatchYuiCompressor)
* Added [fiddles/bash/fiddle-0027-CombineJs](fiddles/bash/fiddle-0027-CombineJs)
* Added [fiddles/bash/fiddle-0028-CurlAndroidSDK](fiddles/bash/fiddle-0028-CurlAndroidSDK)
* Added [fiddles/bash/fiddle-0029-JarExtraction](fiddles/bash/fiddle-0029-JarExtraction)
* Added [fiddles/bash/fiddle-0030-PhantomJsScreenShot](fiddles/bash/fiddle-0030-PhantomJsScreenShot)
* Added [fiddles/extjs6/fiddle-0013-MiniGauges](fiddles/extjs6/fiddle-0013-MiniGauges)
* Added [fiddles/extjs6/fiddle-0014-WidgetGridKS](fiddles/extjs6/fiddle-0014-WidgetGridKS)
* Added [scripts/fiddle-combine.sh](scripts/fiddle-combine.sh)
  * Reflected changes:
        1. updated [scripts/fiddle.sh](scripts/fiddle.sh)
* Added [fiddles/ant](fiddles/ant)
    * Reflected changes:
        1. updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        2. updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        3. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        4. updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
        5. added [scripts/fiddle-ant.sh](scripts/fiddle-ant.sh)
        6. added [fiddles/ant/README.markdown](fiddles/ant/README.markdown)
        7. added [fiddles/ant/template](fiddles/ant/template)
* Added [fiddles/bash/fiddle-0031-AntInstalled](fiddles/bash/fiddle-0031-AntInstalled)
* Added [fiddles/ant/fiddle-0001-antEcho](fiddles/ant/fiddle-0001-antEcho)
* Added [fiddles/extjs6/template/src](fiddles/extjs6/template/src)
    * Reflected changes:
        1. updated [scripts/fiddle-extjs-6.sh](scripts/fiddle-extjs-6.sh)
        2. updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
* Added [fiddles/extjs6/fiddle-0017-AssociatedModels](fiddles/extjs6/fiddle-0017-AssociatedModels)
* Added [fiddles/bash/fiddle-0032-ListAndCount](fiddles/bash/fiddle-0032-ListAndCount)
    * Reflected changes:
        1. Updated [scripts/fiddle-combine.sh](scripts/fiddle-combine.sh)
        2. updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        3. updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        4. updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
* Added [fiddles/bash/fiddle-0033-RecursiveLineGrep](fiddles/bash/fiddle-0033-RecursiveLineGrep)
* Added [fiddles/bash/fiddle-0034-InstallTree](fiddles/bash/fiddle-0034-InstallTree)
* Added [fiddles/ant/fiddle-0002-Properties](fiddles/ant/fiddle-0002-Properties)
* Added [fiddles/ant/fiddle-0003-FileList](fiddles/ant/fiddle-0003-FileList)
* Added [fiddles/ant/fiddle-0004-SenchaCmdWebStart](fiddles/ant/fiddle-0004-SenchaCmdWebStart)
* Started [fiddles/extjs6/fiddle-0019-ReporterTearDown](fiddles/extjs6/fiddle-0019-ReporterTearDown)
* Added [fiddles/extjs6/fiddle-0020-PivotGrid](fiddles/extjs6/fiddle-0020-PivotGrid)
* Added [fiddles/extjs6/fiddle-0021-GridExcelExport](fiddles/extjs6/fiddle-0021-GridExcelExport)

### 201509220420

* Added [fiddles/extjs6/fiddle-0022-BufferedStoreExcelExport](fiddles/extjs6/fiddle-0022-BufferedStoreExcelExport)
* Added [fiddles/extjs6/fiddle-0023-ReporterSpecRunner](fiddles/extjs6/fiddle-0023-ReporterSpecRunner)
* Refactored [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
    * Based on [fiddles/bash/fiddle-0032-ListAndCount](fiddles/bash/fiddle-0032-ListAndCount)
* Added [fiddles/jquery/fiddle-0028-RecursiveDOMInjection](fiddles/jquery/fiddle-0028-RecursiveDOMInjection)
* Refactored [scripts/fiddle-combine.sh](scripts/fiddle-combine.sh)
    1. Added "preinit.js" file support for non-ext* fiddles
    2. Added "js-beautify" app.js reformatting logic
    3. Added optional 3rd input parameter for overriding the target file
        * Reflected changes:
            1. updated [scripts/fiddle.sh](scripts/fiddle.sh)
    4. Added optional 4th input parameter for disabling main closure in non-extjs fiddles
            1. updated [scripts/fiddle.sh](scripts/fiddle.sh)
    5. Added support for extjs5 fiddles
* Added [fiddles/jquery/fiddle-0029-CustomJasmineReporter](fiddles/jquery/fiddle-0029-CustomJasmineReporter)
* Added [fiddles/bash/fiddle-0035-Kdiff3](fiddles/bash/fiddle-0035-Kdiff3)
* Added [fiddles/extjs5/fiddle-20150926-PivotGrid](fiddles/extjs5/fiddle-20150926-PivotGrid)
* Enhanced [scripts/fiddle.sh](scripts/fiddle.sh)
    1. Added ASCII artwork-- showTitle function
* Added [fiddles/jquery/fiddle-0030-MixinClass](fiddles/jquery/fiddle-0030-MixinClass)
* Added [fiddles/extjs6/fiddle-0024-TreeStoreLifeCycle](fiddles/extjs6/fiddle-0024-TreeStoreLifeCycle)
* Added [fiddles/jquery/fiddle-0031-ReferenceError](fiddles/jquery/fiddle-0031-ReferenceError)
* Added [fiddles/jquery/fiddle-0032-Namespace](fiddles/jquery/fiddle-0032-Namespace)
* Added [fiddles/svg/fiddle-0019-Button](fiddles/svg/fiddle-0019-Button)

### 2015010270420

* Added [fiddles/svg/fiddle-0024-Clock](fiddles/svg/fiddle-0024-Clock)

### 2015011060420

* Added [fiddles/svg/toolkit](fiddles/svg/toolkit)
    * Based on [fiddles/svg/fiddle-0024-Clock/src/toolkit](fiddles/svg/fiddle-0024-Clock/toolkit)
    * Reflected changes:
        1. Updated [fiddles/svg/template](fiddles/svg/template)
        2. Added [fiddles/svg/toolkit/README.markdown](fiddles/svg/toolkit/README.markdown)
* Finished [fiddles/svg/fiddle-0020-ArcPath](fiddles/svg/fiddle-0020-ArcPath)
    * Reflected changes:
        1. [fiddles/svg/toolkit/Util.js](fiddles/svg/toolkit/Util.js)
            * added mapCircularPoint
            * added convertToRadians
        2. [fiddles/svg/toolkit/Util.js](fiddles/svg/toolkit/Text.js)
            * added style attribute support
* Added [scripts/setup/install-browserify.sh](scripts/setup/install-browserify.sh)
    * Reflected changes:
        1. [scripts/setup/README.markdown](scripts/setup/README.markdown)
* Added [scripts/setup/install-npm.sh](scripts/setup/install-npm.sh)
    * Reflected changes:
        1. [scripts/setup/README.markdown](scripts/setup/README.markdown)
* Added [scripts/setup/install-babel.sh](scripts/setup/install-babel.sh)
    * Reflected changes:
        1. [scripts/setup/README.markdown](scripts/setup/README.markdown)
* Added [fiddles/bash/fiddle-0036-Browserify](fiddles/bash/fiddle-0036-Browserify)
* Added [fiddles/bash/fiddle-0037-Babel](fiddles/bash/fiddle-0037-Babel)
* Enhanced [fiddles/svg/toolkit/Util.js](fiddles/svg/toolkit/Util.js)
* Added [fiddles/extjs6/fiddle-0024-SmartTreeFiltering](fiddles/extjs6/fiddle-0024-SmartTreeFiltering)
* Started [fiddles/extjs6/fiddle-0025-CustomToolButton](fiddles/extjs6/fiddle-0025-CustomToolButton)

### 201511100420

* Added [fiddles/bash/fiddle-0039-DateCommand](fiddles/bash/fiddle-0039-DateCommand)
* Finished [fiddles/bash/fiddle-0037-Babel](fiddles/bash/fiddle-0037-Babel)
* Added [fiddles/bash/fiddle-0040-SenchaAppGenerate](fiddles/bash/fiddle-0040-SenchaAppGenerate)
* Added [fiddles/bash/fiddle-0041-findDeleteCommand](fiddles/bash/fiddle-0041-findDeleteCommand)
* Added [fiddles/bash/fiddle-0042-BabelBeautify](fiddles/bash/fiddle-0042-BabelBeautify)
* Added [fiddles/extjs6/fiddle-0027-GlobalErrors](fiddles/extjs6/fiddle-0027-GlobalErrors)
* Added [fiddles/bash/fiddle-0043-InstallCordova](fiddles/bash/fiddle-0043-InstallCordova)
* Added [fiddles/bash/fiddle-0044-CordovaCreate](fiddles/bash/fiddle-0044-CordovaCreate)
* Added [fiddles/extjs6/fiddle-0027-DragAndDropKS](fiddles/extjs6/fiddle-0027-DragAndDropKS)
* Added [fiddles/extjs6/fiddle-0028-GaugeColumnWidget](fiddles/extjs6/fiddle-0028-GaugeColumnWidget)
* Added [fiddles/bash/fiddle-0045-InstallCappuccino](fiddles/bash/fiddle-0045-InstallCappuccino)
* Added [fiddles/bash/fiddle-0046-InstallEmber](fiddles/bash/fiddle-0046-InstallEmber)
* Added [fiddles/extjs6/fiddle-0029-AriaTheme](fiddles/extjs6/fiddle-0029-AriaTheme)
* Added [fiddles/bash/fiddle-0038-CsvToJson](fiddles/bash/fiddle-0038-CsvToJson)
* Enhanced [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
    1. Added logic to remove the deleted fiddle from the CHANGELOG.markdown file
* Added [fiddles/bash/fiddle-0047-InstallNativeScript](fiddles/bash/fiddle-0047-InstallNativeScript)
* Added [fiddles/bash/fiddle-0048-MountSharedDrive](fiddles/bash/fiddle-0048-MountSharedDrive)
* Added [fiddles/jquery/fiddle-0033-15Puzzle](fiddles/jquery/fiddle-0033-15Puzzle)
* Added [fiddles/jquery/fiddle-0034-RandNumSeq](fiddles/jquery/fiddle-0034-RandNumSeq)
* Added [fiddles/extjs6/fiddle-0030-CSVReporter](fiddles/extjs6/fiddle-0030-CSVReporter)
* Added [fiddles/anglular](fiddles/angular)
    * Reflected changes:
        1. Added [scripts/fiddle-angular.sh](scripts/fiddle-angular.sh)
        2. Updated [fiddles/index.html](fiddles/index.html)
        3. Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        4. Updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
        5. Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
        6. Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
        7. Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        8. Updated [scripts/fiddle-combine.sh](scripts/fiddle-combine.sh)
        9. Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
        10. Updated [fiddles/index.html](fiddles/index.html)
* Added [fiddles/nativeScript](fiddles/nativeScript)
* Added [fiddles/jquery/fiddle-0035-JqueryCSV](fiddles/jquery/fiddle-0035-JqueryCSV)
* Added [fiddles/angular/fiddle-0001-SimpleUIGrid](fiddles/angular/fiddle-0001-SimpleUIGrid)
* Started [fiddles/svg/fiddle-0025-15Puzzle](fiddles/svg/fiddle-0025-15Puzzle)
* Added [fiddles/three/fiddle-0005-EarthMoon](fiddles/three/fiddle-0005-EarthMoon)
* Added [fiddles/jquery/fiddle-0036-NavBar](fiddles/jquery/fiddle-0036-NavBar)
* Added [fiddles/nativeScript/fiddle-0001-SampleGroceries](fiddles/nativeScript/fiddle-0001-SampleGroceries)
* Started [fiddles/nativeScript/fiddle-0020-Puzz](fiddles/nativeScript/fiddle-0020-Puzz)

### 201512240420

* Added [fiddles/java/fiddle-0001-Lambda](fiddles/java/fiddle-0001-Lambda)
* Added [fiddles/java/fiddle-0002-StrategyPattern](fiddles/java/fiddle-0002-StrategyPattern)
* Added [fiddles/android](fiddles/android)
* Added [fiddles/android/fiddle-0006-OpenGLRenderer](fiddles/android/fiddle-0006-OpenGLRenderer)
* Added [fiddles/android/fiddle-0007-DroidzAttack](fiddles/android/fiddle-0007-DroidzAttack)
* Added [fiddles/android/fiddle-0008-SpriteAnimation](fiddles/android/fiddle-0008-SpriteAnimation)
* Added [fiddles/android/fiddle-0009-ParticleExplosion](fiddles/android/fiddle-0009-ParticleExplosion)
* Added [fiddles/android/fiddle-0010-BitmapFonts](fiddles/android/fiddle-0010-BitmapFonts)
* Refactored / Published [fiddles/three/fiddle-0005-EarthMoon](fiddles/three/fiddle-0005-EarthMoon)
* Added [fiddles/three/fiddle-0006-Saturn](fiddles/three/fiddle-0006-Saturn)
* Added [fiddles/three/fiddle-0007-Stars](fiddles/three/fiddle-0007-Stars)
* Added [fiddles/three/fiddle-0008-Orbit](fiddles/three/fiddle-0008-Orbit)
* Added [fiddles/three/fiddle-0009-Sun](fiddles/three/fiddle-0009-Sun)
* Added [fiddles/three/fiddle-0010-SolarSystem](fiddles/three/fiddle-0010-SolarSystem)

### 201601100420

* Added [fiddles/python](fiddles/python)
    * Reflected changes:
        1. Added [scripts/fiddle-python.sh](scripts/fiddle-python.sh)
        2. Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        3. Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
        4. Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
        5. Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
* Added dependency to [nativescript-marketplace-demo](https://github.com/NativeScript/nativescript-marketplace-demo) ~ [fiddles/nativeScript/demo/nativescript-marketplace-demo](fiddles/nativeScript/demo/nativescript-marketplace-demo)
* Added dependency to [the-art-of-command-line](https://github.com/jlevy/the-art-of-command-line) ~ [fiddles/bash/libs/the-art-of-command-line](fiddles/bash/libs/the-art-of-command-line)
* Added dependency to [angular.js](https://github.com/angular/angular.js) ~ [fiddles/angular/libs/angular.js](fiddles/angular/libs/angular.js)
* Added dependency to [programming_chrome_apps](https://github.com/MarcRochkind/programming_chrome_apps.git) ~ [fiddles/chrome/libs/programming_chrome_apps](fiddles/chrome/libs/programming_chrome_apps)
* Added dependency to [ITM463](https://github.com/bradyhouse/ITM463.git) ~ [fiddles/jquery/libs/ITM463](fiddles/jquery/libs/ITM463)
* Added dependency to [WebGLBook](https://github.com/tparisi/WebGLBook.git) ~ [fiddles/three/libs/WebGLBook](fiddles/three/libs/WebGLBook)
* Added dependency to [three.js/](https://github.com/mrdoob/three.js/) ~ [fiddles/three/libs/three.js](fiddles/three/libs/three.js)
* Added dependency to [ITM413](https://github.com/bradyhouse/ITM413.git) ~ [fiddles/python/libs/ITM413](fiddles/python/libs/ITM413)
* Added dependency to [ITM462](https://github.com/bradyhouse/ITM462.git) ~ [fiddles/php/libs/ITM462](fiddles/php/libs/ITM462)
* Added dependency to [tween.js](https://github.com/tweenjs/tween.js.git) ~ [fiddles/tween/libs/tween.js](fiddles/tween/libs/tween.js)
* Added dependency to [ITM455](https://github.com/bradyhouse/ITM455.git) ~ [fiddles/android/libs/ITM455](fiddles/android/libs/ITM455)
* Added [fiddles/extjs6/fiddle-0031-ArrayStore](fiddles/extjs6/fiddle-0031-ArrayStore)
* Continued [fiddles/nativeScript/fiddle-0020-Puzz](fiddles/nativeScript/fiddle-0020-Puzz)
* Added [fiddles/nativeScript/emulate.sh](fiddles/nativeScript/emulate.sh)
* Added [fiddles/bash/fiddle-0049-InstallTypeScript](fiddles/bash/fiddle-0049-InstallTypeScript)
* Added [fiddles/three/fiddle-0011-PlanetTween](fiddles/three/fiddle-0011-PlanetTween)
* Added [fiddles/three/fiddle-0012-BasicTween](fiddles/three/fiddle-0012-BasicTween)

### 201601190420

* Bug fix [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
    * Note - Previously, the "fiddle.sh fork chrome ..." command threw an error while attempting to update the manifest.json file.  This issue is now resolved.
* Added [fiddles/chrome/fiddle-0003-NoteApp](fiddles/chrome/fiddle-0003-NoteApp)
* Added [fiddles/chrome/fiddle-0004-NoteAppSync](fiddles/chrome/fiddle-0004-NoteAppSync)
* Added [fiddles/chrome/fiddle-0005-TextEditor](fiddles/chrome/fiddle-0005-TextEditor)
* Added [fiddles/extjs6/fiddle-0032-CSVStore](fiddles/extjs6/fiddle-0032-CSVStore)
* Added [fiddles/chrome/fiddle-0006-BookmarkSearch](fiddles/chrome/fiddle-0006-BookmarkSearch)
* Added [fiddles/bash/fiddle-0050-InstallIstanbul](fiddles/bash/fiddle-0050-InstallIstanbul)
* Added [fiddles/bash/fiddle-0051-InstallCucumber](fiddles/bash/fiddle-0051-InstallCucumber)
* Added [fiddles/bash/fiddle-0052-InstallBeautifulSoup](fiddles/bash/fiddle-0052-InstallBeautifulSoup)
* Added [fiddles/bash/fiddle-0053-PythonVirtualEnv](fiddles/bash/fiddle-0053-PythonVirtualEnv)
* Added [fiddles/python/fiddle-0001-BeautifulSoup](fiddles/python/fiddle-0001-BeautifulSoup)
* Added [fiddles/python/fiddle-0002-SoupFindAll](fiddles/python/fiddle-0002-SoupFindAll)
* Added [fiddles/python/fiddle-0003-SoupFindChildren](fiddles/python/fiddle-0003-SoupFindChildren)
* Added [fiddles/python/fiddle-0004-SoupFindRegex](fiddles/python/fiddle-0004-SoupFindRegex)
* Added [fiddles/python/fiddle-0005-HelloCrawler](fiddles/python/fiddle-0005-HelloCrawler)
* Added [fiddles/python/fiddle-0006-OreillyCrawler](fiddles/python/fiddle-0006-OreillyCrawler)

### 201602010420

* **fiddle.sh**
  1. Added [fiddles/angular2](fiddles/angular2)
        * Reflected changes:
            1.  Added [scripts/fiddle-angular2.sh](scripts/fiddle-angular2.sh)
            2.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            3.  Updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
            4.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            5.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            6.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            7.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            8.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
* **Bash**
    1.  Added [fiddles/bash/fiddle-0054-DownloadLibXml2](fiddles/bash/fiddle-0054-DownloadLibXml2)
    2.  Added [fiddles/bash/fiddle-0055-InstallScrapy](fiddles/bash/fiddle-0055-InstallScrapy)
    3.  Added [fiddles/bash/fiddle-0056-InstallLiveServer](fiddles/bash/fiddle-0056-InstallLiveServer)
* **Angular 2**
    1.  Added dependency to [systemjs](https://github.com/systemjs/systemjs)
    2.  Added dependency to [traceur-compiler](https://github.com/google/traceur-compiler.git)
    4.  Added [fiddles/angular2/fiddle-0002-PoormanReddit](fiddles/angular2/fiddle-0002-PoormanReddit)
* **ExtJS 6**
    1.  Added [fiddles/extjs6/fiddle-0033-CSVExporter](fiddles/extjs6/fiddle-0033-CSVExporter)

### 201602110420

* **fiddle.sh**
    1. Refactored [scripts/fiddle-angular-2.sh](scripts/fiddle-angular-2.sh)
        * Note - Added logic to use the fiddle name as the default component selector in the app.ts template file.
* **Angular 2**
    1.  Added [fiddles/angular2/fiddle-0003-InventoryApp](fiddles/angular2/fiddle-0003-InventoryApp)
    2.  Added [fiddles/angular2/fiddle-0004-OutputBinding](fiddles/angular2/fiddle-0004-OutputBinding)
    3.  Added [fiddles/angular2/fiddle-0005-NgIf](fiddles/angular2/fiddle-0005-NgIf)
    4.  Added [fiddles/angular2/fiddle-0006-NgStyle](fiddles/angular2/fiddle-0006-NgStyle)
    5.  Added [fiddles/angular2/fiddle-0007-NgSwitch](fiddles/angular2/fiddle-0007-NgSwitch)
    6.  Added [fiddles/angular2/fiddle-0008-NgClass](fiddles/angular2/fiddle-0008-NgClass)
    7.  Added [fiddles/angular2/fiddle-0009-NgFor](fiddles/angular2/fiddle-0009-NgFor)
    8.  Added [fiddles/angular2/fiddle-0011-NgNonBindable](fiddles/angular2/fiddle-0011-NgNonBindable)
    9.  Added [fiddles/angular2/fiddle-0012-FormBuilder](fiddles/angular2/fiddle-0012-FormBuilder)
    10. Added [fiddles/angular2/fiddle-0013-FormValidator](fiddles/angular2/fiddle-0013-FormValidator)
* **ExtJS 6**
    1. Added [fiddles/extjs6/fiddle-0034-CSVExcelStyleGrid](fiddles/extjs6/fiddle-0034-CSVExcelStyleGrid)
* **Bash**
    1. Added [fiddles/bash/fiddle-0057-PhantomJsRasterize](fiddles/bash/fiddle-0057-PhantomJsRasterize)

### 201602130420

* **fiddle.sh**
    1.  Enhanced [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
        * Note - added logic to use npm live-server.
    2.  Enhanced [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        * Note - added python support.
    3.  Enhanced [scripts/fiddle-three.sh](scripts/fiddle-three.sh)
        * Note - added logic to update the src/metadata.js based on the fiddle name.
    4.  Enhanced [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        * Note - added logic to invoke fiddle-combine.sh for three type fiddles.
    5.  Enhanced [scripts/fiddle-combine.sh](scripts/fiddle-combine.sh)
        * Note - added logic to invoke the typescript compiler, "tsc", for angular2 fiddles.
* **python**
    1.  Added [fiddles/python/fiddle-0007-ScrapyTutorial](fiddles/python/fiddle-0007-ScrapyTutorial)
    2.  Added [fiddles/python/fiddle-0008-WikipediaScrapy](fiddles/python/fiddle-0008-WikipediaScrapy)
* **bash**
    1.  Added [fiddles/bash/fiddle-0058-InstallJsBeautify](fiddles/bash/fiddle-0058-InstallJsBeautify)
    2.  Added [fiddles/bash/fiddle-0059-NpmDisableStrictSSL](fiddles/bash/fiddle-0059-NpmDisableStrictSSL)
    3.  Added [fiddles/bash/fiddle-0060-NodeVersionManagement](fiddles/bash/fiddle-0060-NodeVersionManagement)
    4.  Added [fiddles/bash/fiddle-0061-InstallNpmCheckUpdates](fiddles/bash/fiddle-0061-InstallNpmCheckUpdates)
* **ExtJS 6**
    * Added [fiddles/extjs6/fiddle-0035-SimpleGrid](fiddles/extjs6/fiddle-0035-SimpleGrid)
* **Three**
    * Started [fiddles/three/fiddle-0013-ParticleExplosion](fiddles/three/fiddle-0013-ParticleExplosion)
* **Angular**
    1.  Added [fiddles/angular/fiddle-0002-ResizeableAgGrid](fiddles/angular/fiddle-0002-ResizeableAgGrid)
    2.  Added dependency [angular-resizeable](https://github.com/Reklino/angular-resizable)
        * [fiddles/angular/lib/angular-resizeable](fiddles/angular/lib/angular-resizeable)
    3.  Added dependency [angular-phonecat](https://github.com/angular/angular-phonecat)
        * [fiddles/angular/lib/angular-phonecat](fiddles/angular/lib/angular-phonecat)
    4.  Added [fiddles/angular/fiddle-0003-PhoneCatIntro](fiddles/angular/fiddle-0003-PhoneCatIntro)
    5.  Added [fiddles/angular/fiddle-0004-PhoneCatStep0](fiddles/angular/fiddle-0004-PhoneCatStep0)
    6.  Added [fiddles/angular/fiddle-0005-PhoneCatStep1](fiddles/angular/fiddle-0005-PhoneCatStep1)
    7.  Added [fiddles/angular/fiddle-0006-PhoneCatStep2](fiddles/angular/fiddle-0006-PhoneCatStep2)
    8.  Added [fiddles/angular/fiddle-0007-FullTextSearch](fiddles/angular/fiddle-0007-FullTextSearch)
    9.  Added [fiddles/angular/fiddle-0008-2WayDatabinding](fiddles/angular/fiddle-0008-2WayDatabinding)
    10. Added [fiddles/angular/fiddle-0009-PhoneCatStep5](fiddles/angular/fiddle-0009-PhoneCatStep5)
    11. Added [fiddles/angular/fiddle-0010-PhoneCatStep6](fiddles/angular/fiddle-0010-PhoneCatStep6)
    12. Added [fiddles/angular/fiddle-0011-PhoneCatStep7](fiddles/angular/fiddle-0011-PhoneCatStep7)
    13. Added [fiddles/angular/fiddle-0012-PhoneCatStep8](fiddles/angular/fiddle-0012-PhoneCatStep8)
    14. Added [fiddles/angular/fiddle-0013-PhoneCatStep9](fiddles/angular/fiddle-0013-PhoneCatStep9)
    15. Added [fiddles/angular/fiddle-0014-PhoneCatStep10](fiddles/angular/fiddle-0014-PhoneCatStep10)
    16. Added [fiddles/angular/fiddle-0015-PhoneCatStep11](fiddles/angular/fiddle-0015-PhoneCatStep11)
    17. Added [fiddles/angular/fiddle-0016-PhoneCatStep12](fiddles/angular/fiddle-0016-PhoneCatStep12)
    18. Added [fiddles/angular/fiddle-0018-CustomTransclusion](fiddles/angular/fiddle-0018-CustomTransclusion)
* **Angular 2**
    1.  Added [fiddles/angular2/fiddle-0014-CustomFormValidation](fiddles/angular2/fiddle-0014-CustomFormValidation)
    2.  Added [fiddles/angular2/fiddle-0015-NgModel](fiddles/angular2/fiddle-0015-NgModel)
    3.  Started [fiddles/angular2/fiddle-0016-PseudoChatApp](fiddles/angular2/fiddle-0016-PseudoChatApp)
    4.  Added [fiddles/angular2/fiddle-0017-AjaxGetRequest](fiddles/angular2/fiddle-0017-AjaxGetRequest)
    5.  Added [fiddles/angular2/fiddle-0018-AgGrid](fiddles/angular2/fiddle-0018-AgGrid)
    6.  Added [fiddles/angular2/fiddle-0019-ZingChart](fiddles/angular2/fiddle-0019-ZingChart)
    9.  Added [fiddles/angular2/fiddle-0022-MicroApp](fiddles/angular2/fiddle-0022-MicroApp)
    10. Added [fiddles/angular2/fiddle-0023-SelectList](fiddles/angular2/fiddle-0023-SelectList)
    11. Added [fiddles/angular2/fiddle-0024-Dashboard](fiddles/angular2/fiddle-0024-Dashboard)
    12. Added [fiddles/angular2/fiddle-0025-TreeComponent](fiddles/angular2/fiddle-0025-TreeComponent)
* **jQuery**
    1.  Added [fiddles/jquery/fiddle-0037-ShadowDom](fiddles/jquery/fiddle-0037-ShadowDom)

### 201603020420

* **fiddle.sh**
    1.  Added [fiddles/d3](fiddles/d3)
        * Reflected changes:
            1.  Added [scripts/fiddle-d3.sh](scripts/fiddle-d3.sh)
            2.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            3.  Updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
            4.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            5.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            6.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            7.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            8.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
* **d3**
    1.  Added dependency to [d3-cookbook](https://github.com/NickQiZhu/d3-cookbook)
        *   [fiddles/d3/libs/d3-cookbook](fiddles/d3/libs/d3-cookbook)
    2.  Added dependency (submodule) to [d3](https://github.com/mbostock/d3)
        *   [fiddles/d3/libs/d3]([fiddles/d3/libs/d3)
    3.  Added dependency (submodule) to [sizzlejs](https://github.com/jquery/sizzle/tree/master)
        *   [fiddles/d3/libs/sizzle](fiddles/d3/libs/sizzle)
    4.  Added [fiddles/d3/fiddle-0001-SelectAppend](fiddles/d3/fiddle-0001-SelectAppend)
    5.  Added [fiddles/d3/fiddle-0002-SingleSelection](fiddles/d3/fiddle-0002-SingleSelection)
    6.  Added [fiddles/d3/fiddle-0003-MultipleSelect](fiddles/d3/fiddle-0003-MultipleSelect)
    7.  Added [fiddles/d3/fiddle-0004-SelectionIteration](fiddles/d3/fiddle-0004-SelectionIteration)
    8.  Added [fiddles/d3/fiddle-0005-SubSelection](fiddles/d3/fiddle-0005-SubSelection)
    9.  Added [fiddles/d3/fiddle-0006-FunctionChain](fiddles/d3/fiddle-0006-FunctionChain)
    10. Added [fiddles/d3/fiddle-0007-EnterUpdateExit](fiddles/d3/fiddle-0007-EnterUpdateExit)
    11. Added [fiddles/d3/fiddle-0008-ObjectBinding](fiddles/d3/fiddle-0008-ObjectBinding)
    12. Added dependency (submodule) to [nvd3](https://github.com/novus/nvd3)
        * [fiddles/d3/libs/nvd3](fiddles/d3/libs/nvd3)
* **Bash**
    *   Added [fiddles/bash/fiddle-0062-PsuedoDatabase](fiddles/bash/fiddle-0062-PsuedoDatabase)
* **Angular2**
    *   Added [fiddles/angular2/fiddle-0026-Nvd3Component](fiddles/angular2/fiddle-0026-Nvd3Component)

### 201603050420

* **Angular2**
    1.  Added dependency (submodule) to [angular2-rxjs-observable-data-services](https://github.com/jhades/angular2-rxjs-observable-data-services.git)
        *   [fiddles/angular2/libs/angular2-rxjs-observable-data-services](fiddles/angular2/libs/angular2-rxjs-observable-data-services)
    2.  Added [fiddles/angular2/fiddle-0028-CgmPanel](fiddles/angular2/fiddle-0028-CgmPanel)
* **Bash**
    1.  Added [fiddles/bash/fiddle-0063-InstallTsun](fiddles/bash/fiddle-0063-InstallTsun)
    2.  Added [fiddles/bash/fiddle-0064-InstallTypings](fiddles/bash/fiddle-0064-InstallTypings)
    3.  Added [fiddles/bash/fiddle-0065-InstallAtom](fiddles/bash/fiddle-0065-InstallAtom)
    4.  Added [fiddles/bash/fiddle-0066-TypeScriptProjectSetup](fiddles/bash/fiddle-0066-TypeScriptProjectSetup)
    5.  Added [fiddles/bash/fiddle-0067-YoTypescriptGenerator](fiddles/bash/fiddle-0067-YoTypescriptGenerator)
    6.  Added [fiddles/bash/fiddle-0068-YoSassTypescriptGenerator](fiddles/bash/fiddle-0068-YoSassTypescriptGenerator)
* **D3**
    1.  Added [fiddles/d3/fiddle-0009-QuantitativeScales](fiddles/d3/fiddle-0009-QuantitativeScales)
    2.  Added [fiddles/d3/fiddle-0010-TimeScale](fiddles/d3/fiddle-0010-TimeScale)
    3.  Added [fiddles/d3/fiddle-0011-OrdinalScale](fiddles/d3/fiddle-0011-OrdinalScale)
    4.  Added [fiddles/d3/fiddle-0012-StringInterpolation](fiddles/d3/fiddle-0012-StringInterpolation)
    5.  Added [fiddles/d3/fiddle-0013-ColorInterpolation](fiddles/d3/fiddle-0013-ColorInterpolation)
    6.  Added [fiddles/d3/fiddle-0014-CompoundInterpolation](fiddles/d3/fiddle-0014-CompoundInterpolation)
* **fiddle.sh**
    1.  Refactored [scripts/fiddle-angular-2.sh](scripts/fiddle-angular-2.sh)
        *   Note - Modified to use new node based template directory
    2.  Added [scripts/_fiddle-func.sh](scripts/_fiddle-func.sh)
        *   Note - This script is meant to share functions across the fiddle-* collection of scripts.
        *   Reflected changes:
            1.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            2.  Updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
            3.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            4.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            5.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            6.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            7.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
    2.  Added [fiddles/rxjs](fiddles/rxjs)
            *   Reflected changes:
                1.  Added [scripts/fiddle-rxjs.sh](scripts/fiddle-rxjs.sh)
                2.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
                3.  Updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
                4.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
                5.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
                6.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
                7.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
                8.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
    3.  Added [fiddles/typescript](fiddles/typescript)
            *   Reflected changes:
                1.  Added [scripts/fiddle-typescript.sh](scripts/fiddle-typescript.sh)
                    *   Note - Adapted from the [scripts/fiddle-node.sh](scripts/fiddle-node.sh)
                2.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
                4.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
                5.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
                6.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
                7.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
                8.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
* **RxJS**
    1.  Added [fiddles/rxjs/fiddle-0001-AjaxObservable](fiddles/rxjs/fiddle-0001-AjaxObservable)

### 201603220420

* **Bash**
    1.  Added [fiddles/bash/fiddle-0069-NodeProjectSetup](fiddles/bash/fiddle-0069-NodeProjectSetup)
    2.  Added [fiddles/bash/fiddle-0070-GitSubModuleInitUpdate](fiddles/bash/fiddle-0070-GitSubModuleInitUpdate)
    3.  Added [fiddles/bash/fiddle-0071-TypescriptD3ProjectSetup](fiddles/bash/fiddle-0071-TypescriptD3ProjectSetup)
* **D3**
    1.  Added [fiddles/d3/fiddle-0015-BasicAxes](fiddles/d3/fiddle-0015-BasicAxes)
    2.  Added [fiddles/d3/fiddle-0017-ClickEventListener](fiddles/d3/fiddle-0017-ClickEventListener)
    3.  Added [fiddles/d3/fiddle-0018-DragEventListener](fiddles/d3/fiddle-0018-DragEventListener)
    4.  Added [fiddles/d3/fiddle-0019-BarChartGradient](fiddles/d3/fiddle-0019-BarChartGradient)
    5.  Added [fiddles/d3/fiddle-0020-CustomAxisTick](fiddles/d3/fiddle-0020-CustomAxisTick)
    6.  Added [fiddles/d3/fiddle-0021-GridLines](fiddles/d3/fiddle-0021-GridLines)
    7.  Added [fiddles/d3/fiddle-0022-Rescaling](fiddles/d3/fiddle-0022-Rescaling)
* **Angular 2**
    1.  Started [fiddles/angular2/fiddle-0030-D3VerticalBarChart](fiddles/angular2/fiddle-0030-D3VerticalBarChart)

### 201603260420

* **D3**
    1.  Added [fiddles/d3/fiddle-0023-ElementTransition](fiddles/d3/fiddle-0023-ElementTransition)
    2.  Added [fiddles/d3/fiddle-0024-BarChart](fiddles/d3/fiddle-0024-BarChart)
    3.  Added [fiddles/d3/fiddle-0025-TwoQuadrantBarChart](fiddles/d3/fiddle-0025-TwoQuadrantBarChart)
    4.  Added [fiddles/d3/fiddle-0027-Level3Events](fiddles/d3/fiddle-0027-Level3Events)
    5.  Added [fiddles/d3/fiddle-0028-BarChartTooltips](fiddles/d3/fiddle-0028-BarChartTooltips)
* **Angular2**
    1.  Added [fiddles/angular2/fiddle-0031-PlayerToolbar](fiddles/angular2/fiddle-0031-PlayerToolbar)
    2.  Finished [fiddles/angular2/fiddle-0030-D3VerticalBarChart](fiddles/angular2/fiddle-0030-D3VerticalBarChart)
    3.  Added [fiddles/angular2/fiddle-0032-D3BarChartTooltip](fiddles/angular2/fiddle-0032-D3BarChartTooltip)
    4.  Added dependency (submodule) to [angular2-canvas-renderer-experiment](https://github.com/matsko/angular2-canvas-renderer-experiment)
* **Rx**
    1.  Refactored [fiddles/rxjs/fiddle-0001-AjaxObservable](fiddles/rxjs/fiddle-0001-AjaxObservable)
    2.  Added [fiddles/rxjs/fiddle-0002-TimeObservable](fiddles/rxjs/fiddle-0002-TimeObservable)
    3.  Started [fiddles/rxjs/fiddle-0003-Disposable](fiddles/rxjs/fiddle-0003-Disposable)
* **Node**
    1.  Started [fiddles/node/fiddle-0002-FileWatcher](fiddles/node/fiddle-0002-FileWatcher)
* **Bash**
    1.  Added [fiddles/bash/fiddle-0073-CsvToJson](fiddles/bash/fiddle-0073-CsvToJson)

### 201604160420

* **fiddle.sh**
    1.  Removed [scripts/bin/house-*.sh](scripts/bin)
    2.  Removed [scripts/mysql-*.sh](scripts)
    3.  Removed [scripts/setup](scripts)
    4.  Added [scripts/bin/_*](scripts/bin)
        *   See - [fiddles/bash/fiddle-0071-TypescriptD3ProjectSetup](fiddles/bash/fiddle-0071-TypescriptD3ProjectSetup)
        *   Reflected changes
            1. Updated [scripts/fiddle-typescript.sh](scripts/fiddle-typescript.sh)
    5.  Removed [scripts/_fiddle_func.sh](scripts)
        *   Reflected changes:
            1.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            2.  Updated [scripts/fiddle-index.sh](scripts/fiddle-index.sh)
            3.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            4.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            5.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            6.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            7.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
            8.  Updated [scripts/fiddle-stop.sh](scripts/fiddle-stop.sh)
            9.  Updated [scripts/fiddle-test.sh](scripts/fiddle-test.sh)
            10. Updated [scripts/fiddle-combine.sh](scripts/fiddle-combine.sh)
            12. Updated [scripts/fiddle-angular-2.sh](scripts/fiddle-angular-2.sh)
            13. Updated [scripts/fiddle-angular.sh](scripts/fiddle-angular.sh)
            14. Updated [scripts/fiddle-ant.sh](scripts/fiddle-ant.sh)
            15. Updated [scripts/fiddle-bash.sh](scripts/fiddle-bash.sh)
            16. Updated [scripts/fiddle-chrome.sh](scripts/fiddle-chrome.sh)
            17. Updated [scripts/fiddle-compass.sh](scripts/fiddle-compass.sh)
            18. Updated [scripts/fiddle-d3.sh](scripts/fiddle-d3.sh)
            19. Updated [scripts/fiddle-dojo.sh](scripts/fiddle-dojo.sh)
            20. Updated [scripts/fiddle-extjs-5.sh](scripts/fiddle-extjs-5.sh)
            21. Updated [scripts/fiddle-extjs-6.sh](scripts/fiddle-extjs-6.sh)
            22. Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            23. Updated [scripts/fiddle-jquery.sh](scripts/fiddle-jquery.sh)
            24. Updated [scripts/fiddle-node.sh](scripts/fiddle-node.sh)
            25. Updated [scripts/fiddle-php.sh](scripts/fiddle-php.sh)
            26. Updated [scripts/fiddle-python.sh](scripts/fiddle-python.sh)
            27. Updated [scripts/fiddle-rxjs.sh](scripts/fiddle-rxjs.sh)
            28. Updated [scripts/fiddle-svg.sh](scripts/fiddle-svg.sh)
            29. Updated [scripts/fiddle-three.sh](scripts/fiddle-three.sh)
            30. Updated [scripts/fiddle-tween.sh](scripts/fiddle-tween.sh)
            31. Updated [scripts/fiddle-typescript.sh](scripts/fiddle-typescript.sh)
    6.  Added [scripts/test](scripts/test)
        * Reflected changes:
            1. Added [scripts/test/fiddle.sh](scripts/test/fiddle.sh)
            2. Added [scripts/test/bin/utils.sh](scripts/test/bin/utils.sh)

* **Typescript**
    1.  Started [fiddles/typescript/fiddle-0002-GenericService](fiddles/typescript/fiddle-0002-GenericService)

* **Bash**
    1.  Started [fiddles/bash/fiddle-0074-Angular2ProjectSetup](fiddles/bash/fiddle-0074-Angular2ProjectSetup)

* **Angular2**
    1.  Added [fiddles/angular2/fiddle-0032-D3VerticalBarChartJs](fiddles/angular2/fiddle-0032-D3VerticalBarChartJs)
    2.  Added [fiddles/angular2/fiddle-0033-Tooltip](fiddles/angular2/fiddle-0033-Tooltip)
    3.  Added [fiddles/angular2/fiddle-0034-TooltipJs](fiddles/angular2/fiddle-0034-TooltipJs)

### 201605020420

* **fiddle.sh**
    1.  Added [scripts/bin/angular2](scripts/bin/angular2)
        *   See - [fiddles/bash/fiddle-0076-Angular2CLI](fiddles/bash/fiddle-0076-Angular2CLI)
        *   Reflected changes:
            1.  Updated [scripts/fiddle-angular-2.sh](scripts/fiddle-angular-2.sh)
            2.  Updated [scripts/fiddle-start.sh]
    2.  Added [scripts/bin/_test_fiddle_shell.sh](scripts/bin/_test_fiddle_shell.sh)
        *   Reflected changes:
            1.  Updated [scripts/fiddle.sh](scripts/fiddle.sh)
            2.  Updated [scripts/fiddle-test.sh](scripts/fiddle-test.sh)
    3.  Added [scripts/bin/_run_jstestdriver.sh](scripts/bin/_run_jstestdriver.sh)
        *   Reflected changes:
            1.  Updated [scripts/fiddle-test.sh](scripts/fiddle-test.sh)
    4.  Deleted [scripts/fiddle-stop.sh](scripts)
    5.  Added [fiddles/meteor](fiddles/meteor)
         *  See [fiddles/bash/fiddle-0077-Meteor](fiddles/bash/fiddle-0077-Meteor)
         *  Reflected changes:
            1.  Added [scripts/bin/meteor](scripts/bin/meteor)
            2.  Added [scripts/fiddle-meteor.sh](scripts/fiddle-meteor.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)

* **Bash**
    1.  Added [fiddles/bash/fiddle-0075-Angular2SeederSetup](fiddles/bash/fiddle-0075-Angular2SeederSetup)
    2.  Added [fiddles/bash/fiddle-0076-Angular2CLI](fiddles/bash/fiddle-0076-Angular2CLI)
    3.  Added [fiddles/bash/fiddle-0077-Meteor](fiddles/bash/fiddle-0077-Meteor)

* **Angular2**
    1.  Added [fiddles/angular2/fiddle-0035-ModalForm](fiddles/angular2/fiddle-0035-ModalForm)
    2.  Added [fiddles/angular2/fiddle-0036-SiblingComponents](fiddles/angular2/fiddle-0036-SiblingComponents)
    3.  Added [fiddles/angular2/fiddle-0037-ModalPopUp](fiddles/angular2/fiddle-0037-ModalPopUp)
    4.  Added [fiddles/angular2/fiddle-0038-ComponentResolver](fiddles/angular2/fiddle-0038-ComponentResolver)
    5.  Added dependency (submodule) to [Farata / angular2typescript](https://github.com/Farata/angular2typescript)
    6.  Added dependency (submodule) to [angular-cli](https://github.com/angular/angular-cli)

* **SVG**
    1.  Started (~ restored) [fiddles/svg/fiddle-0022-Spirograph](fiddles/svg/fiddle-0022-Spirograph)
    2.  Started (~ restored) [fiddles/svg/fiddle-0023-Menubar](fiddles/svg/fiddle-0023-Menubar)

* **Meteor**
    1.  Added [fiddles/meteor/fiddle-0001-TaskManager](fiddles/meteor/fiddle-0001-TaskManager)
    2.  Added dependency (submodule) to [meteor-workshop-solution](https://github.com/pavlovich/meteor-workshop-solution)


### 201605180420

* **fiddle.sh**
   1.   Added [fiddles/ember](fiddles/ember)
        *   See [bash fiddle #80](fiddles/bash/fiddle-0080-Ember)
        *   Reflected changes:
            1.  Added [scripts/bin/ember](scripts/bin/ember)
            2.  Added [scripts/fiddle-ember.sh](scripts/fiddle-ember.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
   2.   Added [fiddles/aurelia](fiddles/ember)
        *   See [bash fiddle #79](fiddles/bash/fiddle-0079-Aurelia)
        *   Reflected changes:
            1.  Added [scripts/bin/aurelia](scripts/bin/aurelia)
            2.  Added [scripts/fiddle-ember.sh](scripts/fiddle-aurelia.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
   3.   Added [fiddles/docker](fiddles/docker)
        *   See [bash fiddle #81](fiddles/bash/fiddle-0081-Docker)
        *   Reflected changes:
            1.  Added [scripts/bin/docker](scripts/bin/docker)
            2.  Added [scripts/fiddle-docker.sh](scripts/fiddle-docker.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
   4.   Added [fiddles/nativescript](fiddles/nativescript)
        *   See [bash fiddle #84](fiddles/bash/fiddle-0084-NativeScript)
        *   Reflected changes:
            1.  Added [scripts/bin/nativescript](scripts/bin/nativescript)
            2.  Added [scripts/fiddle-nativescript.sh](scripts/fiddle-docker.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
   5.  Added [fiddles/angular2-cli](fiddles/angular2-cli)
        *   See [bash fiddle #76](fiddles/bash/fiddle-0076-Angular2CLI)
        *   Reflected changes:
            1.  Added [scripts/bin/angular2-cli](scripts/bin/angular2-cli)
            2.  Added [scripts/fiddle-angular2-cli.sh](scripts/fiddle-angular2-cli.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
   6.  Added [fiddles/angular2-seeder](fiddles/angular2-seeder)
        *   See [bash fiddle #75](fiddles/bash/fiddle-0075-Angular2SeederSetup)
        *   Reflected changes:
            1.  Added [scripts/bin/angular2-seeder](scripts/bin/angular2-seeder)
            2.  Added [scripts/fiddle-angular2-seeder.sh](scripts/fiddle-angular2-seeder.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
   7.  Added [fiddles/electron](fiddles/electron)
        *   See [bash fiddle #86](fiddles/bash/fiddle-0086-Electron)
        *   Reflected changes:
            1.  Added [scripts/bin/electron](scripts/bin/electron)
            2.  Added [scripts/fiddle-electron.sh](scripts/fiddle-electron.sh)
            3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
            4.  Updated [scripts/bin/_types.sh](scripts/bin/_utils.sh)
            5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
            6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
            7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
            8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
            9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)

* **Bash**
    1.  Added [fiddles/bash/fiddle-0079-Aurelia](fiddles/bash/fiddle-0079-Aurelia)
    2.  Added [fiddles/bash/fiddle-0080-Ember](fiddles/bash/fiddle-0080-Ember)
    3.  Added [fiddles/bash/fiddle-0081-Docker](fiddles/bash/fiddle-0081-Docker)
    4.  Added [fiddles/bash/fiddle-0082-GrantAdmin](fiddles/bash/fiddle-0082-GrantAdmin)
    5.  Added dependency (submodule) to [Homebrew](https://github.com/Homebrew/brew)
    6.  Added [fiddles/bash/fiddle-0084-NativeScript](fiddles/bash/fiddle-0084-NativeScript)
    7.  Added [fiddles/bash/fiddle-0083-Nvm](fiddles/bash/fiddle-0083-Nvm)
    8.  Started [fiddles/bash/fiddle-0085-ShellDb](fiddles/bash/fiddle-0085-ShellDb)
    9.  Added [fiddles/bash/fiddle-0086-Electron](fiddles/bash/fiddle-0086-Electron)

* **Docker**
    1.  Added [fiddles/docker/fiddle-0100-EmptyTemplate](fiddles/docker/fiddle-0100-EmptyTemplate)
    2.  Added dependency (submodule) to [docker machine](https://github.com/docker/machine)
    3.  Added [fiddles/docker/fiddle-0001-MachineCreate](fiddles/docker/fiddle-0001-MachineCreate)
    4.  Added dependency (submodule) to [docker-node-hello](https://github.com/spkane/docker-node-hello)
    5.  Added [fiddles/docker/fiddle-0002-DockerNodeHello](fiddles/docker/fiddle-0002-DockerNodeHello)

* **Ember**
    1.  Added [fiddles/ember/fiddle-0001-SuperRental](fiddles/ember/fiddle-0001-SuperRental)
    2.  Added [fiddles/ember/fiddle-0100-EmptyTemplate](fiddles/ember/fiddle-0100-EmptyTemplate)


* **NativeScript**
    1.  Added dependency (submodule) to [Angular2 Seed Advanced](https://github.com/NathanWalker/angular2-seed-advanced)
    2.  Added [fiddles/nativeScript/fiddle-0100-EmptyTemplate](fiddles/nativeScript/fiddle-0100-EmptyTemplate)

* **Angular**
    1.  Added [fiddles/angular/fiddle-0100-EmptyTemplate](fiddles/angular/fiddle-0100-EmptyTemplate)

* **Angular2**
    1.  Added [fiddles/angular2/fiddle-0100-EmptyTemplate](fiddles/angular2/fiddle-0100-EmptyTemplate)
    3.  Added [fiddles/angular2/fiddle-0036-ModalOverlay](fiddles/angular2/fiddle-0036-ModalOverlay)
    4.  Added [fiddles/angular2/fiddle-0037-ModalPopUp](fiddles/angular2/fiddle-0037-ModalPopUp)

* **Angular2 CLI**

* **Angular2 Seeder**
    1.  Added [fiddles/angular2-seeder/fiddle-0100-EmptyTemplate](fiddles/angular2-seeder/fiddle-0100-EmptyTemplate)

* **Electron**
    1.  Added [fiddles/electron/fiddle-0100-EmptyTemplate](fiddles/electron/fiddle-0100-EmptyTemplate)

* **Aurelia**

* **D3**
    1.  Added [fiddles/d3/fiddle-0100-EmptyTemplate](fiddles/d3/fiddle-0100-EmptyTemplate)

* **Meteor**
    1.  Added [fiddles/meteor/fiddle-0100-EmptyTemplate](fiddles/meteor/fiddle-0100-EmptyTemplate)


### 201605290420

* **Bash**
    1.  Added [fiddles/bash/fiddle-0087-OpenShift](fiddles/bash/fiddle-0087-OpenShift) ~ [Issue #3](https://github.com/bradyhouse/house/issues/3)
    2.  Added [fiddles/bash/fiddle-0088-GcUtil](fiddles/bash/fiddle-0088-GcUtil)
    3.  Revisited [fiddles/bash/fiddle-0079-Aurelia](fiddles/bash/fiddle-0079-Aurelia)
    4.  Added [fiddles/bash/fiddle-0089-NodeWebKit](fiddles/bash/fiddle-0089-NodeWebKit) ~ [Issue #9](https://github.com/bradyhouse/house/issues/9)
    5.  Added [fiddles/bash/fiddle-0090-Zmq](fiddles/bash/fiddle-0090-Zmq) ~ [Issue 19](https://github.com/bradyhouse/house/issues/19)

* **Aurelia**
    1.  Added [fiddles/aurelia/fiddle-0100-EmptyTemplate](fiddles/aurelia/fiddle-0100-EmptyTemplate)
    2.  Started [fiddles/aurelia/fiddle-0037-ModalPopUp](fiddles/aurelia/fiddle-0037-ModalPopUp)
    3.  Started [fiddles/aurelia/fiddle-0001-Component](fiddles/aurelia/fiddle-0001-Component)
    4.  Added dependency (submodule) to [Patrick Walter's Aurelia Examples](https://github.com/PWKad/aurelia-samples)
    5.  Added dependency (submodule) to [Marcel Hoyer's ToDoMVC App](https://github.com/mhoyer/todomvc-aurelia)
    6.  Added dependency (submodule) to [Jeremy Danyow's Northwind Breeze Example](https://github.com/jdanyow/aurelia-breeze-northwind)
    7.  Added [fiddles/aurelia/fiddle-0002-DependencyInjection](fiddles/aurelia/fiddle-0002-DependencyInjection) ~ [Issue #10](https://github.com/bradyhouse/house/issues/10)
    8.  Added [fiddles/aurelia/fiddle-0003-ObjectLifeTime](fiddles/aurelia/fiddle-0003-ObjectLifeTime) ~ [Issue 23](https://github.com/bradyhouse/house/issues/23)
    9.  Started [fiddles/aurelia/fiddle-0004-HTTPServices](fiddles/aurelia/fiddle-0004-HTTPServices) ~ [Issue #28](https://github.com/bradyhouse/house/issues/28)

* **Angular2**
    1.  Started [fiddles/angular2/fiddle-0038-DragAndDrop](fiddles/angular2/fiddle-0038-DragAndDrop) ~ [Issue #11](https://github.com/bradyhouse/house/issues/11)
    2.  Added [fiddles/angular2/fiddle-0039-ResponsiveModalPopUp](fiddles/angular2/fiddle-0039-ResponsiveModalPopUp) ~ [Issue 29](https://github.com/bradyhouse/house/issues/29)
    3.  Added [fiddles/angular2/fiddle-0040-CSVReporter](fiddles/angular2/fiddle-0040-CSVReporter) ~ [Issue 30](https://github.com/bradyhouse/house/issues/30)
    4.  Added [fiddles/angular2/fiddle-0041-JqueryCSV](fiddles/angular2/fiddle-0041-JqueryCSV) ~ [Issue 31](https://github.com/bradyhouse/house/issues/31)
    5.  Added [fiddles/angular2/fiddle-0042-DeepLinks](fiddles/angular2/fiddle-0042-DeepLinks) ~ [Issue 42](https://github.com/bradyhouse/house/issues/42)
    6.  Added [fiddles/angular2/fiddle-0043-ComponentRouting](fiddles/angular2/fiddle-0043-ComponentRouting) ~ [Issue 43](https://github.com/bradyhouse/house/issues/43)

* **Angular2 CLI**
    1.  Added [fiddles/angular2-cli/fiddle-0001-GenerateRoute](fiddles/angular2-cli/fiddle-0001-GenerateRoute) ~ [Issue 22](https://github.com/bradyhouse/house/issues/22)
    2.  Added [fiddles/angular2-cli/fiddle-0002-GeneratePipe](fiddles/angular2-cli/fiddle-0002-GeneratePipe) ~ [Issue 27](https://github.com/bradyhouse/house/issues/27)

* **Node**
    1.  Added [fiddles/node/fiddle-0003-ChildProcess](fiddles/node/fiddle-0003-ChildProcess) ~ [Issue 12](https://github.com/bradyhouse/house/issues/12)
    2.  Added [fiddles/node/fiddle-0004-EventEmitter](fiddles/node/fiddle-0004-EventEmitter) ~ [Issue 13](https://github.com/bradyhouse/house/issues/13)
    3.  Added [fiddles/node/fiddle-0005-ReadStream](fiddles/node/fiddle-0005-ReadStream) ~ [Issue 14](https://github.com/bradyhouse/house/issues/14)
    4.  Added [fiddles/node/fiddle-0006-NetWatcher](fiddles/node/fiddle-0006-NetWatcher) ~ [Issue 15](https://github.com/bradyhouse/house/issues/15)
    5.  Added [fiddles/node/fiddle-0007-SocketWatcher](fiddles/node/fiddle-0007-SocketWatcher) ~ [Issue 16](https://github.com/bradyhouse/house/issues/16)
    6.  Added [fiddles/node/fiddle-0008-ClientServerJSON](fiddles/node/fiddle-0008-ClientServerJSON) ~ [Issue 17](https://github.com/bradyhouse/house/issues/17)
    7.  Added [fiddles/node/fiddle-0009-Inheritance](fiddles/node/fiddle-0009-Inheritance) ~ [Issue 18](https://github.com/bradyhouse/house/issues/18)
    8.  Added [fiddles/node/fiddle-0010-ZeroMqPubSub](fiddles/node/fiddle-0010-ZeroMqPubSub) ~ [Issue 20](https://github.com/bradyhouse/house/issues/20)
    9.  Added [fiddles/node/fiddle-0011-ZeroMqReqRep](fiddles/node/fiddle-0011-ZeroMqReqRep) ~ [Issue 21](https://github.com/bradyhouse/house/issues/21)
    10. Added [fiddles/node/fiddle-0012-ZeroMqCluster](fiddles/node/fiddle-0012-ZeroMqCluster) ~ [Issue 26](https://github.com/bradyhouse/house/issues/26)
    11. Added [fiddles/node/fiddle-0013-CouchDB](fiddles/node/fiddle-0013-CouchDB) ~ [Issue 34](https://github.com/bradyhouse/house/issues/34)
    12. Added [fiddles/node/fiddle-0014-Express](fiddles/node/fiddle-0014-Express) ~ [Issue 36](https://github.com/bradyhouse/house/issues/36)
    13. Added [fiddles/node/fiddle-0015-RESTService](fiddles/node/fiddle-0015-RESTService) ~ [Issue 37](https://github.com/bradyhouse/house/issues/37)
    14. Added [fiddles/node/fiddle-0016-Redis](fiddles/node/fiddle-0016-Redis) ~ [Issue 41](https://github.com/bradyhouse/house/issues/41)

* **Ember**
    1.  Added [fiddles/ember/fiddle-0002-Inheritance](fiddles/ember/fiddle-0002-Inheritance) ~ [Issue 32](https://github.com/bradyhouse/house/issues/32)
    2.  Started [fiddles/ember/fiddle-0003-LifeCycle](fiddles/ember/fiddle-0003-LifeCycle) ~ [Issue 24](https://github.com/bradyhouse/house/issues/24)
    3.  Added dependency (submodule) to [emberjs-essentials](https://github.com/suchitpuri/emberjs-essentials)
    4.  Added dependency (submodule) to [broccollijs](https://github.com/broccolijs/broccoli)
    5.  Added [fiddles/ember/fiddle-0004-Mixins](fiddles/ember/fiddle-0004-Mixins) ~ [Issue 35](https://github.com/bradyhouse/house/issues/35)
    6.  Added [fiddles/ember/fiddle-0005-ComputedProperties](fiddles/ember/fiddle-0005-ComputedProperties) ~ [Issue 38](https://github.com/bradyhouse/house/issues/38)
    7.  Added [fiddles/ember/fiddle-0006-Observer](fiddles/ember/fiddle-0006-Observer) ~ [Issue 39](https://github.com/bradyhouse/house/issues/39)
    8.  Added [fiddles/ember/fiddle-0007-XObjectBinding](fiddles/ember/fiddle-0007-XObjectBinding) ~ [Issue 40](https://github.com/bradyhouse/house/issues/40)

* **Python**
    1.  Added dependency (submodule) to [coursera-dl](https://github.com/coursera-dl/coursera-dl)
    2.  Added [fiddles/python/fiddle-0009-CourseraDL](fiddles/python/fiddle-0009-CourseraDL) ~ [Issue 33](https://github.com/bradyhouse/house/issues/33)


### 201607010420

* **Ember**

* **Angular2**
    1.  Added [fiddles/angular2/fiddle-0044-GridStateRouting](fiddles/angular2/fiddle-0044-GridStateRouting) ~ [Issue 45](https://github.com/bradyhouse/house/issues/45)
    2.  Added [fiddles/angular2/fiddle-0045-AttributeDirective](fiddles/angular2/fiddle-0045-AttributeDirective) ~ [Issue 49](https://github.com/bradyhouse/house/issues/49)
    3.  Added [fiddles/angular2/fiddle-0046-StructuralDirective](fiddles/angular2/fiddle-0046-StructuralDirective) [Issue 50](https://github.com/bradyhouse/house/issues/50)
    4.  Started [fiddles/angular2/fiddle-0047-HeightDirective](fiddles/angular2/fiddle-0046-HeightDirective) [Issue 56](https://github.com/bradyhouse/house/issues/56)

* **SVG**
    1.  Added [fiddles/svg/fiddle-0026-Images](fiddles/svg/fiddle-0026-Images) ~ [Issue 44](https://github.com/bradyhouse/house/issues/44)
    2.  Added [fiddles/svg/fiddle-0027-ImageCloud](fiddles/svg/fiddle-0027-ImageCloud) ~ [Issue 51](https://github.com/bradyhouse/house/issues/51)

* **Node**
    1.  Added [fiddles/node/fiddle-0017-WebApp](fiddles/node/fiddle-0017-WebApp) ~ [Issue 46](https://github.com/bradyhouse/house/issues/46)
    2.  Added [fiddles/node/fiddle-0018-XmlToJson](fiddles/node/fiddle-0018-XmlToJson) ~ [Issue 48](https://github.com/bradyhouse/house/issues/48)
    3.  Added dependency (submodule) to [jimbojw > right-way](https://github.com/jimbojw/right-way)
    4.  Added [fiddles/node/fiddle-0019-PassThruRest](fiddles/node/fiddle-0019-PassThruRest) ~ [Issue 58](https://github.com/bradyhouse/house/issues/58)

* **ES2015 / JQuery**
    1.  Added [fiddles/jquery/fiddle-0038-CorsRequest](fiddles/jquery/fiddle-0038-CorsRequest) ~ [Issue 52](https://github.com/bradyhouse/house/issues/52)
    2.  Added [fiddles/jquery/fiddle-0039-MomentJs](fiddles/jquery/fiddle-0039-MomentJs) ~ [Issue 53](https://github.com/bradyhouse/house/issues/53)
    3.  Added [fiddles/jquery/fiddle-0040-FabricJs](fiddles/jquery/fiddle-0040-FabricJs) ~ [Issue 54](https://github.com/bradyhouse/house/issues/54)
    4.  Added [fiddles/jquery/fiddle-0041-FabricImageCloud](fiddles/jquery/fiddle-0041-FabricImageCloud) ~ [Issue 57](https://github.com/bradyhouse/house/issues/57)


### 201609160420

* **fiddle.sh**
    1.  Extended [scripts/bin/_util.sh](scripts/bin/_util.sh)
        *   See [bash fiddle #91](fiddles/bash/fiddle-0091-SplitDelimitedString)
    2.  Fixed [Bug ~ Issue #60](https://github.com/bradyhouse/house/issues/60)
        *   Reflected changes:
          1.  Updated [scripts/bin/nativescript/_install.sh](scripts/bin/nativescript/_install.sh)
          2.  Updated [scripts/bin/nativescript/_create.sh](scripts/bin/nativescript/_create.sh)
          3.  Updated [scripts/bin/nativescript/_start.sh](scripts/bin/nativescript/_start.sh)
          4.  Updated [scripts/bin/fiddle-start.sh](scripts/bin/fiddle-start.sh)
          5.  Updated [scripts/bin/fiddle-nativescript.sh](scripts/bin/fiddle-nativescript.sh)
          6.  Added [scripts/bin/nativescript/.nativescriptrc](scripts/bin/nativescript/.nativescriptrc)
          7.  Updated [scripts/bin/fiddle-fork.sh](scripts/bin/fiddle-fork.sh)
    3.  Fixed [Bug ~ Issue #63](https://github.com/bradyhouse/house/issues/63)
        * Reflected changes:
          1.  Updated [scripts/bin/fiddle-create.sh](scripts/bin/fiddle-create.sh)
          2.  Updated [scripts/bin/fiddle-delete.sh](scripts/bin/fiddle-delete.sh)
    4.  Fixed [Bug ~ Issue #66](https://github.com/bradyhouse/house/issues/66)
        * Reflected changes:
          1.  Updated [scripts/bin/fiddle-fork.sh](scripts/bin/fiddle-fork.sh)
          2.  Added [scripts/bin/nativescript/_fork.sh](scripts/bin/nativescript/_fork.sh)
          3.  Updated [scripts/bin/nativescript/_start.sh](scripts/bin/nativescript/_start.sh)
    5.  Added Java support
        * See [fiddles/bash/fiddle-0092-InitJavaProject](fiddles/bash/fiddle-0092-InitJavaProject)
        * Reflected changes:
          1.  Added [scripts/bin/java](scripts/bin/java)
          2.  Added [scripts/fiddle-java.sh](scripts/fiddle-java.sh)
          3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
          4.  Updated [scripts/bin/_types.sh](scripts/bin/_types.sh)
          5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
          6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
          7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
          8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
          9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
          10. Updated [fiddles/java/README.md](fiddles/java/README.md)

* **Bash**
    1.  Added [fiddles/bash/fiddle-0091-SplitDelimitedString](fiddles/bash/fiddle-0091-SplitDelimitedString) ~ [Issue #62](https://github.com/bradyhouse/house/issues/62)
    2.  Added [fiddles/bash/fiddle-0092-InitJavaProject](fiddles/bash/fiddle-0092-InitJavaProject) ~ [Issue #67](https://github.com/bradyhouse/house/issues/67)
    3.  Started [fiddles/bash/fiddle-0093-InitAndroidProject](fiddles/bash/fiddle-0093-InitAndroidProject) ~ [Issue 77](https://github.com/bradyhouse/house/issues/77)
 
* **Ember**
    1.  Added [fiddles/ember/fiddle-0000-Template](fiddles/ember/fiddle-0000-Template)

* **ExtJS 6**
    1.  Added [fiddles/extjs6/fiddle-0036-ItunesTop100](fiddles/extjs6/fiddle-0036-ItunesTop100) ~ [Issue #74](https://github.com/bradyhouse/house/issues/74)

* **NativeScript**
    1.  Added [fiddles/nativescript/fiddle-0000-Template](fiddles/nativescript/fiddle-0000-Template)
    2.  Added [fiddles/nativescript/fiddle-0001-PageNavigation](fiddles/nativescript/fiddle-0001-PageNavigation) ~ [Issue #64](https://github.com/bradyhouse/house/issues/64)
    3.  Added [fiddles/nativescript/fiddle-0002-DeclarativeUI](fiddles/nativescript/fiddle-0002-DeclarativeUI) ~ [Issue #65](https://github.com/bradyhouse/house/issues/65)
    4.  Added dependency (submodule) to [Getting Started with NativeScript > Chapter 1 Repo](https://github.com/GettingStartedWithNativeScript/Chapter_1)
      *   [fiddles/nativeScript/libs/Chapter_1](fiddles/nativeScript/libs/Chapter_1)
    5.  Added dependency (submodule) to [Getting Started with NativeScript > Chapter 2 Repo](https://github.com/GettingStartedWithNativeScript/Chapter_2)
      *   [fiddles/nativeScript/libs/Chapter_2](fiddles/nativeScript/libs/Chapter_2)
    6.  Added dependency (submodule) to [Getting Started with NativeScript > Chapter 3 Repo](https://github.com/GettingStartedWithNativeScript/Chapter_3)
      *   [fiddles/nativeScript/libs/Chapter_3](fiddles/nativeScript/libs/Chapter_3)
    7.  Added dependency (submodule) to [Getting Started with NativeScript > Chapter 4 Repo](https://github.com/GettingStartedWithNativeScript/Chapter_4)
      *   [fiddles/nativeScript/libs/Chapter_4](fiddles/nativeScript/libs/Chapter_4)
    8.  Added dependency (submodule) to [Getting Started with NativeScript > Chapter 5 Repo](https://github.com/GettingStartedWithNativeScript/Chapter_5)
      *   [fiddles/nativeScript/libs/Chapter_5](fiddles/nativeScript/libs/Chapter_5)
    9.  Added dependency (submodule) to [Getting Started with NativeScript > Chapter 6 Repo](https://github.com/GettingStartedWithNativeScript/Chapter_6)
      *   [fiddles/nativeScript/libs/Chapter_6](fiddles/nativeScript/libs/Chapter_6)
    10. Added [fiddles/nativescript/fiddle-0003-RssReader](fiddles/nativescript/fiddle-0003-RssReader) ~ [Issue 68](https://github.com/bradyhouse/house/issues/68)
    11. Added dependency (submodule) to [Raymond Camden's NativeScripts Demo Repo](https://github.com/cfjedimaster/NativeScriptDemos)
      *   [fiddles/nativeScript/libs/NativeScriptDemos](fiddles/nativeScript/libs/NativeScriptDemos)
    12. Added [fiddles/nativescript/fiddle-0004-Layouts](fiddles/nativescript/fiddle-0004-Layouts) ~ [Issue 70](https://github.com/bradyhouse/house/issues/70)
    13. Added [fiddles/nativescript/fiddle-0005-Chat](fiddles/nativescript/fiddle-0005-Chat)
    14. Added dependency (submodule) to [Nathanael Anderson's Simple Web Server](https://github.com/GettingStartedWithNativeScript/crossCommunicator_Server)
      *   [fiddles/nativeScript/libs/crossCommunicator_Server](fiddles/nativeScript/libs/crossCommunicator_Server) 
    15. Added [fiddles/nativescript/fiddle-0006-Plugins](fiddles/nativescript/fiddle-0006-Plugins) ~ [Issue 73](https://github.com/bradyhouse/house/issues/73)
    16. Added [fiddles/nativescript/fiddle-0007-SvgPlugin](fiddles/nativescript/fiddle-0007-SvgPlugin) ~ [Issue #79](https://github.com/bradyhouse/house/issues/79)

* **Node**
    1.  Added [fiddles/node/fiddle-0020-WebSocketServer](fiddles/node/fiddle-0020-WebSocketServer) ~ [Issue 72](https://github.com/bradyhouse/house/issues/72)

* **Java**
    1.  Added dependency (submodule) to [Spring Guide gs-gradle Repo](https://github.com/spring-guides/gs-gradle)
      *   [fiddles/java/libs/gs-gradle](fiddles/java/libs/gs-gradle)
    2.  Added [fiddles/java/fiddle-0003-SpringFox](fiddles/java/fiddle-0003-SpringFox) ~ [Issue #78](https://github.com/bradyhouse/house/issues/78)


### 201610010420

* **Bash**
    1.  Finished [fiddles/bash/fiddle-0093-InitAndroidProject](fiddles/bash/fiddle-0093-InitAndroidProject) ~ [Issue 77](https://github.com/bradyhouse/house/issues/77)

* **fiddle.sh**
    1.  Added Android support ~ ~ [Issue 80](https://github.com/bradyhouse/house/issues/80)
      * See [fiddles/bash/fiddle-0093-InitAndroidProject](fiddles/bash/fiddle-0093-InitAndroidProject)
      * Reflected changes:
        1.  Added [scripts/bin/android](scripts/bin/android)
        2.  Added [scripts/fiddle-android.sh](scripts/fiddle-android.sh)
        3.  Updated [scripts/fiddle-create.sh](scripts/fiddle-create.sh)
        4.  Updated [scripts/bin/_types.sh](scripts/bin/_types.sh)
        5.  Updated [scripts/fiddle-list.sh](scripts/fiddle-list.sh)
        6.  Updated [scripts/fiddle-refactor.sh](scripts/fiddle-refactor.sh)
        7.  Updated [scripts/fiddle-delete.sh](scripts/fiddle-delete.sh)
        8.  Updated [scripts/fiddle-fork.sh](scripts/fiddle-fork.sh)
        9.  Updated [scripts/fiddle-start.sh](scripts/fiddle-start.sh)
        10. Updated [fiddles/android/README.md](fiddles/android/README.md)

* **Java**
  1.  Started [fiddles/java/fiddle-0004-CSVToJsonEndpoint](fiddles/java/fiddle-0004-CSVToJsonEndpoint) ~  [Issue 81](https://github.com/bradyhouse/house/issues/81)

* **NativeScript**
  1.  Added [fiddles/nativescript/fiddle-0008-FifteenPuzzle](fiddles/nativescript/fiddle-0008-FifteenPuzzle) ~ [Issue 83](https://github.com/bradyhouse/house/issues/83)
  2.  Added [fiddles/nativescript/fiddle-0009-SqliteDb](fiddles/nativescript/fiddle-0009-SqliteDb) ~ [Issue 84](https://github.com/bradyhouse/house/issues/84)        
  3.  Started [fiddles/nativescript/fiddle-0010-Puzzle](fiddles/nativescript/fiddle-0010-Puzzle) ~ [Issue 85](https://github.com/bradyhouse/house/issues/85)

* **Node**
  1.  Added [fiddles/node/fiddle-0021-DirectoryWatcher](fiddles/node/fiddle-0021-DirectoryWatcher) ~  [Issue 82](https://github.com/bradyhouse/house/issues/82)
