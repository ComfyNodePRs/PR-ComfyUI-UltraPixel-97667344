# ComfyUI-UltraPixel (WIP)

All thanks to the team that made UltraPixel:<br/>
https://jingjingrenabc.github.io/ultrapixel/<br/>
https://arxiv.org/abs/2407.02158<br/>
https://github.com/catcathh/UltraPixel<br/>

Install by git cloning this repo to your ComfyUI custom_nodes directory.
```
git clone https://github.com/2kpr/ComfyUI-UltraPixel
```

Install the requirements from within your conda/venv.
```
pip install -r requirements.txt
```

Load the provided workflow.json in ComfyUI and hit 'Queue Prompt'.

When the workflow first runs the first node will download all the necessary files into a ComfyUI/models/ulttrapixel directory.<br/>
<i>(make sure to update as there was an issue with downloading stage_b_lite_bf16.safetensors which was fixed [here](https://github.com/2kpr/ComfyUI-UltraPixel/commit/45d32bbe3777f1773dc0f74deea075d77b6d9278))</i>

Example Output for prompt:
"A close-up portrait of a young woman with flawless skin, vibrant red lipstick, and wavy brown hair, wearing a vintage floral dress and standing in front of a blooming garden."
<br/>
<br/>

<img src="https://github.com/2kpr/ComfyUI-UltraPixel/blob/main/ComfyUI_00001_.png">

<br/>
Example Output for prompt:
A highly detailed, high-quality image of the Banff National Park in Canada. The turquoise waters of Lake Louise are surrounded by snow-capped mountains and dense pine forests. A wooden canoe is docked at the edge of the lake. The sky is a clear, bright blue, and the air is crisp and fresh.
<br/>
<br/>

<img src="https://github.com/2kpr/ComfyUI-UltraPixel/blob/main/ComfyUI_00002_.png">
