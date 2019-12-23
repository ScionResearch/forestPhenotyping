# forestPhenotyping
A machine learning approach to model productivity based on area calculated features

Developped in Python.

## What it does
The programme shows the different stages developed to compare three gradient boosting approaches: XGBoost, CatBoost, and LightGBM. The input is a large dataset representing a 25x25m area within the forest and composed of variables describing climate, forest management, tree genetics, and fine-scale terrain information extracted from environmental surfaces. 

The second script shows the usage of the predictions from the models to extract the features of importance, drivers of the productivity accross the forest (Gini score or Gain) or for the individual area (Shapley values).

## Credits
The authors would like to acknowledge the contribution of the forest manager Timberlands Ltd. for generously providing datasets, contributing significant staff time to dealing with our data requests and questions, and providing access to the forest. This research was undertaken as part of the Growing Confidence in Forestry's Future research programme, which is jointly funded by the New Zealand Ministry of Business, Innovation and Employment (contract No C04X1306) and the Forest Growers Levy Trust. We recognise the contribution of the whole GCFF team at Scion (NZ Forest Research Institute) team who provided useful discussions and helped with the development of the concepts applied in this research.

The authors were employed by the New Zealand Forest Research Institute Limited, trading as Scion. The authors declare that the research was conducted in the absence of any commercial or financial relationships that could be construed as a potential conflict of interest.

Due to data protection, we cannot share the exact content of the DataFrame, however, the list of features studied in this project are detailed in Bombrun et al., 2020 (under review).

## License 

    Copyright (c) 2013-2020, Maxime Bombrun
    All rights reserved.

    Redistribution and use in source and binary forms, with or without modification,
    are permitted provided that the following conditions are met:

      Redistributions of source code must retain the above copyright notice, this
      list of conditions and the following disclaimer.

      Redistributions in binary form must reproduce the above copyright notice, this
      list of conditions and the following disclaimer in the documentation and/or
      other materials provided with the distribution.

      Neither the name of the {organization} nor the names of its
      contributors may be used to endorse or promote products derived from
      this software without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
    WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
    DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR
    ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
    (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
    LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
    ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
    SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
