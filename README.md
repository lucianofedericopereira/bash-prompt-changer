# Bash Prompt Changer

**Bash Prompt Showcase Changer** is a small script designed to customize and rotate your terminal bash prompts from a curated gallery of themes. This repository provides an array of visually appealing and functional bash prompts, allowing users to switch and showcase different styles with ease.

**Features:**
- Comprehensive collection of bash prompt themes.
- Easy-to-use script for changing prompts.
- Automatic prompt rotation functionality.
- Customization options to suit personal preferences.
- Enhance your CLI experience with dynamic and unique prompts.

Whether you're looking to make your terminal aesthetically pleasing or seeking productivity-enhancing prompt features, the Bash Prompt Showcase Changer has got you covered!

```bash
#!/bin/bash
SCRIPT_DIR=$( cd -- "$( dirname -- "${BASH_SOURCE[0]}" )" &> /dev/null && pwd )
clear
random=$(shuf -i 0-4 -n 1)
prompt=("digdug" "invaders" "pacman" "rally" "tanks")
bash "${SCRIPT_DIR}/${prompt[$random]}"
```

## Gallery

### Dig Dug

![Dig Dug](/images/digdug.png)

Adapted from: **thevdude**

Source: **http://crunchbang.org/forums/viewtopic.php?pid=144700#p144700**

### Invaders

![Invaders](/images/invaders.png)

Adapted from: **lolilolicon**

Source: **http://crunchbanglinux.org/forums/post/126921/#p126921**

### PacMan

![PacMan](/images/pacman.png)

Adapted from: **pfh**

Source: **http://crunchbang.org/forums/viewtopic.php?pid=144481#p144481**

### Rally

![Rally](/images/rally.png)

Adapted from: **pfh**

Source: **http://crunchbang.org/forums/viewtopic.php?pid=143700#p143700**

### Tanks

![Tanks](/images/tanks.png)

Adapted from: **muzieca**

Source: **http://crunchbang.org/forums/viewtopic.php?pid=127023#p127023**


### Other Credits:

- **lolilolicon** Use initializing mod from Archlinux. 
- **Derek Taylor** Gallery Source **https://gitlab.com/dwt1/shell-color-scripts**
