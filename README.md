# Oddibits KiCad Library

Oddibits is a custom KiCad library containing components and footprints that are not included in the default KiCad distribution. This library extends the standard KiCad libraries with additional components commonly used in electronics projects.

## Directory Structure

### 3dmodels/
Contains 3D model files in STEP format for components. These models can be used for 3D visualization and mechanical integration in KiCad PCB designs.

### footprints/oddibits.pretty/
Contains custom KiCad footprint library files (.kicad_mod) for PCB layout. The `.pretty` directory format is the standard KiCad footprint library structure.

### symbols/
Contains custom KiCad symbol library files (.kicad_sym) for schematic design.

## Available Components

| Component | Type | Category |
|-----------|------|----------|
| SM04B-SRSS-TB (LF)(SN) | Connector | JST SH Connector |
| Texas Instruments MSPM0C1104 | Microcontroller | SOT23-8 Package |

## Installation

### Adding to KiCad

1. Clone or download this repository to your local machine
2. In KiCad, go to Preferences > Manage Symbol Libraries (or Footprint Libraries)
3. Add the path to the appropriate directories in this repository:
   - For symbols: Point to the `symbols/oddibits.kicad_sym` file
   - For footprints: Point to the `footprints/oddibits.pretty/` directory
   - For 3D models: Configure the 3D model search paths in KiCad settings

## Usage

Once installed, the components will be available in KiCad's symbol and footprint libraries. Use them in your schematics and PCB designs as you would with any other library component.

## Contributing

If you have additional components to add or improvements to suggest, please open an issue or submit a pull request.

## License

Please refer to the LICENSE file for licensing information.
