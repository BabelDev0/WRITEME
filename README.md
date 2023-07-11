<p align="center">
    <h1 align="center">
        ✍️ writeme
    </h1>
    <p align="center"> Cross-platform Auto-generate README.md for dev projects</p>
</p>

**writeme** is a project designed to simplify the process of creating a comprehensive **README.md** file for software development projects.
The primary purpose of writeme is to automatically extract relevant information from your project and generate for you a well-formatted README.md file that includes important details such as project name, description, repository name, usage and configuration steps, funding details, and collaborators.

writeme primarily extracts information from the project's configuration file. The specific type of configuration file depends on the project, but popular examples include **Cargo.toml**, **package.json**, **composer.json**, and others. To get the best from writeme, take a look at your configuration files

# Table of Contents
- [Table of Contents](#table-of-contents)
  - [⚙️ Configuration ](#️-configuration-)
  - [⬇️ Installation ](#️-installation-)
    - [Cargo](#cargo)
    - [Homebrew](#homebrew)
  - [🎈 Usage ](#-usage-)
- [📄 License ](#-license-)
- [✍️ Authors ](#️-authors-)

## ⚙️ Configuration <a name="configuration"></a>
If you choose to install the application using cargo, make sure you have the rust toolchain installed on your machine. You can find the installation instructions [here](https://www.rust-lang.org/tools/install).


## ⬇️ Installation <a name="installation"></a>
### Cargo
```bash
cargo install writeme
```

### Homebrew
```bash
brew tap writeme-project/writeme  && brew install writeme
```

## 🎈 Usage <a name="usage"></a>
As simple as writing:

```bash
writeme 
```
or to select a different path
```bash
writeme --path 'path/to/your/project'
```

Use `writeme --help` to see all the available options.
# 📄 License <a name="license"></a>
<a href="https://github.com/writeme-project/writeme.git/blob/master/LICENSE" target="_blank">
    GNU General Public License
</a>

# ✍️ Authors <a name = "authors"></a>
<div style="display: flex; justify-content: center;">
  <a href="https://github.com/writeme-project/writeme/graphs/contributors" target="_blank">
    <img alt="contrib.rocks image" src="https://contrib.rocks/image?repo=writeme-project/writeme" />
  </a>
</div>

<p align="center">
auto-generated by <a href="https://github.com/writeme-project/writeme">writeme</a>
</p>