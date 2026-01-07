# Nutanix-HandsOn-RESTAPI

## Nutanixハンズオン環境

### 接続先
nuta-auto(172.29.30.12) user:nutanix/pw:Peg-12345!

### 操作方法
①Pythonの仮想環境へ移動
'''source .python3_venv/bin/activate'''
②ディレクトリの移動
'''cd basic-handson'''
③コードの実行
'''python Foundation_Post.py'''


### 初級
```
basic-handson/
├── HYD_Cluster/ or AF_Cluster/
│   ├── 0_foundation/
        ├── Foundation_Post.py
        └── foundation_image_nodes7.3.json
│   ├── 1_after_foundation/
        ├── after_foundation.py
        └── body_dict_pulse.json
│   ├── 2_initial_setup/
        ├── 01_handson_Networkadd.py
        ├── 02_DataserviceIP-patch.py
        ├── 03_Image_Post.py
        ├── 04_v4Deploy_PrismCentral.py
        ├── 05_PrismCentralEULA.py
        ├── 06_PCregister.py
        ├── 07_handson_password_extension.py
        ├── 08_hanson_Useradd.py
        └── PrismCentral01.json or PrismCentral02.json
│   ├── param.json
│   └── param.py

```

### 中級
```
basic-handson/
├── HYD_Cluster/ or AF_Cluster/
│   ├── 0_foundation/
        ├── Foundation_Post.py
        └── foundation_image_nodes7.3.json
│   ├── 1_after_foundation/
        ├── after_foundation.py
        └── body_dict_pulse.json
│   ├── 2_initial_setup/
        ├── 01_handson_Networkadd.py
        ├── 02_DataserviceIP-patch.py
        ├── 03_Image_Post.py
        ├── 04_v4Deploy_PrismCentral.py
        ├── 05_PrismCentralEULA.py
        ├── 06_PCregister.py
        ├── 07_handson_password_extension.py
        ├── 08_hanson_Useradd.py
        └── PrismCentral01.json or PrismCentral02.json
│   ├── 3_mid_setup/
        ├── 10_Enable_Marketplace.py
        ├── 11_FilesUpload.py
        ├── 12_CreateFileServer.py
        ├── 13_CreateSSR.py
        ├── 14_Deploy_FileAnaytics.py
        ├── 15_Enable_FileAnalytics.py
        ├── 16_ImportImage.py
        ├── 17_CreateVM-v4api.py
        ├── 18_Enable_NCM.py
        ├── 19_EnableDR.py
        ├── 20_smtp_config.py
│   ├── param.json
│   └── param.py
```
