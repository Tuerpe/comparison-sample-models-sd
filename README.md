# comparison-sample-models-sd
Comparsion of euler_a, dpmpp_2m_sde and dpmpp_3m_sde in text2vid with comfyui

| steps/cfg | euler_a | dpmpp_2m_sde | dpmpp_3m_sde |
| --- | --- | --- | --- |
| 10/2.0 | ![GIFS_00001](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/79771ab1-d9a3-4f68-a7ba-24c6c5df49e0) | ![GIFS_00002](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/3cb1608a-c5f0-4ff5-a90b-c26d1a111798) | ![GIFS_00003](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/895ff58c-a72a-4ea4-b8b1-f148fdce6ae4) |
| 10/4.5 | ![GIFS_00004](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/1db9afdc-b8b4-4de4-a1df-284e596c03f2) | ![GIFS_00005](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/d98c7133-6c2c-446b-a698-4543eec275a6) | ![GIFS_00006](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/f2f7563f-b3d4-4034-9d1f-be58a449d00c) |
| 16/3.0 | ![GIFS_00007](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/ec98fb6f-4c67-409d-be70-72acb8af99c2) | ![GIFS_00008](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/7e1f5e11-0685-4262-ac3a-e7c78c9b14a2) | ![GIFS_00009](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/5a10f5fc-365b-4ef0-a6c6-5e4314a2fb5a) |
| 16/5.1 | ![GIFS_00010](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/50990ba7-3269-4221-9c13-6ba774c7c3c5) | ![GIFS_00011](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/e33c15ee-8153-499e-a6aa-2bb3fdce988c) | ![GIFS_00012](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/74acb380-75bb-4c9c-9b23-da555d55f699) |
| 32/6.0 | ![GIFS_00013](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/f5f21ff2-6173-4c10-91bb-994ee12253ec) | ![GIFS_00014](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/4e1b5588-aa4d-474e-880b-547faefa61cd) | ![GIFS_00015](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/989c0406-b96d-446f-83a7-6c4060111e37) |
| 32/4.0 | ![GIFS_00016](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/4cefddea-d595-46c1-9dea-debc09f34c26) | ![GIFS_00017](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/6f1c9d4b-522e-4350-947c-41df32b55d9e) | ![GIFS_00018](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/5dfffc10-5a12-40b3-beb2-906119060b88) |
| 32/10.0 | ![test32_13_00002](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/2591c2d9-5552-45fe-a910-349f7c5e17bb) | ![test32_13_00004](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/b94095c6-3a36-4dfc-b9ec-187988c68645) | ![test32_13_00006](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/82465a4b-fced-4e69-929d-552544d4abc3) | 
| 32/13.0 | ![test32_13!_00002](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/b12271fc-838e-4f1a-91f2-f83b842cb0b4) | ![test32_13!_00004](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/f08c6af5-870e-495f-93e8-a3817b908977) | ![test32_13!_00006](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/64f96c2d-0030-4cc5-bcc2-50b1db1fbedc) |





##Compare euler_a
|  | 2 | 4 | 6 | 10 | 13 |
| --- | --- | --- | --- | --- | --- |
| 10 | ![306945068-79771ab1-d9a3-4f68-a7ba-24c6c5df49e0](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/be1a53fa-1916-4a1a-b918-856bda9bca65) | --- | --- | --- | --- |
| 16 | --- | --- | --- | ![306963062-187a7494-3179-4ea1-9e4e-84970afb7e68](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/f01a0815-8650-4274-942a-aa8d0e464e8c) | ![306963163-b3046b7c-dcb6-4e09-874d-c9c054879b17](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/08e8f6b4-0069-4505-9e51-ddadee9d65c7) |
| 32 | --- | ![306945961-4cefddea-d595-46c1-9dea-debc09f34c26](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/60550019-832a-4a19-a930-4f0001f24bbb) | ![306945878-f5f21ff2-6173-4c10-91bb-994ee12253ec](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/5e732bf8-de7a-45bc-809b-e3bb6447fd80) | ![306957316-2591c2d9-5552-45fe-a910-349f7c5e17bb](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/71e6427e-6a90-4d4f-bd0f-92aa61ae512f) | ![306956400-b12271fc-838e-4f1a-91f2-f83b842cb0b4](https://github.com/Tuerpe/comparison-sample-models-sd/assets/73192339/eea51a3c-43c7-4552-83be-615d5e0b6930) |
| 64 | --- | --- | --- | --- | --- |
