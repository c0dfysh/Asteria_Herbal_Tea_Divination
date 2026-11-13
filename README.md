# Herbal Tea Divination · 涼茶占卜

## 繁體中文

這是涼茶占卜機的網頁互動原型。店員選擇一種身體狀態，顧客模擬掃描茶渣，再確認列印雙語籤文。原型包含五種身體狀態與五種茶渣結果，共 25 種組合。

### 開啟與操作

1. 解壓縮後，用瀏覽器開啟 `index.html`。請保留同一資料夾內的 SVG 檔案。
2. 在機器螢幕上選擇 DAMP、HEAT、DRY、STAGNANT 或 COLD，按下 **CONFIRM**。
3. 在網頁的 **DEMO CAMERA RESULT** 區域選擇模擬掃描結果。選項為散 · RELEASE、聚 · GATHER、轉 · TURN、和 · HARMONY、定 · SETTLE。
4. 在機器螢幕上按下 **CONFIRM SCAN**，查看組合圖案與雙語籤文摘要，再按 **CONFIRM PRINT**。
5. 完整籤文從機身右下方的出籤口吐出並落下。按 **SLIP COLLECTED**，回到店員設定。

掃描、列印與蓋章皆為網頁模擬。螢幕按 46 × 155 mm 的比例呈現，紙籤按 50 × 130 mm 的比例呈現。

### 上傳到 GitHub Pages

將解壓縮後的檔案上傳到 GitHub 儲存庫。讓 `index.html`、`machine-top.svg`、所有圖案 SVG 與 `README.md` 位於同一層，並將該層設為 GitHub Pages 的發佈來源。

- `index.html`：互動原型入口。
- `machine-top.svg`：機器俯視矢量圖。
- `A1.svg` 至 `A5.svg`：五種身體狀態的圖案。
- `A1_B1.svg` 至 `A5_B5.svg`：25 種籤文組合圖案。

## English

This browser prototype demonstrates the Herbal Tea Divination machine. Staff select a body state, the customer simulates a tea residue scan, and then confirms printing a bilingual fortune slip. Five body states and five tea trace results produce 25 combinations.

### Open and use

1. Extract the ZIP and open `index.html` in a browser. Keep the SVG files in the same folder.
2. On the machine screen, select DAMP, HEAT, DRY, STAGNANT, or COLD and press **CONFIRM**.
3. Under **DEMO CAMERA RESULT**, choose the simulated result: RELEASE · 散, GATHER · 聚, TURN · 轉, HARMONY · 和, or SETTLE · 定.
4. Press **CONFIRM SCAN** on the machine screen. Review the combined pattern and bilingual summary, then press **CONFIRM PRINT**.
5. The full slip feeds out of the slot on the lower right of the machine and drops below it. Press **SLIP COLLECTED** to return to staff setup.

The browser simulates scanning, printing, and stamping. The screen and slip use the proportions of a 46 × 155 mm screen and a 50 × 130 mm slip.

### Publish with GitHub Pages

Upload the extracted files to a GitHub repository. Keep `index.html`, `machine-top.svg`, all pattern SVGs, and `README.md` together. Use that directory as the GitHub Pages publishing source.

- `index.html` opens the interactive prototype.
- `machine-top.svg` is the vector top view of the machine.
- `A1.svg` through `A5.svg` contain the five body state patterns.
- `A1_B1.svg` through `A5_B5.svg` contain the 25 combined patterns.
