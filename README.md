# PWAs 
Progressive web apps are a type of web applications which can act simialr to native applications on mobile  that is having its own icon, can be installed on a browser, working when offline, and provide push notifications.

## Manifest JSON
The manifest json which is  in the public folder should contain a short_name, name, start_url =".", display = standalone and icons which is an array of icon objects having keys "src", "sizes", "type", "purpose" and hve elements of size(purpose) 72*72(maskable), 96*96(maskable), 128*128(maskable), 144*144(any), 152*152(maskable), 192*192(maskable), 384*384(maskable), 512*512(maskable)  