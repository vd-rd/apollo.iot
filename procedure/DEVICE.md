## Device lifecycle
All devices must pass analog hardware tests. After that the firmware will be loaded and the the device will be registered with the system if the debug firmware passest the tests. At this point the production firmware will be loaded and the device will go in an unprovisioned state, ready to be used. The provisioning will mark the device as active and data will be recorded in the system.

### Steps overview
 * Analog test - after assembly device will be powered up and testpoints will be checked for proper voltages
 * Debug firmware - compliance checking firmware that will loop the devices present and check for comms on interfaces
 * Production firmware - desired app is loaded on the device and is ready to be provisioned.
 * Provisioning - The user associates the device with his account and the system will process data from/to device
 
