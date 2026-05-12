# 單元08. Python實戰 - 鐵達尼號數據科學工作坊

## Environment Setup (環境建置)
<img width="814" height="298" alt="image" src="https://github.com/user-attachments/assets/c285f97e-5793-4dc8-8035-3587d85b1717" />

## Phase 1: 資料概觀 (Data Overview)

### Lab 19-01: Head & Tail
### HEAD
<img width="762" height="509" alt="image" src="https://github.com/user-attachments/assets/f292b18d-fda3-4aec-af03-6e8b42483bbf" />

### TAIL
<img width="788" height="364" alt="image" src="https://github.com/user-attachments/assets/00837f7b-725f-45d8-8d6f-ceea8eabf7ec" />

### Lab 19-02: Info & Types
<img width="782" height="495" alt="image" src="https://github.com/user-attachments/assets/681a08ca-902b-4498-8df7-1601fe057644" />

### Lab 19-03: Descriptive Stats
<img width="789" height="518" alt="image" src="https://github.com/user-attachments/assets/f056f587-fea9-40d4-9f30-6dc8254e7796" />

## Phase 2: 基礎視覺化 (Basic Visualization - 20+ Charts)

### Chart 01: 整體存活計數 (Countplot)
題目: 到底有多少人存活，多少人罹難？畫出長條圖。
Insight: 罹難人數 (0) 遠多於存活人數 (1)。
<img width="795" height="151" alt="image" src="https://github.com/user-attachments/assets/f99e0441-9831-4754-ad7a-c13078658759" />

<img width="712" height="493" alt="image" src="https://github.com/user-attachments/assets/98c12a06-1cdc-4cbb-a41f-804f5d0e7378" />

### Chart 02: 存活比例圓餅圖 (Pie Chart)
題目: 畫出存活與罹難的百分比。
Insight: 61.6% 罹難, 38.4% 存活。
<img width="786" height="155" alt="image" src="https://github.com/user-attachments/assets/cbc6347b-fa27-4258-8dab-f24c637e3f14" />
<img width="540" height="491" alt="image" src="https://github.com/user-attachments/assets/e2438a83-8e3b-415b-9601-788c8536787a" />

### Chart 03: 性別分布 (Sex Count)
題目: 船上男性與女性的數量。
Insight: 男性乘客約為女性的兩倍。
<img width="784" height="127" alt="image" src="https://github.com/user-attachments/assets/d71d9412-ffe0-4fe1-bb27-b25c8ede849c" />
<img width="704" height="545" alt="image" src="https://github.com/user-attachments/assets/af0fd483-cea2-4f74-9f51-426a0a03daf6" />

### Chart 04: 性別與存活 (Sex vs Survival - Count)
題目: 男性與女性分別有多少人存活/罹難 (分組長條圖)。
Insight: 女性存活人數 > 罹難人數，男性則相反。
<img width="777" height="122" alt="image" src="https://github.com/user-attachments/assets/46e91988-d0d3-4ce3-b6d0-abfbac54c765" />
<img width="705" height="550" alt="image" src="https://github.com/user-attachments/assets/8c60c45a-0403-41c0-95f9-21f57d0abcf5" />

### Chart 05: 性別存活率 (Survival Rate by Sex)
題目: 直接畫出存活機率 (Barplot with CI)。
Insight: 女性存活率約 74%，男性僅約 18%。
<img width="787" height="97" alt="image" src="https://github.com/user-attachments/assets/b7e9c9b3-0116-4278-87da-e09f129cc104" />
<img width="694" height="540" alt="image" src="https://github.com/user-attachments/assets/c3f27d60-11de-4490-a72b-e42ed80ebca9" />

### Chart 06: 艙等分布 (Pclass Count)
題目: 不同艙等的人數分布。
Insight: 三等艙 (3) 人數最多。
<img width="783" height="127" alt="image" src="https://github.com/user-attachments/assets/beb0ddf2-f263-4185-a6b0-ceb7ac99ef89" />
<img width="706" height="545" alt="image" src="https://github.com/user-attachments/assets/60134c19-91cf-479b-babc-29654acc26b2" />

### Chart 07: 艙等與存活 (Pclass vs Survival)
題目: 各艙等的存活狀況。
Insight: 一等艙有較高比例存活，三等艙死傷慘重。
<img width="783" height="128" alt="image" src="https://github.com/user-attachments/assets/a13bd5d1-6fc0-4555-978e-227c4d8514cb" />
<img width="696" height="544" alt="image" src="https://github.com/user-attachments/assets/ccab96bc-f257-4070-8c4e-e2c64eac4af8" />

### Chart 08: 艙等存活率 (Rate by Pclass)
題目: 畫出各艙等的生存率。
Insight: P1 > 60%, P2 ~ 47%, P3 ~ 24%.
<img width="787" height="76" alt="image" src="https://github.com/user-attachments/assets/076f14c2-1f72-4a6f-9460-74ff926efc85" />
<img width="690" height="522" alt="image" src="https://github.com/user-attachments/assets/2011cb42-9b08-4827-9dd5-17b20120aeed" />

### Chart 09: 艙等與性別交互 (Factorplot/Catplot)
題目: 分開看男性與女性在不同艙等的存活率。
Insight: 一二等艙女性存活率接近 95%！但三等艙女性存活率下降至 50% 左右
<img width="784" height="97" alt="image" src="https://github.com/user-attachments/assets/2ad2c29a-60a2-4066-9247-b156b5e7c9f4" />
<img width="697" height="594" alt="image" src="https://github.com/user-attachments/assets/faad7eb5-1a77-45d6-b031-506cc18e6991" />

### Chart 10: 交互作用長條圖 (Catplot Bar)
題目: 同上，但使用長條圖表示。
<img width="788" height="98" alt="image" src="https://github.com/user-attachments/assets/cb63e664-31fe-449a-9cad-e6150f5b71c4" />
<img width="1679" height="533" alt="image" src="https://github.com/user-attachments/assets/63ceaeba-26bb-4ffb-8f22-d55c6c44989c" />
