
## Abstract
With the demand for autonomous control and personalized speech generation, style control and transfer in Text-to-Speech (TTS) are becoming more and more important. In this paper, we propose a new TTS system that can perform style transfer with high fidelity and interpretability. Firstly, we design a two-stage TTS system, which combines variational autoencoder and diffusion refiner, to analyse the audio quality and the performance of style transfer. Furtherly we simplify the training pipeline to form a one-stage TTS system that can reduce training time and get comparable results. Secondly, a diffusion bridge of quantized variational autoencoder is designed to efficiently learn complex discrete representations. In order to achieve a better level of interpretability, we introduce ControlVAE to extract more disentangled latent space and improve the reconstruction quality simultaneously.
Experiments on LibriTTS datatset demonstrate that our method is more effective than baseline models.


## Parallel Style Transfer.

| <center> Reference Speech </center> | <center> Text </center> | <center> Generated Speech </center>|
| -----------     |  -----------     | -----------     |
|  <audio src="Interpret-TTS/PST/wavs_g/[000009].wav" controls preload></audio>  | we will leave the banker contemplating the enormous magnitude of his debt before the phantom of bankruptcy , and follow the baroness , who after being momentarily crushed under the weight of the blow which had struck her , had gone to seek her usual adviser , lucien debray . |  <audio src="Interpret-TTS/PST/wavs_p/[000009].wav" controls preload></audio>  |
| <audio src="Interpret-TTS/PST/wavs_g/[000028].wav" controls preload></audio> | when wendy returned diffidently she found peter sitting on the bed post crowing gloriously , while jane in her nighty was flying round the room in solemn ecstasy .| <audio src="Interpret-TTS/PST/wavs_p/[000028].wav" controls preload></audio> |
| <audio src="Interpret-TTS/PST/wavs_g/[000029].wav" controls preload></audio> | we shall never get on together therefore , and theres no use trying . | <audio src="Interpret-TTS/PST/wavs_p/[000029].wav" controls preload></audio>|



## Non-parallel Style Transfer.


| <center> Text </center> |
| ----------- |
| the invention of movable metal letters in the middle of the fifteenth century may justly be considered as the invention of the art of printing. |

---


| <center> Reference Speech </center> | <center> Generated Speech </center>|
| -- | -- |
|<audio src="Interpret-TTS/NPST/000009_g.wav" controls preload></audio>  |  <audio src="Interpret-TTS/NPST/000009_p.wav" controls preload></audio> |
|<audio src="Interpret-TTS/NPST/000032_g.wav" controls preload></audio>  |  <audio src="Interpret-TTS/NPST/000032_p.wav" controls preload></audio> |
|<audio src="Interpret-TTS/NPST/000048_g.wav" controls preload></audio>  |  <audio src="Interpret-TTS/NPST/000048_p.wav" controls preload></audio> |


##  Style Interpretability.

| <center> Reference Speech </center> | <center> Dimension </center> | <center> Generated Speech </center> |
| -----------     | -----------     |-----------     |
| <audio src="Interpret-TTS/style_interpret/696_93314_000002_000000.wav" controls preload></audio> | Dimension 1 | <audio src="Interpret-TTS/style_interpret/dim1/generate.wav" controls preload></audio> |
| <audio src="Interpret-TTS/style_interpret/696_93314_000002_000000.wav" controls preload></audio> | Dimension 7 | <audio src="Interpret-TTS/style_interpret/dim7/generate.wav" controls preload></audio> |
| <audio src="Interpret-TTS/style_interpret/696_93314_000002_000000.wav" controls preload></audio> | Dimension 28 | <audio src="Interpret-TTS/style_interpret/dim28/generate.wav" controls preload></audio> |
