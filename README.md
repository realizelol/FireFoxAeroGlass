# FireFoxAeroGlass
#

´´´
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
  opacity: 0.25 !important;
  background: #FF6666 !important;
  margin-bottom: 10px !important;
  margin-right: 2px !important;
  margin-left: -2px !important;
}
#main-window:not([customizing]) .titlebar-button:not(#titlebar-close):hover {
  opacity: 0.4 !important;
  background: #BFFFF0 !important;
  margin-bottom: 10px !important;
    margin-left: -2px !important;
}
#main-window:not([customizing]) .titlebar-button:first-child:hover {
    padding-left: 10px !important;
}
´´´
