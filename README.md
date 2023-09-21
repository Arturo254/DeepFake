DeepFake 
==========

 > POR FAVOR USARLO CON RESPONSABILIDAD




Preview
-------
![IMG](https://github.com/Arturo254/DeepFake/assets/87346871/f34b17a3-a2ea-4f39-a568-9e61e92abc58)



Instalación
------------

Ten en cuenta que la instalación requiere habilidades técnicas y no es para principiantes. Por favor, no abras problemas relacionados con la plataforma y la instalación en GitHub. Tenemos una comunidad muy útil en [Discord](https://join.facefusion.io) que te guiará en la instalación de FaceFusion.

Lee la [instalación](https://docs.facefusion.io/installation) ahora.


Uso
----

Ejecuta el siguiente comando:

```
python run.py [options]

-h, --help                                                                                       show this help message and exit
-s SOURCE_PATH, --source SOURCE_PATH                                                             select a source image
-t TARGET_PATH, --target TARGET_PATH                                                             select a target image or video
-o OUTPUT_PATH, --output OUTPUT_PATH                                                             specify the output file or directory
--frame-processors FRAME_PROCESSORS [FRAME_PROCESSORS ...]                                       choose from the available frame processors (choices: face_enhancer, face_swapper, frame_enhancer, ...)
--ui-layouts UI_LAYOUTS [UI_LAYOUTS ...]                                                         choose from the available ui layouts (choices: benchmark, webcam, default, ...)
--keep-fps                                                                                       preserve the frames per second (fps) of the target
--keep-temp                                                                                      retain temporary frames after processing
--skip-audio                                                                                     omit audio from the target
--face-recognition {reference,many}                                                              specify the method for face recognition
--face-analyser-direction {left-right,right-left,top-bottom,bottom-top,small-large,large-small}  specify the direction used for face analysis
--face-analyser-age {child,teen,adult,senior}                                                    specify the age used for face analysis
--face-analyser-gender {male,female}                                                             specify the gender used for face analysis
--reference-face-position REFERENCE_FACE_POSITION                                                specify the position of the reference face
--reference-face-distance REFERENCE_FACE_DISTANCE                                                specify the distance between the reference face and the target face
--reference-frame-number REFERENCE_FRAME_NUMBER                                                  specify the number of the reference frame
--trim-frame-start TRIM_FRAME_START                                                              specify the start frame for extraction
--trim-frame-end TRIM_FRAME_END                                                                  specify the end frame for extraction
--temp-frame-format {jpg,png}                                                                    specify the image format used for frame extraction
--temp-frame-quality [0-100]                                                                     specify the image quality used for frame extraction
--output-image-quality [0-100]                                                                   specify the quality used for the output image
--output-video-encoder {libx264,libx265,libvpx-vp9,h264_nvenc,hevc_nvenc}                        specify the encoder used for the output video
--output-video-quality [0-100]                                                                   specify the quality used for the output video
--max-memory MAX_MEMORY                                                                          specify the maximum amount of ram to be used (in gb)
--execution-providers {cpu} [{cpu} ...]                                                          choose from the available execution providers (choices: cpu, ...)
--execution-thread-count EXECUTION_THREAD_COUNT                                                  specify the number of execution threads
--execution-queue-count EXECUTION_QUEUE_COUNT                                                    specify the number of execution queries
--headless                                                                                       run the program in headless mode
-v, --version                                                                                    show program's version number and exit
```


Disclaimer
----------
Reconocemos el potencial éticamente cuestionable los DeepFakes y estamos firmemente comprometidos a establecer salvaguardias contra su mal uso. Este programa ha sido diseñado para abstenerse de procesar contenido inapropiado, como desnudos, contenido gráfico y material sensible.

Es importante destacar que mantenemos una postura firme en contra de cualquier tipo de contenido pornográfico y no colaboramos con ningún sitio web que promueva el uso no autorizado de nuestro software.

Los usuarios que busquen participar en tales actividades enfrentarán consecuencias, incluyendo ser prohibidos de nuestra comunidad. Nos reservamos el derecho de informar a los desarrolladores en GitHub que distribuyan bifurcaciones no bloqueadas de nuestro software en cualquier momento.

