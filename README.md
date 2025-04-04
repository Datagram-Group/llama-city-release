- Download the appropriate version. Don't forget to download and configure the `config.yaml` file.

- Launch the application with a config:

    - For the `config.yaml` file located in the same directory as the application, use the command `./llama-city` to launch the application.

    - For the `config.yaml` file located in a different directory from the application, use the command `./llama-city -config path/config.yaml` to launch the application.

    - Note: It is recommended to use the `config.yaml` file placed in the same directory as the application.

- Stop and restart the application:

    - To stop the application, use the command: `./llama-city -cmd stop`
    
    - To restart the application, use the command: `./llama-city -cmd restart`

- Check the application health:

    - To check the health of the application, use the command: `curl your_domain:port/api/up`

    - Note: `your_domain` is the IP or domain of the server, and similarly for `port`. These are configured in the `HTTPServer` section of the `config.yaml` file.
