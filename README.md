# F2E Project Architecture
*前端技術架構及應用說明*

## 目錄

1. [ReactJS.NET 運作及架構說明](reactjs.net/)
1. [React 基本設計理念](react_base/)
1. [CSS與JavaScript 打包壓縮方式](bundler/)


## 主要目的
### ReactJS.NET
* 將前端程式建置整合在.NET Project，後端也可以運行前端架構並共同合作
* 運用 .NET MVC 的好處，Route 路徑轉導的工作交給原生的 MVC 
* 支援 Isomorphic Javascript，便於SEO及後端 model 介接調整

### UnitTest
* 檢測單元，讓每一個component 維持高品質的正確性
* 使用 jest 測試 React components
* 導入 storybook 建置 component reference site

 