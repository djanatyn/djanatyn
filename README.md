# djanatyn (they/them)

<p align="center"><img src="./randall.gif"></p>

Howdy :) I'm a curious hacker, and I love learning! I'm [non-binary](https://en.wikipedia.org/wiki/Non-binary_gender), please use [they/them pronouns](https://pronoun.is/they) for me. I spend much of my time writing [Nix](https://nixos.org/), [Haskell](https://www.haskell.org/), and [Rust](https://www.rust-lang.org/). I'm [Recurse Center](https://www.recurse.com/about) alumni.

I have a lot of favorite tools, including [emacs](https://www.gnu.org/software/emacs/), [radare2](https://rada.re/n/radare2.html), [lldb](https://lldb.llvm.org/), [entr](https://eradman.com/entrproject/), [jq](https://stedolan.github.io/jq/), [bwrap](https://github.com/containers/bubblewrap), [bpftrace](https://bpftrace.org/), [visidata](https://www.visidata.org/), [fd](https://github.com/sharkdp/fd), and [rg](https://github.com/BurntSushi/ripgrep).

---

I'm currently working on:
## <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/521c96fd04b0ea93034db8715eda5a4de27a58bb/icons/rust.svg" width="32"> [melee-inject](https://github.com/djanatyn/melee-inject)
  - Rust library replacing Super Smash Bros. Melee NTSC v1.02 DAT files (modifying character textures) within an ISO, transforming the GCM filesystem table.
  - Exploring WebAssembly support, replacing `gc_gcm` dependency
## <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/521c96fd04b0ea93034db8715eda5a4de27a58bb/icons/haskell.svg" width="32"> [djan.world](https://github.com/djanatyn/djan.world)
  - Personal blog and website. Content is formatted as [CommonMark](https://commonmark.org/) with [KDL](https://kdl.dev) frontmatter. The site is generated via a Haskell program, and the build is configured with Nix flakes.
## <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/521c96fd04b0ea93034db8715eda5a4de27a58bb/icons/haskell.svg" width="32"> [huffman-coding](https://github.com/djanatyn/huffman-coding)
  - Haskell implementation of Huffman coding using GHC2021, no libraries except `base`.
## <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/521c96fd04b0ea93034db8715eda5a4de27a58bb/icons/rust.svg" width="32"> [netplay-bracker-finder](https://github.com/netplay-bracket-finder/netplay-bracket-finder) ([netplay.djan.world](https://netplay.djan.world))
  - Rust backend scrapes smash.gg API using GraphQL, pulling in upcoming Melee netplay tournaments with open registration
  - Web frontend exposes information, allowing filtering and sorting
  - Website is hosted using GitHub Pages, updated every 15 minutes using GitHub Actions
## <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/521c96fd04b0ea93034db8715eda5a4de27a58bb/icons/rust.svg" width="32"> [lodestone-seer](https://github.com/djanatyn/lodestone-seer)
  - Daemon running in the background, fetching information from the Final Fantasy Lodestone database periodically, and saving it to a database (recording the history of your character progression over time).
  - Exploring exposing metrics to be gathered with Prometheus, visualizing character stat progression on a Grafana dashboard.
