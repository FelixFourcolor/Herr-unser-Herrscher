# Herr, unser Herrscher
"Herr, unser Herrscher" in Bach's St. John Passion, arranged for Minecraft's noteblocks.

Recording: https://www.youtube.com/watch?v=pvM6F4RrCoU

## Arrangement
Instrumentation:
* Soprano: bit
* Alto: bit
* Tenor: guitar
* Bass: guitar
* Flute I & II: flute
* Oboe I & II (double flute I & II) are omitted
* Violin I & II, viola: harp
* Continuo: bass

Tranposed down one semitone to better fit noteblock's ranges (or you can argue it's baroque tuning, effectively the same thing). However, a few notes still do not fit, then they are either transposed up/down an octave or played by a different instrument, depending on which sounds better to me.

## Play requirements
Minecraft java 1.19+.

Go to Music & Sounds settings and turn on Directional Audio. Optionally, turn down Master Volume to about 50% to 60%, otherwise it might be a bit too loud (but of course this depends on your speakers).

## Easy install 
Copy the [World](https://github.com/FelixFourcolor/Herr-unser-Herrscher/tree/main/World) folder into your saves.

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10+
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator). The program takes [src](https://github.com/FelixFourcolor/Herr-unser-Herrscher/tree/main/src) which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install the lastest version of [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator):
    ```
    pip install --upgrade noteblock-generator
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain [src](https://github.com/FelixFourcolor/Herr-unser-Herrscher/tree/main/src). You may clone the repo or download just that folder.

3. Obtain a world in Minecraft java 1.19+. You may use your existing world or create a new one.

4. If you are inside the world, exit it first. Then,
    ```
    noteblock-generator [path to src] [path to minecraft world]
    ```

    (See [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator)'s documentation for explanation and more build options.)

## License
While Minecraft remains Mojang's property and is subjected to their terms of service, the source code used to generate this structure is given to the public domain. You are free to do whatever you want with it, as long as it complies with Minecraft's terms of service, without any restrictions from my end.

See [LICENSE](https://github.com/FelixFourcolor/Herr-unser-Herrscher/blob/main/LICENSE) for more details.