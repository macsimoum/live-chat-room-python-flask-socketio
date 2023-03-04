# live-chat-room-python-flask-socketio

**Uses Flask Sockets to create a live chat room application.**

# For Windows users# Note: <> denotes changes to be made

# Create a conda environment

```shell
conda create --name <environment-name>
```

# To create a requirements.txt file:

```shell
# Gives you list of packages used for the environment
conda list

# Save all the info about packages to your folder
conda list -e > requirements.txt
```

# To export environment file

```shell
activate <environment-name>
conda env export > <environment-name>.yml
```

# For other person to use the environment

```shell
conda env create -f <environment-name>.yml
```