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

# Usage in rails projects

... rudimentary step-by-step for now...

1. git clone kpolitowicz/kamil
1. clone your rails project
1. copy .chang/ and .changingnore from there to your rails project
1. cp config/database.yml.hal config/database.yml
1. cp config/sunspot.yml.hal config/sunspot.yml
1. hal build
1. hal start
