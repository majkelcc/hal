# Installation

## MacOS

Run:

1. install-hal-dev-proxy
1. install-hal-shell-completion

## Linux

1. Install puma-dev manually
1. Run install-hal-dev-proxy
1. Manually modify PATH to include hal tools

<pre>
if [[ -d ~/hal ]]; then
  export PATH="${HOME}/hal:\${PATH}"
fi
</pre>
