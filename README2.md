###  步驟1
>首先我想先在原本AndroidStudio裡面選模板
>
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/845c494d-70a9-4488-a9eb-011b9141b2df)
>
>，然後修改成我要的樣子和新增功能

###  步驟2
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


###  步驟3
>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/1b6d2e0b-34a9-4138-b10f-9e8de09595a7)
>
>我要來新增登入畫面的那些格子了

>![image](https://github.com/jing920119/ChefClothesAPP/assets/144665311/42bfd961-fc8d-4ce9-8e71-ab4cb1662ad3)

>拉好了 但要改一下內程式碼



