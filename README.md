# hass-ttlock

Home Assistant integration for TTLock based locks.

## Currently supported features

- Locking and unlocking
- Loading status on startup
- Limited handling of real-time events

## Known working locks

> If this integration is working for you, please leave a comment [here](https://github.com/jbergler/hass-ttlock/issues/1)

- [Catchface Smart Lock](https://s.click.aliexpress.com/e/_DFtl1Wd)
- [Cielsa Dawn Fingerprint Digital Doorknob](https://www.amazon.com/dp/B09B557YZK)
- [E-Lok 9 series](https://www.e-lok.com/9-series)
- [TOTOWISER locks](https://www.amazon.com.au/gp/product/B08TQKW3JC)
- [YRHAND locks](https://yrhandlock.com)

## Limitations (will be fixed over time)

- Almost everything else

# Usage

## Requirements

1. A TTLock based smart lock
1. A Gateway (if your lock doesn't have integrated wifi)
   - These can be purchased from the vendor of your lock or direct from [Aliexpress](https://s.click.aliexpress.com/e/_DEPpClx)

## Creating an OAuth APP

1. Go to https://open.ttlock.com/manager and create an account
1. Register an application (this will take a few days to get approved)
1. Install the extension via HACS
   - You will need to add add custom repository 'jbergler/hass-ttlock' of type 'integration'
1. Setup the integration via Home Assistant UI
1. Once the integration is working you should receive a notification with the webhook url
   - This will go away when the webhook receives data
1. Go back to the url from the first step and set the 'Callback URL' for your application

## Reporting issues

When reporting issues, please attach the diagnostic information and consider enabling debug logging to provide extra information.

## Say thanks

If you found this helpful and you'd like to say thanks you can do so via buy me a coffee. Thanks!

<a href="https://www.buymeacoffee.com/jbergler" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="60" width="217"></a>
