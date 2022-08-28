# Index
- [My creations](#my-creations)
- [Upscale](#upscale)

# My creations

<img src="https://user-images.githubusercontent.com/65092569/187077016-930cd505-bbc7-48b4-b2ce-eced9fdd8f13.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077078-b39817a7-82fc-4493-839d-fa26957afb9b.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077126-d3556634-c42d-4df7-9ac7-02f4a7e829a1.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077219-f2574c00-cc30-4eb5-b251-8423dfac5aba.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077253-ab539c57-ccf9-487b-b4a7-a3658ee7c56f.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077141-d722dd86-0304-40e1-9f82-f07c043a6b01.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077157-f49d6a1b-80bc-4cea-8432-19c8a12b0344.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077230-ec0133cb-14a9-4856-82b5-fde4a0beb75b.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077179-111299d2-5522-4f0a-bc03-d25951de9540.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187077132-13587344-25df-41d6-83dd-dc02ffe7ec2a.png" width="800">
<img src="https://user-images.githubusercontent.com/65092569/187083159-5eebefca-f81c-477c-acf2-2811185491de.png" width="800">


# Upscale

<table>
  <tr>
    <th width=200>Command</th>
    <th>Beta upscale (--upbeta)</th>
    <th>Light upscale (--uplight)</th>
    <th>Detailed</th>
  </tr>
  <tr>
    <td>Beautiful lonely tree on a green field, next to a creek</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187076186-71dda66e-a899-4746-9e47-1c0b258511aa.png" width="200"></td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187076256-b27152d7-7539-4aca-a6a5-f61fd77f89f8.png" width="200"></td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187076268-b590c5c2-1653-4a7a-bbd4-98db520d62f5.png" width="200"></td>
  </tr>
  <tr>
    <td>Dark cave filled with water</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187076347-7639b18e-b6d1-4a65-983b-82ace253ae7b.png" width="200"></td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187076368-894a9a05-564b-44a2-a076-53f6756e65f9.png" width="200"></td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187076379-64dcf29f-4136-42a6-a9e6-1d118f52978c.png" width="200"></td>
  </tr>
  <tr>
    <td>Purple sky at sunset, oil paint</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187077542-c4382237-757c-4915-a7f8-dccb703b33ea.png" width="200"></td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187077522-f307cdda-839c-450c-845a-a59d7f6c1a32.png" width="200"></td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187077532-d175557f-01bf-4bf3-9a69-d5e857eea479.png" width="200"></td>
  </tr>
</table>

# Parameters

## Image Weight (--iw)

Default: --iw 0.25

The more image weight (iw) an image has, the more similar the style of the new image will be to the reference.

But even with the highest image weight, the new image will only be somewhat similar to the reference

### With the same prompt and adding the reference image
<table>
  <tr>
    <th>Value</th>
    <th>Prompt</th>
    <th>Image</th>
  </tr>
  <tr>
    <td>Base</td>
    <td>Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187081612-c302aeea-89da-4290-bebb-bbef6e8c2996.png" width="600"></td>
  <tr>
    <td>0.01</td>
    <td>https://s.mj.run/9zHMEyu_73k Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight --iw 0.01</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187081894-b8418489-e3db-4d71-85be-ac240731f9f4.png" width="800"></td>
  </tr>
  <tr>
    <td>0.10</td>
    <td>https://s.mj.run/9zHMEyu_73k Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight --iw 0.10</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187082191-34b2a4d0-518f-413f-8b9d-459e63cae28f.png" width="800"></td>
  </tr>
  <tr>
    <td>0.25</td>
    <td>https://s.mj.run/9zHMEyu_73k Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight --iw 0.25</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187082399-21e11359-c21d-4ee0-b6fb-0554fce996a9.png" width="800"></td>
  </tr>
  <tr>
    <td>1</td>
    <td>https://s.mj.run/9zHMEyu_73k Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight --iw 1</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187082770-882ec1e5-7c52-4dd3-8559-76104ee52b41.png" width="800"></td>
  </tr>
  <tr>
    <td>4</td>
    <td>https://s.mj.run/9zHMEyu_73k Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight --iw 4</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187083058-99cf303b-48f1-46b8-8c21-fd730f5dc8a8.png" width="800"></td>
  </tr>
  <tr>
    <td>10</td>
    <td>https://s.mj.run/9zHMEyu_73k Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight --iw 10</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187083357-81f105e0-a661-47a3-99d6-037d4d13ecd1.png" width="800"></td>
  </tr>
  <tr>
    <td>100</td>
    <td>https://s.mj.run/9zHMEyu_73k Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight --iw 100</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187083699-76ebd68f-6ee5-4c31-ba40-09d595785ec7.png" width="600"></td>
  </tr>
</table>

### With a very basic prompt and adding the reference image
<table>
  <tr>
    <th>Value</th>
    <th>Prompt</th>
    <th>Image</th>
  </tr>
  <tr>
    <td>Base</td>
    <td>Dark mystery cave with water, clear water, water reflection lighting, epic lighting, hyper-realistic, octane render, hyper-detailed, 8k, vfx, ray tracing, de-noise, Cinematic Lighting, --ar 16:9 --uplight</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187084082-20ff8bae-3fd1-4de0-9b4d-21f3c7aba0d9.png" width="600"></td>
  <tr>
    <td>0.01</td>
    <td>https://s.mj.run/9zHMEyu_73k Cave --iw 0.01 --uplight --ar 16:9</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187084484-f9571b33-98ef-4c2b-8471-57338e8039ea.png" width="800"></td>
  </tr>
  <tr>
    <td>0.25</td>
    <td>https://s.mj.run/9zHMEyu_73k Cave --iw 0.25 --uplight --ar 16:9</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187084593-906b5829-53d8-47f8-9eaf-3c487192385b.png" width="800"></td>
  </tr>
  <tr>
    <td>0.25</td>
    <td>https://s.mj.run/9zHMEyu_73k Cave --iw 100 --uplight --ar 16:9</td>
    <td><img src="https://user-images.githubusercontent.com/65092569/187084824-bb1237f7-f547-4dca-a162-3770a7b28d08.png" width="800"></td>
  </tr>
</table>

