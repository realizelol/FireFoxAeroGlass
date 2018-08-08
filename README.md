# FireFoxAeroGlass
#

```
#main-window[windowtype="navigator:browser"] {
    background-color: transparent !important;
}
 
.titlebar-button {
    background-color: transparent !important;
    transition: background-color 0.2s ease;
}
 
.titlebar-button > .toolbarbutton-icon {
    list-style-image: none;
}
 
.titlebar-button:hover {
    background-color: rgba(0, 0, 0, 0.15) !important;
}

#titlebar-close:hover > .toolbarbutton-icon {
    /* list-style-image: url("chrome://browser/skin/caption-buttons.svg#close-white") !important; */
	background-color: transparent !important;
}

#titlebar-buttonbox .titlebar-button {
	background-color: transparent !important;
}

/* */

/* Firefox Quantum userChrome.css tweaks ************************************************/
/* Github: https://github.com/aris-t2/customcssforfx ************************************/
/****************************************************************************************/
/* Glass8 ( http://www.glass8.eu/ ) required for 'Windows 7'-like window transparency */

@-moz-document url(chrome://browser/content/browser.xul) {
	#main-window {
	  background-color: transparent !important;
	  -moz-appearance: -moz-win-glass !important;
	}
}
#main-window:not([customizing]) .titlebar-button,
#main-window:not([customizing]) .titlebar-button > .toolbarbutton-icon{
  opacity: 0.01 !important;
}
#main-window:not([customizing]) .titlebar-button:hover {
  opacity: 0.3 !important;
  background: #FF6666 !important;
  margin-bottom: 10px !important;
  margin-right: 2px !important;
  margin-left: -2px !important;
}
#main-window:not([customizing]) .titlebar-button:not(#titlebar-close):hover {
  opacity: 0.45 !important;
  background: #BFFFF0 !important;
  margin-bottom: 10px !important;
    margin-left: -2px !important;
}
#main-window:not([customizing]) .titlebar-button:first-child:hover {
    padding-left: 10px !important;
}
#main-window  {
  background-color: transparent !important;
  -moz-appearance: -moz-win-glass !important;
  background-image: none !important;
}
#navigator-toolbox {
  background-color: transparent !important;
  color: #FFFFFF !important;
}
#TabsToolbar {
  background-color: transparent !important;
}
.tabbrowser-tab > .tab-stack > .tab-background {
		background-color: #404040 !important;
}
```
