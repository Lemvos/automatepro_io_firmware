# AutomatePro IO Controller Firmware

This repository contains the firmware for the AutomatePro IO controller. The firmware files are provided in HEX format and can be used to update or restore the firmware on your controller.

## Repository Structure

The file structure of this repository is organized as follows:

```text

├── control_module.hex - Main firmware file. 
├── previous_versions - Directory containing previous versions of the firmware. 
├── LICENSE
└── README.md - This README file with instructions and information.

```

## Firmware File

- `control_module.hex`: This is the main firmware file that you will use to flash the AutomatePro IO controller.

## Flashing Instructions

Follow these steps to flash the firmware to your AutomatePro IO controller:

1. **Download the Firmware:**  
   Download the `control_module.hex` file from this repository.

2. **Flash the Firmware:**  
   Run the following command to flash the firmware:

   ```bash
   flash-mcu /path/to/control_module.hex
   ```

   Replace `/path/to/control_module.hex` with the actual path.

3. **Reboot the AutomatePro**  
   Once the firmware is flashed, reboot the AutomatePro to ensure that the new firmware is fully loaded and operational.

## Previous Versions

The previous_versions directory contains archived versions of the firmware. These are provided for reference and in case a rollback is necessary.

## License

This project is licensed under the terms found in the LICENSE file in this repository. Please refer to this file for full licensing details.

## Support

For support, please contact <support@lemvos.com> with any questions or issues you encounter.
