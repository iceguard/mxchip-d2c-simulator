# MXChip D2C Simulator

## Usage

Set `connectionString` in `SimulatedDevice.js` to connection string for the device named `simulated`.
Set interval time in `SimulatedDevice.js` (currently one msg per second).

Install project

	npm install

Run simulator

	node SimulatedDevice.js


### Connection String

Go to [igss-iothub - IoT Devices](https://portal.azure.com/#@azurelabor.onmicrosoft.com/resource/subscriptions/7b28371c-4617-4404-a09a-cea628704705/resourceGroups/igss-iot-backend-rg/providers/Microsoft.Devices/IotHubs/igss-iothub/DeviceExplorer) and open device `simulated`.

Use the connection string primary which looks like

	HostName=igss-iothub.azure-devices.net;DeviceId=simulated;SharedAccessKey=<accessKey>
