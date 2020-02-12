# gazebo_models
These models are available in the gazebo world.  

![snap](https://github.com/calm0815/gazebo_models/blob/master/snapshot.png)

## usage
Register the file path to "models" in the environment variable before using.

- PATH registration
```
cd models
export GAZEBO_MODEL_PATH=`pwd`:$GAZEBO_MODEL_PATH
```

It's convenient if the model PATH are automatically added to your bash session every time a new shell is launched:
```bash
export GAZEBO_MODEL_PATH="/path/to/models_directory:$GAZEBO_MODEL_PATH"
```
