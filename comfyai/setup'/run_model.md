##### \*\*\* Load **workflow \*\*\***



1. keep workflow at "**C:\\Users\\Piyush Kumar\\AppData\\Local\\Comfy-Desktop\\ComfyUI-Installs\\ComfyUI\\ComfyUI\\user\\default\\workflows**"
2. use **menu** -> **file** -> **new** to load workload from file explorer





##### \*\*\*\* Load model with **.gguf** extension7 \*\*\*



1\) Install **ComfyUI-GGUF** using **ComfyUI Manager** or **extension** (**menu -> extension**), then restart ComfyUI.



2\) Put the **.gguf** model file in **ComfyUI/models/unet/**.



3\) **Double-click** an empty area on the canvas to open node search.



4\) Type **Unet Loader (GGUF)** and select it. In some versions, it may appear as **Unet Loader GGUF** under the **bootleg category**.



5\) On the new node, click the model dropdown and choose your **.gguf file**.





##### \*\*\* Load model with **.safetensors** extension \*\*\*



1. put the **.safetensors** model file is in **ComfyUI/models/diffusion\_models/**



2\. **Double-click** an empty area on the canvas to open node search.



3\. Type **Load Diffusion Model (safetensors)** and select it.







##### \*\*\* Load **VAE** with **.safetensors** extension \*\*\*



1\. **Download** **vae** for the vae encoder and decoder and place it in **ComfyUI/models/vae/**





##### \*\*\* Load **Text Encoder** with **.gguf** extension \*\*\*



1\. **Downlaod** **text encoder** and place it to **ComfyUI/models/clip** or **ComfyUI/models/clip\_gguf/.**





##### \*\*\* Load **Text Encoder** with **.safetensors** extension \*\*\*



1\. **Downlaod** **text encoder** and place it to **ComfyUI/models/text\_encoders**





