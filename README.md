# wizSpinner

The wizSpinner wrapper wraps around the wizSpinner/nativeSpinner PhoneGap
plugin, and exposes a virtually identical API.

For the phonegap plugin, please refer to:
[wizSpinner github repo](https://github.com/Wizcorp/phonegap-plugin-wizSpinner)

## API

`window.pg.wizSpinner.create(options, cb)`
This call will create the spinner with the given options (please refer to the
plugin's reference).

`window.pg.wizSpinner.show(options, cb)`
This shows the spinner, optionally augmenting the options given on creation
time.

`window.pg.wizSpinner.hide(cb)`
This hides the spinner.

