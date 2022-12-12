# vim-study

# nomal mode

# visual mode
v, V, ctrl + v

After a client has successfully joined a channel,
incoming events from the client are routed through the channel's handle_in/3 callbacks.
Within these callbacks, you can perform any action.
Typically you'll either forward a message to all listeners with broadcast!/3,
or push a message directly down the socket with push/3.
Incoming callbacks must return the socket to maintain ephemeral state.

# select mode
v - ctrl + g

# insert mode
i

# command-line mode
:, /, ?

# ex mode
:1y
:1,2 co 30
:/pattern/ d
:% s/old/new/g

# operator pending mode
d4w

# replace mode
R, r

# virtual replace mode
gR

# insert normal mode
i -> ctrl + o

# insert visual mode
i -> ctrl + o -> v
