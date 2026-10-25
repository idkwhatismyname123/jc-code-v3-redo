# jc-code-v3-redo
反编译某人的jc code v3 可重新编译的源码 
apktool_patch/
├── apktool.yml              # 工程配置：版本号、min/targetSdk 等
├── AndroidManifest.xml      # 解码后的明文 XML（不是二进制）
├── res/                     # 解码后的资源（layout、values、drawable...）
├── assets/                  # 原 APK 的 assets
├── lib/                     # 原 APK 的 .so
├── smali/                   # classes.dex 反汇编出来的 Smali
├── smali_classes2/          # classes2.dex 反汇编出来的 Smali
├── original/                # 原 META-INF 等
└── unknown/                 # 原样保留的未知文件
