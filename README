Firefox Popup Alerts

Simpe library that adds two new methods to the window:

window.falert();
window.fconfrim();

# Add focus back to alerts and confirms in a popup windows only for FF 4+

* Author: Steven Irby 
* License: GPLv2/MIT

## Installation and Usage

Just add JS file to the page of a popup you want to focus with an alert or confirm. (only way to focus a popup window in FF 4+ now; without having the user initiate a function) If user clicks ok for an alert, the page is reloaded.

### 1. Add Script to popup window

	<script type="text/javascript" src="focusalerts.js"></script>

### 2. falert:

    falert( message [, url ] );

    url - default is window.location.href + '?'

    Example:

    window.falert('Alert with focus!');
    window.falert('Alert with focus!', 'http://example.com/popup.html?alertFired=true');

### 2. fconfirm

    fconfirm( message [, url] [, cancelCallback ] [, okCallback ]);

    Example:

    function close() {
        window.close();
    }

    window.fconfirm('Do you want to continue?', null, close);

