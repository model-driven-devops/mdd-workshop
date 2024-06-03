# Initial Setup

This workshop is designed to work with Visual Studio Code and the Cisco NSO DevNet sandbox that we've reserved for you.

## Steps
1. Open SecureClient (AnyConnect) on your laptop and type in the URL that's given on your laptop. Then enter your username/password. Click Connect.

1. Open Visual Studio Code and click the green "Open a Remote Window" button in the bottom left corner then choose "Connect to Host...".  Select "+ Add New SSH Host..." from the list and enter the command to access the DevBox and then press return.
    ```
    ssh developer@10.10.20.50
    ```

1. Click the green "Open a Remote Window" button in the bottom left corner, choose "Connect to Host..." and select 10.10.20.50 from the list.  When prompted, enter the DevBox password.
   
1. Click "Open" and click on the "mdd-workshop" folder to open.

1. Open a new terminal in Visual Studio Code using the Terminal menu (or CTRL-` if you like shortcuts). All future commands for this workshop should be executed in this terminal.

1. Activate the Virtual Python environment we've pre-configured.
    ```
    source venv/bin/activate
    ```

1. Source the `envvars` file.
    ```
    source envvars
    ```


That's it! Your environment should be properly setup and you are ready to start your journey with Model-Driven DevOps.

[Home](../README.md#workshop-exercises) | [Previous](../README.md#workshop-exercises) | [Next](exploring-topology.md#exploring-the-topology)
