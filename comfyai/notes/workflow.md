BASIC text to image flow:-

1) text_encoder -> clip_loader (clip)
                -> ksampler(postive,negative)

2) model -> ksampler(model)

3) empty latent image / upload image -> ksampler(latent_image) 
                
                -> act as a base image on which model generate final image

4) vae_decoder -> vae_loader

4) ksampler -> vae_decoder -> save image

            -> to convert final latent to image (jpg,png,--) and save image


BASIC Image to image flow:-

1) text_encoder -> load image
                -> load vae
                -> clip_loader (clip)
                -> ksampler(postive,negative)

2) model -> ksampler(model)

3) empty latent image / upload image -> ksampler(latent_image) 
                
                -> act as a base image on which model generate final image

4) vae_decoder -> vae_loader

4) ksampler -> vae_decoder -> save image

            -> to convert final latent to image (jpg,png,--) and save image

