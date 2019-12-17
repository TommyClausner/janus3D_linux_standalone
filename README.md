# janus3D

janus3D is an open source MATLAB toolbox for the purpose of EEG electrode determination and co-registration of 3D head models with individual structural MR images. It features smart selection and automatic texture-based EEG electrode detection, providing highly accurate EEG sensor positions for source reconstruction analyses. It makes use of GUI-based functions allowing the user to obtain sensor positions fast and comfortable. To enhance the actual 3D reconstruction process a tool for automatic background selection and mask creation is included. Electrode cap templates of EEG cap systems that are not included can be created using the implemented ’Template Builder’. This tool allows the creation of individual cap templates that are used for automatic labeling of the EEG electrode positions. janus3D requires MATLAB 2015a (MathWorks), including Image Processing Toolbox (MathWorks), Computer Vision System Toolbox (MathWorks), and Fieltrip Toolbox (Oostenveld, Fries, Maris, & Schoffelen, 2011).

This standalone version of janus3D requires the MATLAB 2015a Runtime library.

Afterwards run `<path/to/janus3D/run_janus3D.sh /path/to/MATLAB_Runtime/v85/>` to launch the program.

This Version was tested on Manjaro Linux
