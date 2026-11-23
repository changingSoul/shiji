# 食记 / Shiji

简洁的本地优先饮食记录 PWA。记录三餐、零食、水果、地点、就餐人、单张照片、感想；外食和外卖共享月度次数与金额预算。

## 使用 GitHub Pages 部署

1. 在 GitHub 创建一个 **Public** 仓库，例如 `shiji`。
2. 将本目录里的 **所有文件** 上传到仓库根目录（务必把 `index.html` 放在根目录；不要只上传压缩包）。
3. 在仓库 `Settings` → `Pages` → `Build and deployment` 中选 `Deploy from a branch`，Branch 选 `main`，Folder 选 `/(root)`，点击 Save。
4. 等待 GitHub Pages 部署完成，打开 `https://你的用户名.github.io/shiji/`（如果仓库不是 shiji，相应修改末尾路径）。
5. 用 Android Chrome 浏览器打开这个网址，在浏览器菜单中选择“安装应用”或“添加到主屏幕”。

## 数据与隐私

- GitHub 仓库与 Pages 网站在此方案中公开；**不要将个人饮食记录、导出的 JSON/CSV 或私密照片上传到仓库**。
- 日常记录和照片保存在浏览器的 IndexedDB 中，正常使用不会上传到 GitHub，也不会自动跨设备同步。
- 同一个网址、同一设备、同一个浏览器环境中才能正常继续使用原本的本地数据；清除网站数据、换浏览器或换手机可能丢失记录。
- 在“设置”中定期导出完整 JSON 备份，妥善保管；CSV 便于分析但不包含全部照片数据。
- 将来升级应用时，尽量保持 GitHub Pages 网址和浏览器环境不变，以便读取原有记录。

> 本应用是个人记录工具，不提供云端同步或账户系统。
