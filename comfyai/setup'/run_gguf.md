1\) Install **ComfyUI-GGUF** using ComfyUI Manager or extension (**menu -> extension**), then restart ComfyUI.



2\) Put the **.gguf** model file in **ComfyUI/models/unet/**.



3\) Double-click an empty area on the canvas to open node search.



4\) Type **Unet Loader (GGUF)** and select it. In some versions, it may appear as Unet Loader GGUF under the bootleg category.



5\) On the new node, click the model dropdown and choose your **.gguf file**. 



6\) **download** **vae** for the vae encoder and decoder and place it in **ComfyUI/models/clip/**



7\) **downlaod** **text encoder** and place it to **ComfyUI/models/vae/**



8\) use **vae loader , text encoder** loader.

