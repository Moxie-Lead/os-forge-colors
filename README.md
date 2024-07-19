![External Libraries SDK](images/odc.png) 
# ODC External Libraries SDK

Please find complete documentation on the OutSystems Developer Cloud (ODC) [product documentation site](https://www.outsystems.com/goto/external-logic-readme).

## COLORS

### Prerequisites

* .NET 6.0 SDK installed.
* An IDE that supports building .NET 6 projects. For example, Visual Studio, Visual Studio Code, and Jet Brains Rider.

### Usage

1. Load the C# project file, `Outsystems.Colors.csproj`, using a supported IDE.

    Files in the project:
    * **ConvertColorNameToHex: Method to convert an inputted color name to the corresponding hexadecimal representation.

    * **FindNearestColor: method to find the nearest color from the inputted color code and set of colors given, using the Euclidean Distance between Two Colors.

    * **FindNearestWebColor: method to find the nearest Web color from the inputted color code, using the Euclidean Distance between two colors.
    
2. Edit the code to meet your use case. 

3. Run the Powershell script `generate_upload_package.ps1` to generate `ExternalLibrary.zip`. Rename as required.

4. Upload the generated ZIP file to the ODC Portal. See the [External Logic feature documentation](https://www.outsystems.com/goto/external-logic) for guidance on how to do this.


