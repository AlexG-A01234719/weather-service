# weather-service
## a basic weather fetching service


The `weather-service` folder will contain the following files:
- README.md
- weather
- weathers.service
- weathers.timer


To run the script immediately, simply execute the bash script `weather`.
Upon execution, it will create the file `wttr` in the `weather-service` directory.
Use `cat wttr` to view the weather report!

In order to add the script as a service that runs on an hourly timer, perform the following actions:
1. sudo cp weathers.service weathers.timer /etc/systemd/system
2. sudo systemctl daemon-reload


That is it! Now you have functioning weather report generator service running every hour.
