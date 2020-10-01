## MONTHLY BITWIG COMMUNITY PRESET COMPILATION

It's time for the community to come together to make some awesome sounds/effects.

At the end of each month, all presets will be compiled for download. Everyone will be able to vote on their favorite preset from each month, to incentivize people to do their best. The idea is to get more people into making presets and to make it easier for everyone to discover new presets.

Join our [Bitwig discord for more informations, talk & help](https://discord.gg/0g2ZPafIN3eWParf)

## INSTALLATION

Here are 3 different ways to install the presets.

1. Copy the contents of this repository into

    - `%userprofile%\Documents\Bitwig Studio\Library\Presets` on Windows
    - `~/Documents/Bitwig Studio/Library/Presets/` on Mac
    - `~/Documents/Bitwig Studio/Library/Presets/` on Linux

2. Use a symlink that points to the cloned repository
    - On linux/mac:
        ```sh
        $ git clone https://github.com/polarity/bitwig-presets.git
        $ cd bitwig-presets
        $ ln -s "$PWD" "~/Documents/Bitwig Studio/Library/Presets/Monthly-Competition"
        ```
    - On windows, open the [command prompt as administrator](https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/) and then:
        ```sh
        cd %userprofile%\Documents\Bitwig Studio\Library\Presets
        mklink /D monthly-preset-competition <path_of_the_cloned_repository>
        ```
3. Use the [companion app (alpha)](https://github.com/polarity/preset-party-app) that syncs the repo into your bitwig preset folder

### RULES : ### 

1. Single instruments with nested devices must be submitted as an instrument preset, layered instruments as a instrument layer/selector device preset, drum machines as a drum machine preset, Effect chains as a Chain or Effect Selector preset. 

2. Keep modulators that will break the preset separated in the modulation grid from modulators you can mess around with (For using math for example.) 

3. Name your preset something appropriate! Fill out preset creator, category, tags and description (if so required). USE TAGS: YEAR, MONTH (f.example "2018" and "february" for this month)

4. Only native devices are allowed. All content from official Packages is allowed. 

5. Maximum 3 submissions per month. You can delete/replace them as much as you like before the deadline. 3 variations of the same preset counts as 3 different presets. 

6. By submitting presets to this compilation, you are allowing for others to use them for their own music. 

7. Presets made before the month are allowed if they haven't been submitted before. Do not submit slight variations of presets submitted in previous months, unless you want to fix or update something. In that case use the same name and metadata so it gets overwritten.

8. Only original presets allowed, but you can include other's presets in your chain. Slight variations to official bitwig presets are not allowed.

9. No beta presets (just incase they break). Only presets saved in non-beta versions are allowed.

10. Samples for sampler presets must be saved within the .bwpreset file (this should be ticked off when saving the preset https://puu.sh/zmpqe/381f7f3011.png), unless they use samples from bitwig packages. Don't use samples you don't have the rights to distribute!!

Submissions can be posted in the discord channel (https://discord.gg/ryNHwnx). Have fun!

## More
I separated all my music goodies into different repositories:
- 🔥 [Bitwig Presets by Polarity](https://github.com/polarity/polarity-music-tools) - My free to use Bitwig presets (updated regulary)
- 📋 [Bitwig Projects by Polarity](https://github.com/polarity/bitwig-projects) - My free to use Bitwig projects
- 💽 [Bitwig Artist Collection](https://github.com/polarity/bitwig-artist-collection) - My official Bitwig 2.0 package
- ❤️ [Bitwig Community Presets](https://github.com/polarity/bitwig-community-presets) - presets collected from the bitwig discord
- 🎹 [Bitwig Pianobook](https://github.com/polarity/bitwig-pianobook) - different pianos sampled as bitwig presets
