<img src="assets/MobileGlues-icon.png" width="128">

MobileGlues
====

> [!NOTE]
> 
>最新版本：
>
> **1.1.0.1**
>
> 請查看 [Release](https://github.com/Swung0x48/MobileGlues-release/releases)

> [!NOTE]
> 
> 查看 [CompatibleShaders.md](https://github.com/Swung0x48/MobileGlues-release/blob/main/CompatibleShaders.md) 以獲取兼容的 Minecraft 光影信息。
>
> 查看 [CompatibleMods.md](https://github.com/Swung0x48/MobileGlues-release/blob/main/CompatibleMods.md) 以獲取兼容的 Minecraft 模組信息。
>
> 查看 [模組支持列表](https://github.com/Swung0x48/MobileGlues-release/blob/main/ModSupportMatrix.md) 或 [光影支持列表](https://github.com/Swung0x48/MobileGlues-release/blob/main/ShaderSupportMatrix.md)，了解您的設備運行情況。

**MobileGlues**，其名稱意為「(在)移動設備上，GL 使用 ES」，是一個基於 OpenGL ES 3.2 運行的 GL 實現，專為運行 Minecraft Java 版設計。

功能特點
====

1. 能夠運行 Minecraft 的 [Sodium](https://github.com/CaffeineMC/sodium) 模組；

2. 能夠使用 Minecraft 的 [Iris](https://github.com/IrisShaders/Iris) 模組或 [Optifine](https://optifine.net/home) 渲染大部分光影；

3. 能夠兼容部分具有自定義渲染流程的 Minecraft 模組，如 [JourneyMap](https://teamjm.github.io/journeymap-docs/latest) 和 [Create](https://createmod.net)。

關於插件應用
====

插件應用已在 [MobileGlues-plugin](https://github.com/Swung0x48/MobileGlues-plugin) 開源。

除非另有說明，該倉庫的內容均以 [ECVL V1.0 許可證](https://github.com/Swung0x48/MobileGlues-plugin/blob/main/LICENSE.md) 開源。

加入我們
====

由於我們的團隊規模較小，我們無法擁有所有設備並對其進行全面測試。

如果您對該項目感興趣，請考慮通過以下方式貢獻：

填寫 [Mod 支持列表](https://github.com/Swung0x48/MobileGlues-release/blob/main/ModSupportMatrix.md) 或 [Shader 支持列表](https://github.com/Swung0x48/MobileGlues-release/blob/main/ShaderSupportMatrix.md)！

我們需要您的幫助來測試不同設備對著色器和模組的兼容性！

> [!NOTE]
> 如何填寫表格：
> 
> 您可以：
> 
> - 在表格中新增一個設備，通過在表格末尾添加新的一行。（您可以使用 `adb shell getprop ro.product.name` 獲取設備代號）
> - 在表格中新增一個項目，通過在表格末尾添加新的一列。（請確保所有行格式合法！）
> - 在設備的對應單元格中標記兼容性情況：
>     - 兼容的項目標記為 ✅；
>     - 完全不兼容的項目標記為 ❌（並提交問題或提供問題鏈接）；
>     - 未測試的項目（不在您的模組包中/您未安裝該模組）標記為 ？；
>     - 存在部分功能缺失或渲染問題的項目標記為 *️⃣（並提交問題或提供問題鏈接）。
> - 如適用，您可以在 "額外驅動/插件" 列中說明您使用的除官方提供之外的其他驅動或插件（如 Turnip 驅動、ANGLE 等）。
> - 如適用，您應添加一個 `*設備代號*.md` 文件，提供更多詳細信息，並在表格的最後一列附上鏈接。

版權聲明
====

版權所有 (C) 2025 Swung0x48, BZLZHH, Tungsten。保留所有權利。標誌設計由 Aou156 友情提供。

第三方組件
====

**SPIRV-Cross** by **KhronosGroup**：[GitHub](https://github.com/KhronosGroup/SPIRV-Cross)

**glslang** by **KhronosGroup**：[GitHub](https://github.com/KhronosGroup/glslang)

**GlslOptimizerV2** by **aiekick**：[GitHub](https://github.com/aiekick/GlslOptimizerV2)

**cJSON** by **DaveGamble**：[GitHub](https://github.com/DaveGamble/cJSON)

**Gson** by **Google**：[GitHub](https://github.com/google/gson)  

**AndroidX Activity Compose** by **Android Open Source Project (AOSP)**：[Android Developers](https://developer.android.com/jetpack/androidx/releases/activity)
