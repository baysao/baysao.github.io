# Unity

Error:

> Couldn't open /opt/Unity/Editor/Data/UnityExtensions/Unity/VR/Android/AudioPluginOculusSpatializer.so, error
>
> /opt/Unity/Editor/Data/UnityExtensions/Unity/VR/Android/AudioPluginOculusSpatializer.so: wrong ELF class: ELFCLASS32

Solution:

> cd /opt/Unity/Editor/Data/UnityExtensions/Unity/VR/Android
>
> mv AudioPluginOculusSpatializer.so AudioPluginOculusSpatializer.ignore



