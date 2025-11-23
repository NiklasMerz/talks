# State of WebViews- Can we fix things?

## Abstract

[WebViews](https://caniwebview.com/about/) are everywhere—but fragmented, inconsistent, and often invisible to web developers. Used for in-app browsers, hybrid apps, and [MiniApps](https://www.w3.org/groups/wg/miniapps/), WebViews form a significant part of the web platform that many developers unknowingly target. Some developers specifically build for WebViews in hybrid apps or MiniApps, while others create standard websites without realizing they'll run in WebView contexts with different behaviors and constraints. 

Through initiatives like [Baseline](https://caniwebview.com/baseline), [CanIWebView](https://caniwebview.com), [apps](https://caniwebview.com/apps), and the [WebView Community Group](https://github.com/WebView-CG), we're working to map this fragmented landscape and identify paths forward. MiniApps that are very popular in some markets also show a very strong fragmentation and very little standardization. With collaboration and improvements between WebViews, MiniApps, PWA, new technologies like [Isolated Web Apps](https://chromeos.dev/en/web/isolated-web-apps) or new engines like Servo there is good potential to improve the web in this space, but it's complicated.

The [W3C WebView Community Group](https://www.w3.org/community/webview/) was formed to identify, understand, and reduce the issues arising from the use of software components (typically referred as WebViews) that are used to render Web technology-based content. As member and co-chair of the community group I'd like to give a little overview what WebViews are today, the work we've done to improve interoperability, and call to action to "fix things" in this overlooked but critical part of the web platform.

