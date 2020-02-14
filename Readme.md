# LoRa-based Device-to-Device Smartphone Communication for Crisis Scenarios

In this repository the sources, as well as the experiment data is made available.

## Ressources

In our paper various software components have been used, including:
 - [rf95modem](https://github.com/gh0st42/rf95modem/), a modem firmware for arduino boards with an rf95 compatible radio module
 - [BlueRa](https://github.com/umr-ds/BlueRa), mobile application for communicating over LoRa and Bluetooth
 - [dtn7-go](https://github.com/dtn7/dtn7-go), Delay-tolerant networking software suite

## Range Evaluation

The range evaluation is contained in the eval folder, and contains the base data, a jupyter notebook and the ploted figures.

The jupyter notebook can be [viewed online](https://nbviewer.jupyter.org/github/umr-ds/hoechst2020lora/blob/master/eval/plot_ranges.ipynb).

## Citation

If you use the data in this repository for your publications, please consider citing our paper:

```bibtex
@inproceedings{hoechst2020lora,
  author = {{Höchst}, Jonas and {Baumgärtner}, Lars and Kuntke, Franz and Penning, Alvar and Sterz, Artur and Freisleben, Bernd},
  title = {{LoRa-based Device-to-Device Smartphone Communication for Crisis Scenarios}},
  booktitle = {{17th International Conference on Information Systems for Crisis Response and Management (ISCRAM 2020) [accepted for publication]}},
  address = {Blacksburg, Virginia, USA},
  month = may,
  year = {2020},
  keywords = {Disaster Communications, LoRa, Environmental Monitoring}
}
```
