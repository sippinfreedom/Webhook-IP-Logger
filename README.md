# WebHook IP Tracker

IP Logger using an ip tracker and sends informational traffic to a discordant channel via webhooks



##  Installation Process
1. Upload the index.php and script.php files to the same level in the tree structure of your web hosting.
2. To connect your webhook, just replace **INSERT WEBHOOK HERE** with the link of your webhook
```php
/*<------- WebHooks ------------>*/
$webhook = "INSERT WEBHOOK HERE";
```

##  Modification

To change the display of the data, modify this part with MarkDown
```php                             
"
IP: {$geoplugin->ip}
Os: $user_os
Navigator: $user_browser
Datation: $time
City: {$geoplugin->city}
Region: {$geoplugin->region}
Region Code: {$geoplugin->regionCode}
Region Nom: {$geoplugin->regionName}
DMA Code: {$geoplugin->dmaCode}
Pays: {$geoplugin->countryName}
Code pays: {$geoplugin->countryCode}
Europeen ?: {$geoplugin->inEU}
Latitude: {$geoplugin->latitude}
Longitude: {$geoplugin->longitude}
Accuracy (Miles): {$geoplugin->locationAccuracyRadius}
Timezone: {$geoplugin->timezone}
"
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

You can also contact me through discord - freedom#1068

## License
[MIT](https://choosealicense.com/licenses/mit/)
