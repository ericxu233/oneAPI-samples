# oneAPI Samplesssss

The oneAPI-samples repository contains samples for the [Intel® oneAPI Toolkits](https://www.intel.com/content/www/us/en/developer/tools/oneapi/toolkits.html).

**The latest versions of code samples on the master branch are not guaranteed to be stable.** Use a [stable release version](https://github.com/oneapi-src/oneAPI-samples/tags) of the repository.

## Get the oneAPI Samples

The version of the repository you use should match the version of the Intel® oneAPI Toolkit you have installed, particularly for the compilers.

Clone a stable version of the repository using Git by entering a command similar to the following:

`git clone -b <tag> https://github.com/oneapi-src/oneAPI-samples.git`

where `<tag>` is the stable version number, like **2023.0.0**.

Alternatively, you can download a zip file containing a stable version of the repository.

1. Select the appropriate tag.
2. Click the **Code** button.
3. Select **Download ZIP** from the menu options.
4. After downloading the file, unzip the repository contents.

### Getting Started with oneAPI Samples

The best oneAPI sample to start with depends on what you are trying to learn or types of problems you are trying to solve.

| If you want to learn about...                                                        | Start with...
|:---                                                                                  |:---
| the basics of writing, compiling, and building programs for CPUs, GPUs, or FPGAs     |[Simple Add](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL/DenseLinearAlgebra/simple-add) or [Vector Add](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL/DenseLinearAlgebra/vector-add) samples <br> (You can use these samples as starter projects by removing unwanted elements and adding your code and build requirements.)
| the basics of using artificial intelligence                                          | [Getting Started Samples for Intel® AI Analytics Toolkit (AI Kit)](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Getting-Started-Samples)
| the basics of image rendering workloads and ray tracing                              | [Getting Started Samples for Intel® oneAPI Rendering Toolkit (Render Kit)](https://github.com/oneapi-src/oneAPI-samples/tree/master/RenderingToolkit/GettingStarted)
| how to modify or create build files for SYCL-compliant projects                      | [Vector Add](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL/DenseLinearAlgebra/vector-add) sample

>**Note**: The README.md included with each samples provides build instructions for all supported operating system. For samples run in Jupyter Notebooks, you might need to install or configure additional frameworks or package managers if you do not already have them on your system.

### Using Integrated Development Environments (IDE)

If you prefer to use an Integrated Development Environment (IDE) with these samples, you can download [Visual Studio Code](https://code.visualstudio.com/download) for use on Windows*, Linux*, and macOS*.

## Repository Structure

The oneAPI-sample repository is organized by high-level categories.

- [AI-and-Analytics](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics)
  - [End-to-End-Workloads](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/End-to-end-Workloads)
  - [Features-and-Functionality](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Features-and-Functionality)
  - [Getting-Started-Samples](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Getting-Started-Samples)
  - [Jupyter](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Jupyter)
- [DirectProgramming](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming)
  - [C++](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++)
  - [C++SYCL](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL)
  - [C++SYCL_FPGA](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL_FPGA)
  - [Fortran](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/Fortran)
- [Libraries](https://github.com/oneapi-src/oneAPI-samples/tree/master/Libraries)
- [Publications](https://github.com/oneapi-src/oneAPI-samples/tree/master/Publications)
- [RenderingToolkit](https://github.com/oneapi-src/oneAPI-samples/tree/master/RenderingToolkit)
- [Tools](https://github.com/oneapi-src/oneAPI-samples/tree/master/Tools/)

## Known Issues and Limitations

### Windows

- If you are using Microsoft Visual Studio* 2019, you must use Microsoft Visual Studio 2019 version 16.4.0 or newer.
- Windows support for the FPGA code samples is limited to the **FPGA emulator** and **optimization reports**. Only Linux supports **FPGA hardware** compilation. See any FPGA code sample README.md for more details.
- If you encounter `Error MSB6003 The specified task executable ... could not be run...` when building a sample program, it might be due to the length of the directory path. Move the `build` directory to a location with a shorter path. Build the sample in the new location.

## Licenses

Code samples are licensed under the MIT license. See [License.txt](https://github.com/oneapi-src/oneAPI-samples/blob/master/License.txt) for details.

Third-party program licenses can be found here: [third-party-programs.txt](https://github.com/oneapi-src/oneAPI-samples/blob/master/third-party-programs.txt).

## Notices and Disclaimers

© Intel Corporation. Intel, the Intel logo, and other Intel marks are trademarks of Intel Corporation or its subsidiaries. Other names and brands may be claimed as the property of others.
