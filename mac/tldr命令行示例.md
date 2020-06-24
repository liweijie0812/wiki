# tldr 为命令提供使用示例

``` bash
~ ᐅ tldr tar                    

tar

Archiving utility.
Often combined with a compression method, such as gzip or bzip.
More information: <https://www.gnu.org/software/tar>.

- Create an archive from files:
    tar cf target.tar file1 file2 file3

- Create a gzipped archive:
    tar czf target.tar.gz file1 file2 file3

- Create a gzipped archive from a directory using relative paths:
    tar czf target.tar.gz -C path/to/directory .

- Extract a (compressed) archive into the current directory:
    tar xf source.tar[.gz|.bz2|.xz]

- Extract an archive into a target directory:
    tar xf source.tar -C directory

- Create a compressed archive, using archive suffix to determine the compression program:
    tar caf target.tar.xz file1 file2 file3

- List the contents of a tar file:
    tar tvf source.tar

- Extract files matching a pattern:
    tar xf source.tar --wildcards "*.html"

- Extract a specific file without preserving the folder structure:
    tar xf source.tar source.tar/path/to/extract --strip-components=depth_to_strip
```

## 安装

| Client                                                       | Installation instructions                                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Web client](https://github.com/ostera/tldr.jsx)             | Visit [https://tldr.ostera.io](https://tldr.ostera.io/)      |
| [Node.js client](https://github.com/tldr-pages/tldr-node-client) | `npm install -g tldr`                                        |
| [Ruby client](https://github.com/YellowApple/tldrb)          | `gem install tldrb`                                          |
| [Haskell client](https://github.com/psibi/tldr-hs)           | `stack install tldr`                                         |
| [Perl client](https://github.com/skaji/perl-tldr)            | `cpanm App::tldr`                                            |
| [Python client](https://github.com/tldr-pages/tldr-python-client) | `pip install tldr` / `pacman -S tldr`                        |
| [C client](https://github.com/tldr-pages/tldr-c-client)      | `brew install tldr`                                          |
| [Rust client](https://github.com/dbrgn/tealdeer/)            | `cargo install tealdeer` / `yaourt -S tealdeer`              |
| [iOS client](https://github.com/freesuraj/TLDR)              | [TLDR Man Page on App Store](https://appsto.re/sg/IQ0-_.i)   |
| [Dash for macOS](https://github.com/Moddus/tldr-python-dash-docset) | open `Preferences > Downloads > User Contributed` and find `tldr pages` in the list |
| [Bash client](https://github.com/pepa65/tldr-bash-client)    | `bpkg install pepa65/tldr`                                   |
| [Go client](https://github.com/isacikgoz/tldr)               | `go get -u github.com/isacikgoz/tldr`                        |

[官网地址 https://tldr.sh](https://tldr.sh/)

[github https://github.com/tldr-pages/tldr](https://github.com/tldr-pages/tldr)