# Static Site Generator

## Description

This project takes markdown files and converts them static html pages that reference a specific stylesheet to provide a "theme".

### Prerequisites

Python3 
* [Downloading Python](https://wiki.python.org/moin/BeginnersGuide/Download)
  ```sh
  #Red Hat, CentOS, or Fedora
  dnf install python3 python3-devel
  #Debian or Ubuntu
  apt-get install python3 python3-dev
  #Gentoo
  emerge dev-lang/python
  #Arch Linux
  pacman -S python3
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/sudotina/static-site-generator.git
   ```
2. `cd` into directory
   ```sh
   cd static-site-generator
   ```
3. `chmod` and execute `main.sh`
   ```sh
   chmod 755 main.sh
   ./main.sh
   ```
   
## Usage

TODO

## Roadmap

- [ ] Support more markdown syntax
- [ ] Error softly when improper/incomplete markdown
- [ ] Customized themes
    - [ ] Specify theme per page

See the [open issues](https://github.com/sudotina/static-site-generator/issues) for a full list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact

Tina - tina@sajfar.dev
