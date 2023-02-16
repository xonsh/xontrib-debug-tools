<p align="center">
Debug tools for xonsh shell. 
</p>

<p align="center">  
If you like the idea click ⭐ on the repo and <a href="https://twitter.com/intent/tweet?text=Nice%20xontrib%20for%20the%20xonsh%20shell!&url=https://github.com/xonsh/xontrib-debug-tools" target="_blank">tweet</a>.
</p>


## Installation

To install use pip:

```bash
xpip install xontrib-debug-tools
# or: xpip install -U git+https://github.com/xonsh/xontrib-debug-tools
```

## Usage

The package contains:

* `pdb` - Simple built-in debugger. Runs pdb on reception of [SIGUSR1 signal](https://www.gnu.org/software/libc/manual/html_node/Miscellaneous-Signals.html).
* `xog` - Simple command to establish and print [`$XONSH_TRACEBACK_LOGFILE`](https://xon.sh/envvars.html#xonsh-traceback-logfile).

### pdb

```bash
xontrib load pdb
```

### xog

```bash
xontrib load xog
xog --help
```

## Credits

This package was created with [xontrib template](https://github.com/xonsh/xontrib-template).
