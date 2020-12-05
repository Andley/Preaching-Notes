# 標題 1
## level 2
### level 3
#### level 4

---
## 強調

**粗體**  
*斜體*  
__*斜粗體*__


`code`

### Ruby

<RUBY><ruby><ruby>ἀλλὰ<rt>Nevertheless</rt></ruby><rt>ἀλλά</rt></ruby><rt>CONJ</rt></RUBY> <RUBY><ruby><ruby>ἐβασίλευσεν<rt>reigned</rt></ruby><rt>βασιλεύω</rt></ruby><rt>V-AAI-3S</rt></RUBY> <RUBY><ruby><ruby>ὁ<rt>‑</rt></ruby><rt>ὁ</rt></ruby><rt>T-NSM</rt></RUBY> <RUBY><ruby><ruby>θάνατος<rt>death</rt></ruby><rt>θάνατος</rt></ruby><rt>N-NSM</rt></RUBY> 

### 特殊符號

| Unicode | result | UniCode | result |
| ------- | ------ | ------- | ------ |
| U00AB   | «      | U00BB   | »      |
| U25C2   | ◂      | U25B8   | ▸      |
| U2190   | ←      | U2192   | →      |
| U21D2   | ⇒     | U21D0    | ⇐     |
| U2235   | ∵      | U2234   | ∴      |
| U00A7   | §      | U2015   | ―      |
| U21B5   | ↵      |

### 引用

> 文字下標<sub>a</sub>
>> 雙重引用上標<sup>b</sup>

---
## 註腳

本文帶註腳<sup id="a1">[1](#%5Ea344fd)</sup>

## 連結
[[
[其他文章連結](IGNT-01)：IGNT/01.md

[其他文章內的段落](IGNT-01#11-%E4%B8%89%E5%80%8B%E5%8B%95%E8%A9%9E%E8%A7%80%E9%BB%9E-The-Three-Verbal-Aspects)：1.1 三個動詞觀點 (The Three Verbal Aspects)

[本文內的段落](#bottom)：bottom
[qq](#%5E88f4c1)



## 表格
| Markdown Engine              | Align Center | Align right |
| :--------------------------- | :----------: | ----------: |
| *Still*                      |  `renders`   |  **nicely** |
| 1                            |      2       |           3 |
| <li>item1</li><li>item2</li> |      5       |           6 |



## 清單
1. 大點自動編號 (同一段落內)
	1. 小點
		1. 小小點
		 	 1. ssd
				  1. sddd
						  1. sdcsc
					  1. sdcsc
						  1. sdcsc
							  1. sdcsdc
								  1. csdcs
									  1. csdcdscsc
										  1. scsdcds
											  1. sdcsdc
      1. 小小點
   2. 小點
1. 大點自動編號 (同一段落內)

- 大點
  - 小點
    - 小小點
    - 小小點
  - 小點
- 大點
  
----

## 可折疊區塊
<details>
   
  <summary>進階資訊</summary>
  
  ### Heading
  
  1. A numbered
  2. list
     * With some
     * Sub bullets
     
</details>

------
## 註腳

<sup id="f1">1</sup> 註腳內容 [↵](#a1) 05793f ^a344fd


- [HOME](README.md)
- [回目錄](README.md)
-------
# GitLab Extension


A footnote reference tag looks like this: [^1]

This reference tag is a mix of letters and numbers. [^footnote-42]

## mermaid diagrams

```mermaid
graph TB

  SubGraph1 --> SubGraph1Flow
  subgraph "SubGraph 1 Flow"
  SubGraph1Flow(SubNode 1)
  SubGraph1Flow -- Choice1 --> DoChoice1
  SubGraph1Flow -- Choice2 --> DoChoice2
  end

  subgraph "Main Graph"
  Node1[Node 1] --> Node2[Node 2]
  Node2 --> SubGraph1[Jump to SubGraph1]
  SubGraph1 --> FinalThing[Final Thing]
end
```

```mermaid
gantt
title Adding GANTT diagram to mermaid

section 掃羅
膏抹 (1Sa 9): des1, 2014-01-06,2034-01-08
Active task:des2, 2024-01-09, 2034-01-08
Future task:des3, after des2, 100w
Future task2:des4, after des3, 50w

section 大衛
膏抹 (1Sa 9): des1, 2014-01-06,2034-01-08
Active task:des2, 2024-01-09, 2034-01-08
Future task:des3, after des2, 100w
Future task2:des4, after des3, 50w
```





[^1]: This is the text inside a footnote.

[^footnote-42]: This is another footnote.


## bottom

^88f4c1
