# pytorch-stable-diffusion
PyTorch implementation of Stable Diffusion from scratch

## Download weights and tokenizer files:

1. Download `vocab.json` and `merges.txt` from [Hugging Face](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main/tokenizer) and save them in the `data` folder.
2. Download `v1-5-pruned-emaonly.ckpt` from [Hugging Face](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main) and save it in the `data` folder.

## Tested fine-tuned models:

Just download the `ckpt` file from any fine-tuned SD (up to v1.5).

1. InkPunk Diffusion: [Hugging Face](https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main)
2. Illustration Diffusion (Hollie Mengert): [Hugging Face](https://huggingface.co/ogkalu/Illustration-Diffusion/tree/main)

## Running the Demo

To run the demo, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/AayudhPanchal/Stable-Diffusion-Model.git
    ```

2. Navigate to the [sd](http://_vscodecontentref_/0) directory:
    ```sh
    cd Stable-Diffusion-Model/sd
    ```

3. Ensure that the downloaded files (`vocab.json`, `merges.txt`, and `v1-5-pruned-emaonly.ckpt`) are placed in a folder named [data](http://_vscodecontentref_/1), parallel to the [sd](http://_vscodecontentref_/2) directory. The folder structure should look like this:
    ```
    Stable-Diffusion-Model/
    ├── data/
    │   ├── vocab.json
    │   ├── merges.txt
    │   └── v1-5-pruned-emaonly.ckpt
    └── sd/
        ├── demo.ipynb
        └── ...
    ```

4. Run the demo file and enter your prompt when prompted:
    ```sh
    jupyter notebook demo.ipynb
    ```

## Special thanks

Special thanks to the following repositories:

1. [CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion/)
2. [divamgupta/stable-diffusion-tensorflow](https://github.com/divamgupta/stable-diffusion-tensorflow)
3. [kjsman/stable-diffusion-pytorch](https://github.com/kjsman/stable-diffusion-pytorch)
4. [huggingface/diffusers](https://github.com/huggingface/diffusers/)
5. [YouTube Tutorial by ZBKpAp_6TGI](https://www.youtube.com/watch?v=ZBKpAp_6TGI)