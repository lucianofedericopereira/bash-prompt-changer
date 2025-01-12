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

### Gallery

#### Dig Dug

![Dig Dug](/images/digdug.png)

#### Invaders

![Dig Dug](/images/invaders.png)

#### PacMan

![PacMan](/images/pacman.png)

#### Rally

![Rally](/images/rally.png)

#### Tanks

![Tanks](/images/tanks.png)
