# leeds-js-post
Send push notifications to the browsers of LeedsJS using push notifications. 

Behind the scenes it uses a Polymer `platinum-push-messaging` element that registers a browser for
push notifications, and a `node` server that collects all the registered clients
and sends them messages.

