## About this data
- Online property companies offer valuations of houses using machine learning techniques. The aim of this report is to predict the house sales in King County, Washington State, USA using Multiple Linear Regression (MLR). The dataset consisted of historic data of houses sold between May 2014 to May 2015. We will predict the sales of houses in King County with an accuracy of at least 75-80% and understand which factors are responsible for higher property value - $650K and above.”

- The dataset consists of house prices from King County an area in the US State of Washington, this data also covers Seattle. The dataset was obtained from Kaggle. This data was published/released under CC0: Public Domain. Unfortunately, the user has not indicated the source of the data. Please find the citation and database description in the Glossary and Bibliography. The dataset consisted of 21 variables and 21613 observations.

# 價格與基本資訊
- id：房子的唯一編號（ID）
- price：房價（目標欄位，預測的 y）
- date：成交日期（可拆成年、月來做特徵）

# 🏡 房屋本體
- bedrooms：臥室數量
- bathrooms：浴室數量
- sqft_living：室內可住面積（平方英尺）
- sqft_lot：土地面積（平方英尺）
- floors：樓層數
- waterfront：是否臨水（1 = 有水岸景觀，0 = 沒有）
- view：景觀評分（0～4，數字越高景觀越好）
- condition：屋況（1～5，數字越高狀況越好）
- grade：建築等級（1～13，代表整體品質與設計水準）

# 📐 面積細節
- sqft_above：地面以上的室內面積
- sqft_basement：地下室面積

# 🗓️ 年份相關
- yr_built：建造年份
- yr_renovated：翻修年份（0 代表從未翻修）

# 📍 地理位置
- ipcode：郵遞區號（區域位置）
- lat：緯度（latitude）
- long：經度（longitude，會是負數是正常的）

# 🧭 周邊環境（附近房子狀況）
- sqft_living15：周圍 15 戶鄰居的平均居住面積
- sqft_lot15：周圍 15 戶鄰居的平均土地面積