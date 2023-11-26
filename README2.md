###  Day1
>首先我想先在原本AndroidStudio裡面選模板
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/845c494d-70a9-4488-a9eb-011b9141b2df)
>
>，然後修改成我要的樣子和新增功能

###  Day2
>我發現要新增一個登入的頁面需要改很多地方
>
>
>我想記錄一下
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/5e74a538-be35-4047-b4eb-62c14fa0dc70)
>
>ui的資料夾底下要新增頁面名稱的資料夾還有Fragment和ViewModel
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/5ff00077-236c-4dbf-8213-b74e0eeea88a)
>
>MainActivity裡面要在OnClick裡面新增頁面的nav
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/8404ee1a-2fce-42a7-92c7-d6ab77778c57)
>
>這邊通常也會需要新增一個drawable的ic_menu_###.xml
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/6c6421b0-f5f0-4b39-9423-a1d1d248f852)
>
>layout也要新增一個fragment_###.xmml的檔案裏面@+id/text_### 要修改成自己的
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/30e94036-5c6b-40ef-9edd-e31d2d40900a)
>menu資料夾下面的activity_main_drawer.xml也要新增一個item
>
>並且把裡面的一些名稱改成要新增頁面的命名
>
>(似乎也能在這邊改選頁面的圖標)
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/88ceec2f-2221-40ea-a5fd-729758a3d734)
>
>都忘了values資料夾裡面的strings.xml也要新增一下頁面名稱不然會出錯


###  Day3
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/1b6d2e0b-34a9-4138-b10f-9e8de09595a7)
>
>我要來新增登入畫面的那些格子了

>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/42bfd961-fc8d-4ce9-8e71-ab4cb1662ad3)

>拉好了 但要改一下內程式碼
>
>當我沒說 物件需要完全限制 不然無法啟用
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/1d4c41c1-a543-41eb-b4f7-700e63070c7b)
>
>目前還是一團亂112/11/25 20:17

###  Day4
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/994edbe5-9936-4f4d-9398-03bc51f38298)
>
>今天繼續弄介面
>
>我發現改這邊會動到
>
![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/8cfa27c5-6c8a-4453-8e0f-ce83e6795f88)

>所以如果有另外要改的話要注意全面的程式有沒有問題
>
>設定漸層背景有參考這個 https://lbt95.pixnet.net/blog/post/41644687-%5Bandroid%5D-漸層色背景
>效果
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/8abbe07e-641d-4560-b90e-d2e4734aae12)
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/cad93be8-be75-4e9f-9f32-6aed0cfcdafb)
>想在login的按鈕上新增一些功能
>要把按鈕設好ID![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/00678a7f-cfed-4a99-8306-de939b886cb1)
>
>然後去到
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/92f34656-64cf-4e49-8e44-4dce2c3e623c)
>
>底下在onCreateView 這邊新增程式








