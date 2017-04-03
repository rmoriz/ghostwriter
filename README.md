# ghostwriter for macOS

hack to write login/password into a noVNC window that does not allow pasting. Also change keyboard layout because most setups assume US keyboard layout.


## Setup

```shell
curl https://raw.githubusercontent.com/rmoriz/ghostwriter/master/ghostwriter -o /usr/local/bin/ghostwriter
chmod 755 /usr/local/bin/ghostwriter
```

## Usage

```shell
ghostwriter root '%$TZ%$G!231'
- saving keyboard layout...
- setting keyboard layout to U.S....
- you have 5 seconds to switch focus to noVNC window...
```
... now hurry up and switch to the right chrome tab ...
