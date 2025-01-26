```
annotations
├── 000
│   ├── 0000
│        ├── img_path='images/0000/Camera00/000000.jpg
│        ├── h_w=(1536,2048)
│        └── 0
             ├── betas:10个体型参数
             ├── pose :24个关节点，姿态参数
             ├── trans:模型沿x,y,z的平移量
             ├── bbox :左上和右下顶点坐标
             ├── smpl_joints_2d:smpl模型24个关键点2D坐标及可见性
             ├── smpl_joints_3d:smpl模型24关键点3D参数
             ├── lsp_joints_2d :LSP模型14个关键点2D坐标及可见性
             ├── lsp_joints_3d :LSP模型14个关键点3D参数
             ├── mask_path     :掩码路径
             ├── alphosepose :alphosepose模型关键点坐标
             ├── openpose:openpose模型关键点坐标
             ├── scale :缩放系数
             ├── halpe_joints_2d:Halpe_FullBody模型身体和脚部26个关键点2D坐标及可见性
             ├── halpe_joints_3d:Halpe_FullBody模型身体和脚部26个关键点3D参数
             ├── intri :相机内参(第一行第一列：沿x轴的相机焦距，第1行第3列：图像平面上光学中心(主点)在x轴方向的坐标；第2行第2列：沿y轴方向的相机焦距，第2行第3列：主点在y轴方向的坐标；第3行：用于保持矩阵运算的一致性)
             ├── extri :旋转矩阵参数
             ├── hmr2_pose:hmr2模型24个关键点3D参数
             ├── smpl_joints_3d:smpl模型24关键点3D参数
             ├── lsp_joints_2d :LSP模型14个关键点2D坐标及可见性
             ├── lsp_joints_3d :LSP模型14个关键点3D参数
             ├── mask_path     :掩码路径
             ├── alphosepose :alphosepose模型关键点坐标
             ├── openpose:openpose模型关键点坐标
             ├── scale :缩放系数
             ├── halpe_joints_2d:Halpe_FullBody模型身体和脚部26个关键点2D坐标及可见性
             ├── halpe_joints_3d:Halpe_FullBody模型身体和脚部26个关键点3D参数
             ├── intri :相机内参(第一行第一列：沿x轴的相机焦距，第1行第3列：图像平面上光学中心(主点)在x轴方向的坐标；第2行第2列：沿y轴方向的相机焦距，第2行第3列：主点在y轴方向的坐标；第3行：用于保持矩阵运算的一致性)
             ├── extri :旋转矩阵参数

│   │   └── smplx_kid_template.npy
│   ├── smil
│   │   ├── smil_packed_info.pth
│   │   └── smplx_kid_template.npy
│   ├── smpla
│   │   └── SMPLA_NEUTRAL.pth
│   ├── smplh
│   │   ├── SMPLH_FEMALE.pk1
│   │   └── SMPLH_MALE.pk1
│   └── smplx
│       ├── SMPLX_FEMALE.npz
│       ├── SMPLX_FEMALE.pk1
│       ├── SMPLX_MALE.npz
│       ├── SMPLX_MALE.pk1
│       ├── SMPLX_NEUTRAL.npz
│       └── SMPLX_NEUTRAL.pk1
└── pretrained
├── Human4D_data
├── CLIFF_data
└── BUDDI_data
