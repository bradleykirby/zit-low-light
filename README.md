
<img width="1536" height="1280" alt="low-light-tut-07_00001_" src="https://github.com/user-attachments/assets/53d5f0e7-9791-4427-b35b-95a7fc8163c0" />
<img width="1536" height="1280" alt="low-light-tut-08_00003_" src="https://github.com/user-attachments/assets/9de11705-0d64-4c75-9700-047f7ddfd8d7" />
<img width="1536" height="1280" alt="low-light-tut-09_00002_" src="https://github.com/user-attachments/assets/8f75e3c6-5ae9-42aa-9ee4-6a8103066540" />


I was having a lot of trouble generating low light scenes with zit until I saw this comment https://www.reddit.com/r/StableDiffusion/comments/1pdgf3f/comment/ns4ulkm/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button

I thought I'd share a simple workflow to make this easier. Download the black latent and import the workflow file. 

Prompt: Photorealistic interior of dive bar at night, adult woman in her late 20s seated alone at bar counter, dark hair falling over one eye, red lips, black dress with low neckline, cigarette trailing smoke. dark blue shadows, her face half-lit Wide shot from entrance, shallow depth of field, film grain.

The key here is adjusting the denoising value as a way to control light level. The examples show 0.7, 0.8, and 0.9.

For the prompt it's best to avoid describing any direct light source. "soft candlelight" will render a white hot candle for example.
