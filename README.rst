This repository is an extension of CityFlow with CO2 emission estimation models used in FAirLight RL-based traffic signal controller model.

Installation
-----

Please build this version of CityFlow from this source code


CityFlow has little dependencies, so building from source is not scary.

Check that you have python 3 installed. Other version of python might work, however, we only tested on python with version >= 3.5.
Install cpp dependencies

  ```sh
  sudo apt update && sudo apt install -y build-essential cmake
  ```

Clone CityFlow project from github.

  ```sh
  git clone https://github.com/ammarhydr/CityFlowEmission.git
  ```

Go to CityFlowEmission root directory and run

  ```sh
  pip install .
  ```

Wait for installation to complete and CityFlow should be successfully installed.

  ```sh
  import cityflow
  eng = cityflow.Engine
  ```
