![WooCommerce Steem](https://steemitimages.com/0x0/https://ps.w.org/woo-steem/assets/banner-1544x500.png?rev=1670250)

# WooCommerce Steem
Accept Steem payments directly to your WooCommerce shop!

## Supported Steem Currencies
- Steem (STEEM)
- Steem Backed Dollars (SBD)

## Limitation
- Currently supports different fiat currencies such as: AUD, BGN, BRL, CAD, CHF, CNY, CZK, DKK, GBP, HKD, HRK, HUF, IDR, ILS, INR, JPY, KRW, MXN, MYR, NOK, NZD, PHP, PLN, RON, RUB, SEK, SGD, THB, TRY, ZAR, EUR
- If none of the fiat currency listed above, it will default 1:1 conversion rate.

## How does it confirm Steem Transfers?
It uses WordPress CRON every 5 minutes to call WooCommerce orders that uses payment method as Steem and calls an API via Steemful (Another application I'm building around WordPress ecosystem) powered by SteemSQL.

## Note
You will <strong>NOT</strong> require any Steem keys for this plugin to work. You just have to provide your Steem username and you're good to go.

## Screenshots

![Screenshot #1](https://steemitimages.com/0x0/https://imgoat.com/uploads/8f13708210/19682.png)
![Screenshot #2](https://steemitimages.com/0x0/https://imgoat.com/uploads/8f13708210/19684.png)

WooCommerce Settings (Backend)
![Screenshot #3](https://imgoat.com/uploads/8f13708210/19683.png)

## Links
- [WordPress Plugin Repository](https://wordpress.org/extend/plugins/woo-steem)

## Thanks
- [@arcange](https://steemit.com/@arcange) for [SteemSQL](https://steemsql.com)
- [@furion](https://steemit.com/@furion) for SteemData (Fallback when SteemSQL doesn't yet index Steem blockchain)

## Support
Please support me by following me on Steem [@recrypto](https://steemit.com/@recrypto) or if you feel like donating, that would really help a lot on my future Steem developments around WordPress ecosystem. :)

Steem: @recrypto
