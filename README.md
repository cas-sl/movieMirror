# MovieMirror

## Pre-install
Before you go ahead and install this project. Be aware that movies that will be reflected back by the 'mirror' will have to be supplied by the user. Secondly, a dataset of poses in the scenes of the movies will need to be generated and inserted into a MongoDB database. Without these steps, the 'mirror' has nothing to reflect.
The user needs a webcam connected to the pc for the application to analyse.
For further, in depth, reading of the technical side of this project, please go to [Technisch Verslag](docs/technisch_verslag.md) (In Dutch)

## How to install

Clone this repo into the desired directory
```cmd
cd desired/location/of/project
git clone https://github.com/cas-sl/movieMirror
```

Change directory to the repo just cloned
```cmd
cd movieMirror
```

And install dependencies
```cmd
yarn
```

Build the disttribute folder that electron will run from source by running
```cmd
yarn run pack
```

It will keep watching for changes in source.
When the build is succesful, start up a second terminal and run
```cmd
yarn start
```
To start up electron. 

## Documentation
Please go [here](https://cas-sl.github.io/movieMirror/) for documentation regarding the source code.

