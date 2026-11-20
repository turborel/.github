<p align="center">
  <a href="https://turborel.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/turborel/turborel/main/artwork/turborel-logo-white.svg">
      <img src="https://raw.githubusercontent.com/turborel/turborel/main/artwork/turborel-logo.svg" alt="Turborel" width="320">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://turborel.com">Website</a> ·
  <a href="https://turborel.com/docs/">Docs</a> ·
  <a href="https://turborel.com/ecosystem/">Ecosystem</a> ·
  <a href="https://turborel.com/blog/">Blog</a> ·
  <a href="https://github.com/turborel/turborel/releases/tag/nightly">Nightly</a>
</p>

<p align="center">
  <a href="https://discord.gg/Fkf3ST2YPP"><img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white"></a>
  <a href="https://x.com/turborel"><img alt="X" src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white"></a>
  <a href="https://www.linkedin.com/company/turborel"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://www.reddit.com/r/turborel"><img alt="Reddit" src="https://img.shields.io/badge/Reddit-FF4500?style=flat-square&logo=reddit&logoColor=white"></a>
  <a href="https://www.youtube.com/@turborel"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white"></a>
  <a href="https://www.facebook.com/turborel"><img alt="Facebook" src="https://img.shields.io/badge/Facebook-0866FF?style=flat-square&logo=facebook&logoColor=white"></a>
  <a href="https://forms.gle/YNJ5YGpBTFW9vvTj8"><img alt="Newsletter" src="https://img.shields.io/badge/Newsletter-E58A5C?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

---

Turborel (TUR-boh-rel) is an open-source relational database in
Rust, designed for high performance and a small footprint, with broad
compatibility across the modern ecosystem. It isn't a fork of another
database.

- Standard SQL as one language, from SQL-86 through SQL:2023.
- Tables, graphs, vectors, JSON, XML, spatial and full-text search in
  one database, under the same transactions.
- Row or columnar storage, chosen per table.
- Extensible throughout storage engines, index methods, types,
  functions, optimizer rules and more are plug-ins you can replace or add
  to.
- Embedded or distributed where a library in your Rust app, or the
  `turboreld` server, replicated with Viewstamped Replication.

> Turborel is in alpha. Anything may change from one build to the next.
> Try the [nightly build](https://github.com/turborel/turborel/releases/tag/nightly)
> for Linux, macOS or Windows, or the container image:
>
> ```
> docker pull ghcr.io/turborel/turborel:nightly
> ```

## Repositories

**The database**

| Repository | About |
|---|---|
| [**turborel**](https://github.com/turborel/turborel) | The server, `turboreld`, the CLI, `turborel`, and the Rust library |
| [**studio**](https://github.com/turborel/studio) | Query, model, tune, administer Turborel from one desktop app. |

**Drivers**, released together with the server

| Language | Repository | Docs |
|---|---|---|
| <img alt="" height="20" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000000"> | [turborel-js](https://github.com/turborel/turborel-js) | [docs](https://turborel.com/docs/drivers/javascript/) |
| <img alt="" height="20" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=FFFFFF"> | [turborel-py](https://github.com/turborel/turborel-py) | [docs](https://turborel.com/docs/drivers/python/) |
| <img alt="" height="20" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=FFFFFF"> | [turborel-go](https://github.com/turborel/turborel-go) | [docs](https://turborel.com/docs/drivers/go/) |
| <img alt="" height="20" src="https://img.shields.io/badge/Java-B07219?style=flat-square&logo=openjdk&logoColor=FFFFFF"> | [turborel-java](https://github.com/turborel/turborel-java) | [docs](https://turborel.com/docs/drivers/java/) |
| <img alt="" height="20" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=FFFFFF"> | [turborel-cs](https://github.com/turborel/turborel-cs) | [docs](https://turborel.com/docs/drivers/csharp/) |
| <img alt="" height="20" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=FFFFFF"> | [turborel-cpp](https://github.com/turborel/turborel-cpp) | [docs](https://turborel.com/docs/drivers/cpp/) |
| <img alt="" height="20" src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=000000"> | [turborel-c](https://github.com/turborel/turborel-c) | [docs](https://turborel.com/docs/drivers/c/) |
| <img alt="" height="20" src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=FFFFFF"> | [turborel-php](https://github.com/turborel/turborel-php) | [docs](https://turborel.com/docs/drivers/php/) |
| <img alt="" height="20" src="https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=FFFFFF"> | [turborel-ruby](https://github.com/turborel/turborel-ruby) | [docs](https://turborel.com/docs/drivers/ruby/) |

**Running it**

| Repository | About |
|---|---|
| [**charts**](https://github.com/turborel/charts) | Helm charts, at [charts.turborel.com](https://charts.turborel.com/) |
| [**turborel-operator**](https://github.com/turborel/turborel-operator) | A Kubernetes operator for Turborel |

**Benchmarks**: Turborel's forks of standard tools

| Repository | About |
|---|---|
| [**sysbench**](https://github.com/turborel/sysbench) | Scriptable database and system benchmarks |
| [**HammerDB**](https://github.com/turborel/HammerDB) | TPROC-C and TPROC-H, derived from TPC-C and TPC-H |

**The website**: [turborel.github.io](https://github.com/turborel/turborel.github.io)
builds [turborel.com](https://turborel.com).

## Get involved

Join on [Discord](https://discord.gg/Fkf3ST2YPP), and get
release news by [newsletter](https://forms.gle/YNJ5YGpBTFW9vvTj8) or on Turborel's blog.

Contributions are welcome. 

<sub>Open source under the BSD-2-Clause Plus Patent License. © Turborel Inc.</sub>
