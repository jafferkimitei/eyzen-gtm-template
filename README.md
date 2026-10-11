# Eyzen Chat for Google Tag Manager

<img src="icon.png" alt="" width="64" height="64" />

Adds [Eyzen](https://eyzen.eycube.com), the AI assistant for websites by Eycube, to every page of a website through Google Tag Manager, without touching the site's code.

## Use it

1. In your GTM container, go to **Templates**, **Tag Templates**, **Search Gallery**, and add **Eyzen Chat**. (Or download `template.tpl` from this repository and choose **New**, then the menu, then **Import**.)
2. Go to **Tags**, **New**, and choose the **Eyzen Chat** tag type.
3. Enter your **Site ID** (`eyzs_...`), from the [Eyzen console](https://console.eyzen.eycube.com) under your site's **Install** tab. Optionally choose the chat's position.
4. Set the trigger to **All Pages**, then **Submit** and publish the container.

Make sure your website's address is listed under your site's allowed websites in the Eyzen console: Eyzen only answers on those addresses.

## What it does

The tag sets `window.EyzenConfig` to your Site ID and position, then loads `https://eyzen.eycube.com/embed/v1/eyzen.js`. Those are the only two permissions it asks for. Your Site ID is public and safe to use in website code.

Full install guide for every platform: https://eyzen.eycube.com/docs/install

## Support

Open an issue in this repository, or email support@eycube.com.

## License

Apache License 2.0. See [LICENSE](LICENSE).
