# MapTool Scripting Language README

This is a VS Code extension intended to support the [MapTool](http://www.rptools.net/toolbox/maptool/) scripting language. 
MapTool is an excellent virtual tabletop for roleplaying games, and amount many brilliant features, sports a comprehensive scripting language. 

## Features

There are not many at the moment, but over time this extension will offer full support for the MapTool scripting language. 

## Requirements

This extension will support the scripting language as of MapTool version 1.4 and newer.
It requires VS Code 1.32.

## Extension Settings


## Known Issues



## Release Notes

### 0.0.1

* Very basic support, barely worth mentioning :)

DISCLAIMER: Logo has been shamelessly stolen from rptool.net...








**Operators:**
+   &&  =   /   ==  >   >=  <   <=  *   !   !=  ||  ^   -

**Special Variables**
bar.*|state.*|init.current|init.denyChange|init.round|json.false|json.null|json.true|macro.args|macro.args.num|macro.catchAbort|macro.catchAssert|macro.return|token.gm_name|token.halo|token.init|token.initHold|token.label|token.name|token.visible|tokens.denyMove|tokens.moveCount

**Reserved Words:**
abs|absolutevalue|add|sum|concat|and|set|bitwiseand|band|bitwisenot|bnot|bitwiseor|bor|bitwisexor|bxor|ceil|ceiling|divide|eq|equals|eval|floor|trunc|intPart|gt|ge|hex|hypot|hypotenuse|lt|le|ln|log|log10|max|mean|avg|average|median|min|multiply|not|ne|or|sqr|square|power|factor|pow|round|sqrt|squareroot|eqs|strEquals|equalsStrict|neqs|strNotEquals|notEqualsStrict|subtract|false|true

**Roll Options:**
e|expanded|h|hidden|hide|r|result|u|unformatted|t|tooltip|g|gm|s|self|w|whisper|gt|gmtt|st|selftt|c|count|for|foreach|while|if|switch|code|macro|frame|dialog|dialog5|frame5|overlay|token

**Dice Rolling Functions**
arsMagicaStress|arsMagicaStressNum|countsuccess|d|dice|drop|dropHighest|explode|explodingSuccess|f|fudge|hero|herobody|herokilling|herokilling2|heromultiplier|herostun|keep|keepLowest|killing|multiplier|openTest|reroll|rerollOnce|roll|rollAddWithLower|rollAddWithUpper|rollSubWithLower|rollSubWithUpper|rollWithLower|rollWithUpper|sr4|sr4e|sr5|sr5e|success|u|ubiquity

**Functions:**
REST.delete|REST.get|REST.patch|REST.post|REST.put|abort|addAllNPCsToInitiative|addAllPCsToInitiative|addAllToInitiative|addTableEntry|addToInitiative|arg|argCount|assert|base64.decode|base64.encode|bringDrawingToFront|bringToFront|broadcast|canSeeToken|capitalize|clearLights|clearRolls|clearTable|closeDialog|closeFrame|closeOverlay|copyMap|copyTable|copyToken|countStrProp|createMacro|createTable|createToken|createTokens|currentToken|data.getStaticData|decode|defineAudioSource|defineFunction|deleteStrProp|deleteTable|deleteTableEntry|deselectTokens|drawHillVBL|drawMBL|drawPitVBL|drawVBL|editStream|encode|endsWith|eraseHillVBL|eraseMBL|erasePitVBL|eraseVBL|evalMacro|execFunction|execLink|execMacro|exportData|exposeAllOwnedArea|exposeFOW|exposeFogAtWaypoints|exposePCOnlyArea|findDrawings|findToken|flipTokenIso|flipTokenX|flipTokenY|formatStrProp|getAllMapDisplayNames|getAllMapNames|getAllPlayerNames|getAllPropertyNames|getAllowsURIAccess|getAlwaysVisible|getAssetProperties|getBar|getBarImage|getCurrentInitiative|getCurrentMapName|getDefinedFunctions|getDialogProperties|getDistance|getDistanceToXY|getDrawingEraser|getDrawingInfo|getDrawingLayer|getDrawingOpacity|getDrawingProperties|getEnvironmentVariable|getExposedTokenNames|getExposedTokens|getFillColor|getFindCount|getFrameProperties|getGMName|getGMNotes|getGroup|getGroupCount|getGroupEnd|getGroupStart|getHalo|getHillVBL|getImage|getImpersonated|getImpersonatedName|getInfo|getInitiative|getInitiativeHold|getInitiativeList|getInitiativeRound|getInitiativeToken|getLabel|getLastPath|getLayer|getLibProperty|getLibPropertyNames|getLights|getLineCap|getMBL|getMacroButtonIndex|getMacroCommand|getMacroContext|getMacroGroup|getMacroIndexes|getMacroLocation|getMacroName|getMacroProps|getMacros|getMapDisplayName|getMapName|getMapVisible|getMatchingLibProperties|getMatchingProperties|getMaxLoopIterations|getMaxRecursionDepth|getMoveCount|getNPC|getNPCNames|getName|getNewRolls|getNotes|getOverlayProperties|getOwned|getOwnedNames|getOwnerOnlyVisible|getOwners|getPC|getPCNames|getPenColor|getPenWidth|getPitVBL|getPlayerName|getProperty|getPropertyDefault|getPropertyNames|getPropertyNamesRaw|getPropertyType|getRawProperty|getRecursionDepth|getRolled|getSelected|getSelectedNames|getSightType|getSize|getSoundProperties|getSpeech|getSpeechName|getSpeechNames|getState|getStateImage|getStrProp|getTableAccess|getTableEntry|getTableImage|getTableNames|getTablePickOnce|getTablePicksLeft|getTableRoll|getTableVisible|getTerrainModifier|getTextLabelStatus|getTokenDrawOrder|getTokenFacing|getTokenHandout|getTokenHeight|getTokenImage|getTokenLayoutProps|getTokenMap|getTokenName|getTokenNames|getTokenNativeHeight|getTokenNativeWidth|getTokenOpacity|getTokenPortrait|getTokenRotation|getTokenShape|getTokenStates|getTokenVBL|getTokenWidth|getTokenX|getTokenY|getTokens|getVBL|getViewArea|getViewCenter|getVisible|getVisibleMapDisplayNames|getVisibleMapNames|getVisibleTokenNames|getVisibleTokens|getWithState|getWithStateNames|getZoom|goto|hasImpersonated|hasLightSource|hasMacro|hasProperty|hasSight|herolab.XPath|herolab.getImage|herolab.getInfo|herolab.getMasterName|herolab.getStatBlock|herolab.hasChanged|herolab.isMinion|herolab.refresh|hideTextLabels|html.dialog|html.dialog5|html.frame|html.frame5|html.overlay|impersonate|indexKeyStrProp|indexOf|indexValueStrProp|initiativeSize|input|isBarVisible|isDialogVisible|isExternalMacroAccessAllowed|isFlippedIso|isFlippedX|isFlippedY|isFrameVisible|isFunctionDefined|isGM|isNPC|isNumber|sOverlayRegistered|isOverlayVisible|isOwnedByAll|isOwner|isPC|isPropertyEmpty|isSnapToGrid|isTrusted|isVisible|js.createNS|js.eval|js.evalNS|js.evalURI|js.removeNS|json.append|json.contains|json.count|json.difference|json.equals|json.evaluate|json.fields|json.fromList|json.fromStrProp|json.get|json.indent|json.indexOf|json.intersection|json.isEmpty|json.isSubset|json.length|json.merge|json.objrolls|json.path.add|json.path.delete|json.path.put|json.path.read|json.path.set|json.remove|json.removeAll|json.removeFirst|json.reverse|json.rolls|json.set|json.shuffle|json.sort|json.toList|json.toStrProp|json.toVars|json.type|json.union|json.unique|lastIndexOf|lastRolled|length|library.getContents|library.getInfo|library.listAddOnLibraries|library.listTokenLibraries|listAppend|listContains|listCount|listDelete|listFind|listFormat|listGet|listInsert|listReplace|listSort|log.debug|log.error|log.fatal|log.getLoggers|log.info|log.setLevel|log.trace|log.warn|lower|macroLink|macroLinkText|markdownToHTML|matches|math.abs|math.acos|math.acos_r|math.arrayMax|math.arrayMean|math.arrayMedian|math.arrayMin|math.arrayProduct|math.arraySum|math.asin|math.asin_r|math.atan|math.atan2|math.atan2_r|math.atan_r|math.cbrt|math.ceil|math.cos|math.cos_r|math.cuberoot|math.e|math.floor|math.hypot|math.hypotenuse|math.isEven|math.isInt|math.isOdd|math.listMax|math.listMean|math.listMedian|math.listMin|math.listProduct|math.listSum|math.log|math.log10|math.max|math.min|math.mod|math.pi|math.pow|math.sin|math.sin_r|math.sqrt|math.squareroot|math.tan|math.tan_r|math.toDegrees|math.toRadians|moveToken|moveTokenFromMap|moveTokenToMap|movedOverDrawing|movedOverPoints|movedOverToken|nextInitiative|number|oldFunction|playClip|playStream|player.getConnectedPlayers|player.getInfo|player.getName|player.getPlayers|prevInitiative|refreshDrawing|removeAllFromInitiative|removeAllNPCsFromInitiative|removeAllPCsFromInitiative|removeDrawing|removeFromInitiative|removeMacro|removeToken|removeTokenFacing|replace|resetFrame|resetProperty|resetSize|resetTablePicks|restoreFoW|return|runJsFunction|selectTokens|sendDrawingToBack|sendToBack|setAllStates|setAllowsURIAccess|setAlwaysVisible|setBar|setBarVisible|setCurrentInitiative|setCurrentMap|setDrawingEraser|setDrawingLayer|setDrawingName|setDrawingOpacity|setDrawingProperties|setFillColor|setGMName|setGMNotes|setHalo|setHasSight|setInitiative|setInitiativeHold|setInitiativeRound|setLabel|setLayer|setLibProperty|setLight|setLineCap|setMacroCommand|setMacroProps|setMapDisplayName|setMapName|setMapSelectButton|setMapVisible|setMaxLoopIterations|setMaxRecursionDepth|setNPC|setName|setNotes|setOverlayVisible|setOwnedByAll|setOwner|setOwnerOnlyVisible|setPC|setPenColor|setPenWidth|setProperty|setPropertyType|setSightType|setSize|setSpeech|setSpeechName|setState|setStrProp|setTableAccess|setTableEntry|setTableImage|setTablePickOnce|setTableRoll|setTableVisible|setTerrainModifier|setTokenDrawOrder|setTokenFacing|setTokenHandout|setTokenHeight|setTokenImage|setTokenLayoutProps|setTokenOpacity|setTokenPortrait|setTokenShape|setTokenSnapToGrid|setTokenVBL|setTokenWidth|setViewArea|setVisible|setZoom|showTextLabels|sortInitiative|startsWith|stopSound|strPropFromVars|strfind|strformat|string|stringToList|substring|switchToken|table|tableImage|tbl|tblImage|test.equal|test.run|toggleFoW|transferVBL|trim|upper|varsFromStrProp|getTokenHillVBL|getTokenMBL|getTokenPitVBL|server.isHosting|server.isPersonal|server.isServer|setTokenHillVBL|setTokenMBL|setTokenPitVBL|transferHillVBL|transferMBL|transferPitVBL
