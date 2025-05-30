# Midas Patch

Midas denotes Monte-Carlo inference over distributions across sliding, performs online global localization of a vision-based touch sensor on an object surface during sliding interactions. For details, refer to authors' <a href="https://suddhu.github.io/midastouch-tactile/">website</a> or their <a href="https://openreview.net/forum?id=JWROnOf4w-K">repo</a>. This is a patched version, compatible with **Python 3.8 to 3.12**.

<div align="center">
  <img src=".github/power_drill_ycb_slide.png"
  width="35%"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <img src=".github/power_drill_train_data.png"
  width="35%">
</div>

## Setup

```bash
sudo apt install build-essential python3-dev libopenblas-dev

# Python should >= 3.8, <= 3.12
pip install -r requirements.txt
pip install -e .
```

## Usage

```bash
python midastouch/data_gen/generate_data.py
```

## License

The majority of MidasTouch is licensed under MIT license, however portions of the project are available under separate license terms: MinkLoc3D is licensed under the MIT license; FCRN-DepthPrediction is licensed under the BSD 2-clause license; pytorch3d is licensed under the BSD 3-clause license. Please see the [LICENSE](LICENSE) file for more information.
