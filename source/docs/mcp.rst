Model Context Protocol（模型上下文協定）
====================================

* Model：大型語言模型（LLM），如 GPT-4、Claude Sonnet、Gemini 等
* Context：模型的上下文，包含提示詞、對話歷史等
* Protocol：通用標準協定，用於定義模型與外部系統之間的交互方式

.. tip:: 

   個人把認爲可以將 MCP 可以類比成 Restful API，只是 MCP 是針對 LLM 獲取上下文的協定


.. tip:: 

   MCP 會讓我想到區塊鏈的預言機（Oracle），它讓 LLM 可以脫離原本訓練的數據，主動與真實世界互動，獲得更多更完善的上下文
