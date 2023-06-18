# Rime Config

## Install Fonts

* [Noto Sans TC](https://fonts.google.com/noto/specimen/Noto+Sans+TC)
* [Noto Sans Mono](https://fonts.google.com/noto/specimen/Noto+Sans+Mono)

## Setup for Onion Rime

1. Clone repo from [Onion Rime (洋蔥注音)](https://github.com/oniondelta/Onion_Rime_Files)
2. In the downloaded folder, execute `sort_rime_file.py` with Python

        ```bash
        python sort_rime_file.py
        ```

3. Copy the generated config files to the Rime data folder

        ```txt
        %APPDATA%\Rime  ( Windows 小狼毫 )
        ~/Library/Rime  ( Mac OS 鼠鬚管 )
        ~/.config/ibus/rime  ( Linux 中州韻 )
        ~/.config/fcitx/rime  ( Linux )
        ~/.local/share/fcitx5/rime ( Linux )
        ```

4. Copy configs from `custom_configs/` to replace the default ones
5. Done
