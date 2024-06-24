# CheaPad Project Summary

The CheaPad project aims to make Klipper pad solutions accessible to all 3D printing enthusiasts by offering a cost-efficient and community-driven alternative. With its minimalist design and emphasis on functionality, the CheaPad opens up new possibilities for enhancing your 3D printing experience.

Join the CheaPad community today, and together, let's revolutionize the world of Klipper pads!

## Introduction
The CheaPad is a community-driven initiative aimed at creating an affordable and functional Klipper pad solution. By utilizing the BTT Pi and TFT35 SPI as its base, the CheaPad offers seamless integration with existing 3D printer setups.

As a DIY project, you can download the printable files to build the case here : https://www.printables.com/fr/model/499763-the-cheapad-btt-pi-tft35-spi-the-cheapest-klipper-

## Key Features
- **Cost-Efficient:** The CheaPad provides a cost-effective alternative to other Klipper pads on the market, allowing enthusiasts to enhance their printing experience without breaking the bank.
- **Minimalist Design:** With a minimalist design approach, the CheaPad offers a compact and space-saving solution for your 3D printer setup.
- **Community-Driven:** The project emphasizes community collaboration and encourages users to modify and suggest improvements to the design. Step and f3d files are available for customization.
- **Functionality First:** While the primary focus of the CheaPad is functionality, it still offers a reliable and efficient performance, even though it may not prioritize aesthetics.

## How Does It Works ?
1. **Select the Corresponding Configuration File:** Choose the configuration file from the CheaPad project repository that corresponds to your specific printer model. These opinionated configuration files serve as a starting point for your setup.

2. **Replace the printer.cfg File:** Once you have identified the appropriate configuration file for your printer, replace the existing "printer.cfg" file in your Klipper firmware with the one you copied from the CheaPad project repository. This file contains the specific settings and parameters for your printer.

3. **Flash Klipper to the Printer:** After updating the "printer.cfg" file, you need to flash the modified Klipper firmware onto your printer's control board. This process involves transferring the updated firmware to your printer, replacing the previous firmware, and enabling the new configuration.

By following these steps, you can effectively integrate the CheaPad configuration into your printer setup and take advantage of the optimized settings provided. Remember that these configuration files serve as a starting point and require further customization and calibration to achieve optimal performance with your specific printer model.

## Important Considerations
Additionally, the CheaPad project's GitHub repository includes opinionated configuration files tailored to specific printers. It's important to note that these files are not readily usable as they require adaptation and customization. Users will need to perform essential calibrations and adjustments to achieve optimal results with their specific printer models. The following calibrations and adjustments should be considered and addressed: 

1. **PID Tuning:** Fine-tuning the Proportional-Integral-Derivative (PID) settings is crucial for achieving stable and accurate temperature control.
2. **Extruder Calibration:** Calibration of the extruder steps per millimeter ensures precise filament feeding and accurate extrusion.
3. **Z_Offset Calibration:** Adjusting the Z-offset ensures proper nozzle-to-bed distance for successful and consistent first layers.
4. **Pressure Advance:** Configuring the pressure advance setting helps mitigate oozing and improve the overall print quality, especially for sharp corners and sudden changes in print direction.
5. **Resonance Compensation:** Addressing resonance issues by adjusting acceleration and jerk settings can minimize artifacts and improve print quality.

It is essential for users to understand that these configuration files serve as a starting point and require fine-tuning to match their specific printer's characteristics and requirements. By adapting and performing the necessary calibrations and adjustments, users can optimize their printing experience with the CheaPad and achieve excellent results.

## How to Get Involved
1. **Utilize the CheaPad:** Download the provided files and implement the CheaPad design into your 3D printer setup.
2. **Customize and Remix:** Modify the design according to your preferences and experiment with different variations.
3. **Contribute and Share:** Share your modifications and improvements with the community, fostering collaboration and innovation.
