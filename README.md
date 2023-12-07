# DailyReward - Minecraft Spigot/Paper Plugin

## Introduction

Give everyone 1 - 5 random items as reward when they first login everyday. :)

For ```Minecraft version 1.20``` and works perfectly on my ```1.20.2 Paper Server```. It should work just fine on newer
versions as well.

## Usage

Download the Jar Plugin from Release, put it into your Spigot / Paper server's `````./Plugins````` folder, restart your
server and good to go.

## Config

The default config is in ```./src/main/resources/config.yml```, remember to use all lowercase item-id.
the example config is below:

```yaml
# This is the example, see the default list in 'src/main/resources/config.yml'
ban-items: [
  # Item-ID you don't want to appear on the reward
  # In all lowercase
  command_block_minecart,
  recovery_compass
]
```

## Compile

This is a maven project made in intellij idea. To compile, simply run mvn package. The output JAR will be located
in ```./target``` folder.