********************
在Studio中創建一門課程
********************

一旦您已經創建一個課程，則您已經準備好去創建課程的內容。

.. warning::

	這個 Alpha 版本的 Studio 沒有版本控制機制，或於您的瀏覽器重新整理頁面時的自動更新功能，版本控制功能將會在未來的版本中釋出。
	目前為止，請保持只有作者一個人於單一瀏覽器 (或是單一分頁) 上編輯課程內容，若是有一個單元同時間有多個網頁進行編輯，則有可能發生覆蓋的情況，新舊之間可能會互相影響。
	因此，在每次開始編輯之前，請先重新整理您的瀏覽器頁面，以確保載入最新的資料。


簡介
****

正如離線課程一般，在一個線上課程內容被細分成許多細小的片段。
在 Studio 中，這些片段被分類成 **節** 、 **小節** 以及 **單元** ，其中每個「單元」是由「組件」所組成，這些組件包含了您課程中的實際內容。

「節」，舉例來說，可對應您課程中的第幾週，而「小節」常常是對應您的第幾課、作業或者測驗。
一門課可以選擇由幾個單元所組成，像是影片、文字、圖片、討論以及問題所交織而成。
這是一個具有互動代表性的教材，您會在一次課程中經歷過所有部分。

在 **課程內容** 頁，您可以一次瀏覽整門課程中所有的節、小節以及單元，以及小節是否為公開或私人狀態。


    .. image:: Images/C02_01.png
       :width: 800

    .. image:: Images/C02_02.png
       :width: 800

.. raw:: latex
  
	\newpage %

章節
****

「章節」是最頂層的類別，可以用它來組織您的課程。
許多教師根據位於課程第幾週來命名，像是第一章被命名為「第一週」、第二章被命名為「第二週」，以此類推。
章當中包含了「小節」，裡面包著更多「單元」.

您可以設置給每一個您課程中的「章節」一個獨立的釋出日期，直到已經通過釋出日期之前，在章節中的內容不會被看見。

要了解更多有關如何創建一個「章節」的資訊，請看 :doc:`create_section_sub_section`.

.. raw:: latex
  
	\newpage %

小節
****

一個「小節」是一個「章節」的子項目。許多教師根據課程的主題去命名小節。
當您於 Edge 上檢視課程時，每個小節的名字會依附於每個章節之下，顯示於左方的課程導覽面板當中。

    .. image:: Images/C02_03.png

您可以設定「小節」作為您作業中評分的依據，並將作業放置於小節之中。

您可以設置給每一個您課程中的「小節」一個獨立的釋出日期，直到已經通過釋出日期之前，在小節中的內容不會被看見。
如果您沒有設定一個釋出日期，這個小節會使用所屬的「節」的釋出日期。


要了解更多有關如何創建一個小節，請看 :doc:`create_section_sub_section`.

.. raw:: latex
  
	\newpage %

單元
****

「單元」是一個進一步幫助您組織您的課程教材的類別，單元中包含建立各個課程區塊之「組件」。
當您於 Edge 中檢視您的課程時，單元不會顯示在左側顯示節與小節的面板中，而是顯示在主要面板的上方。
以下範例中可以看到一個小節中包含兩個單元的範例。

    .. image:: Images/C02_04.png

請注意，預設情況下所有的單元的可見度被設定成 **私有** 。
若要讓一個單元被學生看見，您必須明確的改變單元的可見度為 **公開** 。
要了解更多資訊，請看 :doc:`set_content_releasedates` .

.. raw:: latex
  
	\newpage %


組件 
****

「組件」為一個「單元」的一部分，其中包含您的課程的實際內容。
當您透過滑鼠游標滑過畫面上方的單元導覽列，您可以看到每個單元的實際名稱。

.. image:: Images/C02_05.png    
 :width: 800

目前一共有四種組件：討論組件、HTML 組件、問題組件以及影片組件。
欲了解更多資訊，請看 :doc:`create_discussion`, :doc:`create_html_component`, :doc:`create_problem`, and :doc:`create_video` . 
