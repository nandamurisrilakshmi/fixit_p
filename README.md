# fixit_p

The project is reconstructing an object from 2d image and then regenerating missing part.This helps in reducing scrap since we can reair the missing part with just a click of photo.
This project inputs image and uses Point cloud to generate 3d object the Missing part iss detected and a stl file is generated to adjust the dimensions
as per the real object and feed it to 3D printer.
The project is trained for only Chair object
data set used:
Shape net : Rendered images from https://github.com/chrischoy/3D-R2N2
and Point Clouds from object meshes from Shapenet/Chair

The ground truth is generated for point clouds using Variable Auto Encoder and single vie 3D is reconstructed GAN.
