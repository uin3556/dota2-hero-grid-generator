![Demo](img/demo.gif)

## How To Install

If you want to run from source, ensure that you have Python 3.9.1+ and the `venv` module installed; how to install this depends on your system. Then follow the instructions below.

Windows:
*  `$ git clone https://github.com/uin3556/dota2-hero-grid-generator.git.git`
*  `$ cd dota2-hero-grid-generator`
*  `$ pip install -r requirements.txt`

## How To Use

* Configure `config.json`:
   * Get your own Stratz API token [here](https://stratz.com/api). You just need to log in with your Steam account.
   * Point to the Steam installation directory. Note that this is *not* where Dota is, but where the actual Steam executable resides (e.g. `steam.exe` on Windows).
   * Set up your grids. Take a look [here](config-schema.jsonc) for detailed documentation.

* You'll be informed about which grid(s) were created/updated for which user(s).
* Enjoy!

<sub>Data provided by [STRATZ](https://stratz.com).</sub>
