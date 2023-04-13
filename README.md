# openvino

This is a openvino sample code which getting video stream from  i-PRO camera.
i-PROカメラからのビデオストリームを取得するopenvinoのサンプルコードです。

---

## human_pose_estimation_demo

**Folder：** human_pose_estimation_demo  

**関連記事：** [OpenVINOを使ってみる (Ubuntu編)](https://i-pro-corp.github.io/Programing-Items/openvino/try_openvino_ubuntu.html)
**関連記事：** [Human Pose Estimation Python Demo](https://docs.openvino.ai/latest/omz_demos_human_pose_estimation_demo_python.html)
**関連記事：** [JPEG で接続する](https://i-pro-corp.github.io/Programing-Items/Python/connect_camera/connect_with_jpeg.html)

This source code is based on and modified from human_pose_estimation_demo.py in Intel's open_model_zoo demo.
The image input part is changed to a network camera, so please refer to the original to check the changes.
 
このソースコードは、Intelのopen_model_zooデモのhuman_pose_estimation_demo.pyを元に、改変したものです。
画像入力部分をネットワークカメラに変更していますので、変更点の確認はオリジナルを参照してください。


| Filename                            | Abstract                                                      |
|:------------------------------------|:--------------------------------------------------------------|
| human_pose_estimation_demo_jpeg.py  | human_pose_estimation_demo with i-PRO camera JPEG Stream.     |



---
Original license of human_pose_estimation_demo.py from intel openmodelzoo 
オリジナルのhuman_pose_estimation_demo.pyのライセンス

Copyright (C) 2020-2023 Intel Corporation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License. You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License
