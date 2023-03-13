
## Abstract

The demo page of `Interpretable Style Transfer for Text-to-Speech with ControlVAE and Diffusion Bridge`.
---
## Parallel Style Transfer.

| <center> Reference Speech </center> | <center> Text </center> | <center> GenerSpeech </center>| <center> Our </center>|
| -----------     |  -----------     | -----------     |
|  <audio src="Interpret-TTS/PST/81_true.wav" controls preload></audio>  | i was not thinking of that , replied madame danglars quickly . |  <audio src="Interpret-TTS/PST/81_gener.wav" controls preload></audio>  | <audio src="Interpret-TTS/PST/81_our.wav" controls preload></audio>  |
| <audio src="Interpret-TTS/PST/135_true.wav" controls preload></audio> | of course all the boys went to school ; and most of them got into class three , but slightly was put first into class four and then into class five class one is the top class .| <audio src="Interpret-TTS/PST/135_gener.wav" controls preload></audio> |<audio src="Interpret-TTS/PST/135_our.wav" controls preload></audio> |
| <audio src="Interpret-TTS/PST/231_true.wav" controls preload></audio> | shed like gardencourt a great deal better if it were a boarding house .| <audio src="Interpret-TTS/PST/231_gener.wav" controls preload></audio> |<audio src="Interpret-TTS/PST/231_our.wav" controls preload></audio> |
| <audio src="Interpret-TTS/PST/339_true.wav" controls preload></audio> |it would have proved that he believed she was firm which was what she wished to seem to him .| <audio src="Interpret-TTS/PST/339_gener.wav" controls preload></audio> |<audio src="Interpret-TTS/PST/339_our.wav" controls preload></audio> |



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
| <audio src="Interpret-TTS/style_interpret/696_93314_000002_000000.wav" controls preload></audio> | Dimension 9 | <audio src="Interpret-TTS/style_interpret/dim9/generate.wav" controls preload></audio> |
