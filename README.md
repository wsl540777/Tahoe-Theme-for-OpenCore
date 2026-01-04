# Tahoe Theme for OpenCore
Use Tahoe icons in OpenCore Boot Picker.\
在 OpenCore 中使用 Tahoe 风格的系统图标。

## **How to Apply the Theme｜如何应用主题**

1. Extract the `Dylan` folder and place it in: `EFI/OC/Resources/Image/`  
   将 `Dylan` 文件夹解压并放置于：`EFI/OC/Resources/Image/`

2. Open `config.plist` and navigate to **`Misc → Boot`**. Set the following parameters:\
   打开 `config.plist`，进入 **`Misc → Boot`**，并设置：  
   - **PickerVariant**: `Dylan\Tahoe`  
   - **PickerMode**: `External`  

3. Reboot your system and verify that the theme loads correctly.  
   重启系统，确认主题已正确加载。
