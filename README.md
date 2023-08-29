# EventVibe
Event-based camera recordings of Compressor Vibrations 

This dataset contains recordings of two different compressors. These recordings are collected with the intent of having a 'ground truth' rotational frequency, which can be used to ensure developed algorithims are working correctly. The collection of similar recordings from an old and new compressor was completed to allow for analysis between the new and old compressors, and to see if the goal of identifying vibrational anomalies between two identical compressors could be achieved.

recordings were collected using metavision studio with a Prophesee gen 4.2 camera. data was collected in .raw format, https://github.com/neuromorphic-paris/command_line_tools was used to convert the .raw files to .es files.

the 'BOLT' recordings are of a flag which is a 4mm cap screw atop the compressor piston.

the 'CAM' recordings are of the compressor rotational assembly, camshaft.

the 'Rainmaker' and 'Spectrogram' images were obtained using the https://github.com/neuromorphic-paris/command_line_tools  provided by A.Marcireau.

'perpixel_fft' & 'centroid_fft' were created using https://github.com/RobPatto93/Vibratio by R.Patterson


