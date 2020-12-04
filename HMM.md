# HMM ( Hidden Markov Model)

## Introduce 
Markov Model :  是一種模擬連續的過程，且假設每一次的過程都跟上一次的狀態(state)有關係。而 HMM 其實就是延伸版本，由於在現實生活中，我們觀察 Markov Model 時，只能看見輸出的觀察值(observe)，無法得知內部的狀態，所以我們對於 state 的狀態一無所知。例如：今天你可以透過觀察他的平常的行為來判斷今天是晴天或是雨天。

應用：常被應用於語音與文字處理相關的情境內。

## 基本參數
- state：內部的狀態 (我們無法得知)
- observation: 可以觀察的序列
- Transition matrix: state 與 state 之間的轉換的機率
- Emission matrix: state 選擇 observation 的機率
- inital matrix：最一開始的選擇 state 的機率
- lambda: 為 HMM 的參數 (lambda = {T, E, pi})

## 過程

## 介紹
