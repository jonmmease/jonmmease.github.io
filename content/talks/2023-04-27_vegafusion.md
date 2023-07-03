+++
title = "Scaling Altair visualizations with VegaFusion"

[extra]
venue = "PyData Seattle 2023"
website = "https://seattle2023.pydata.org/cfp/talk/JFP7PR/"
youtube = "8vI0o8CuhLI"
thumbnail = "/talks/PyDataSeattle2023-VegaFusion.png"
+++

## Description
Altair is a popular Python visualization library that makes it easy to build a wide variety of statistical charts. On its own, Altair is unsuitable for visualizing large datasets (more than a few thousand rows) because it requires transferring the entire dataset to the browser for data processing and rendering. VegaFusion integrates with Altair to overcome this limitation by automatically moving data intensive calculations from the browser to the Python kernel. With VegaFusion, many Altair charts easily scale to millions of rows, significantly increasing the utility of Altair throughout the PyData ecosystem.
