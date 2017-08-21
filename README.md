# lonely-ircd - The loneliness IRC server

lonely-ircd aims to be a fully-featured Internet Relay Chat server, except for one intentionally missing feature: multi-user communication.
When you connect to lonely-ircd, you have the entire server to yourself.
Join some channels, look around, and wait for the other people who will never arrive.

## Why?

It's art.
Or its purpose is to test IRC clients.
Or it's making a societal statement about nihilism.
Or it was something fun to write one afternoon.

## Try it out

Either run the daemon yourself (it requires Python 3.4+ and nothing more than stdlib), or try a running test server (example invocation using irssi; adapt to your favorite IRC client):

```
/network add lonely
/server add -auto -ssl -ssl_verify -network lonely lonely-irc.colobox.com 6697
/connect lonely
```

## Current status

A basic handful of commands are supported, enough to make irssi happy joining and parting channels.  SSL is supported, as is IPv6.