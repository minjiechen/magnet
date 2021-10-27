[![Build](https://github.com/PrincetonUniversity/Magnet/actions/workflows/main.yml/badge.svg)](https://github.com/PrincetonUniversity/Magnet/actions/workflows/main.yml)
![MagNet Logo](app/img/magnetlogo.jpg)

Princeton MagNet is a large-scale dataset designed to enable researchers modeling magnetic core loss using machine learning to accelerate the design process of power electronics. The dataset contains a large amount of voltage and current data of different magnetic components with different shapes of waveforms and different properties measured in the real world. Researchers may use these data as pairs of excitations and responses to build up dynamic magnetic models or calculate the core loss to derive static models.

## Website

Princeton MagNet is currently deployed at https://share.streamlit.io/minjiechen/pmagnet/main/main.py

## Documentation

The web application for Princeton MagNet uses the `magnet` package, a python package under development where most of
the functionality is exposed. Before `magnet` is released on PyPI, it can be installed using
`pip install git+https://github.com/PrincetonUniversity/Magnet`.

API Documentation for `magnet` can be viewed online at [https://princetonuniversity.github.io/Magnet/](https://princetonuniversity.github.io/Magnet/)

## How to Cite

If you used MagNet, please cite us with the following BibTeX item.

<!-- TODO: Update once dataset paper is published. -->

```
@INPROCEEDINGS{9265869,
  author={H. {Li} and S. R. {Lee} and M. {Luo} and C. R. {Sullivan} and Y. {Chen} and M. {Chen}},
  booktitle={2020 IEEE 21st Workshop on Control and Modeling for Power Electronics (COMPEL)}, 
  title={MagNet: A Machine Learning Framework for Magnetic Core Loss Modeling}, 
  year={2020},
  volume={},
  number={},
  pages={1-8},
  doi={10.1109/COMPEL49091.2020.9265869}
}
```
## Team Members

Princeton MagNet is currently maintained by the Power Electronics Research Lab as Princeton University. We also collaborate with Dartmouth College, and Plexim.

![MagNet Team](app/img/magnetteam.jpg)

## Sponsors

This work is sponsored by the ARPA-E DIFFERENTIATE Program.

![MagNet Sponsor](app/img/sponsor.jpg)