# Herr, unser Herrscher
"Herr, unser Herrscher" in Bach's St. John Passion, arranged for Minecraft's noteblocks.

## Arrangement
Tuning: A = 415 Hz (effectively equivalent to transposing down one semitone). 

Instrumentation:
* Soprano: bit
* Alto: bit
* Tenor: guitar
* Bass: guitar
* Violin, viola: harp
* Woodwind: flute
* Continuo: bass

## Play requirement
Minecraft java 1.18+

## Easy install 
Copy the `World` folder into your saves.

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10+
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator). The program takes `src` which define the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install the lastest version of [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator):
    ```
    pip install --upgrade noteblock-generator
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain `src`. You may clone the repo or download just that folder.

3. Obtain a world in Minecraft java 1.18+. You may use your existing world or create a new one. 

4. If you are inside the world, exit it first. Then,
    ```
    noteblock-generator --clear [path to src] [path to minecraft world]
    ```

    (See [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator)'s documentation for explanation and more build options.)

## License
Do whatever you want.