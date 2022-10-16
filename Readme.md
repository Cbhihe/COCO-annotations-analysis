## COCO Annotations - a simple descriptive statistics toolbox

This notebook does one thing:<BR>
It describes the distribution of _caption lengths_ for the MS COCO dataset summaries and present results in simple charts.  Caption length is defined as the number of tokens making up a textual summary, barring punctuation.

This notebook was tested under Python 3.9.0. It contains a description of Python package requirements. It relies in part on calls to the COCO API proposed by Piotr Dollar and Lin Tsungyi in 2014.<BR> 
For that reason, and in order to successfully execute the notebook logic, the user first needs to git-clone https://github.com/cocodataset/cocoapi so the cloned contents are placed in the directory _cocoapi_ provided here as an empty placeholder.

--------------------------------------------------------------

### Copyright and licensing information:

The COCO API is protected by Copyright (C) 2014 Piotr Dollar and Tsung-Yi Lin, Microsoft Corp.<BR>

Copyright (c) 2021, 2022 Cedric Bhihe

The contents of this repo, Cbhihe/Coco_annotations, are licensed under the GNU General Public License v3.0.  The license terms can be consulted in the adjoined document under ***License.md***.  Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.
