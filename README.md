# PWAs 
Progressive web apps are a type of web applications which can act simialr to native applications on mobile  that is having its own icon, can be installed on a browser, working when offline, and provide push notifications.

## Manifest JSON
The manifest json which is  in the public folder should contain a short_name, name, start_url =".", display = standalone and icons which is an array of icon objects having keys "src", "sizes", "type", "purpose" and hve elements of size(purpose) 72x72(maskable), 96x96(maskable), 128x128(maskable), 144x144(any), 152x152(maskable), 192x192(maskable), 384x384(maskable), 512x512(maskable)  