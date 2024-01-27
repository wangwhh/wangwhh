# material 使用记录

## 代码块
1. 指定文件名：
   
    === "show"
        ``` py title="bubble_sort.py"
        def bubble_sort(items):
            for i in range(len(items)):
                for j in range(len(items) - 1 - i):
                    if items[j] > items[j + 1]:
                        items[j], items[j + 1] = items[j + 1], items[j]
        ```

    === "code"
    
        ```
            ``` py title="bubble_sort.py"
                def bubble_sort(items):
                    for i in range(len(items)):
                        for j in range(len(items) - 1 - i):
                            if items[j] > items[j + 1]:
                                items[j], items[j + 1] = items[j + 1], items[j]
            ```
        ```

2. 显示行数
   
    === "show"
        
        ``` py linenums="1"
            def bubble_sort(items):
                for i in range(len(items)):
                    for j in range(len(items) - 1 - i):
                        if items[j] > items[j + 1]:
                            items[j], items[j + 1] = items[j + 1], items[j]
        ```

    === "code"

        ```
            ``` py linenums="1"
                def bubble_sort(items):
                    for i in range(len(items)):
                        for j in range(len(items) - 1 - i):
                            if items[j] > items[j + 1]:
                                items[j], items[j + 1] = items[j + 1], items[j]
            ```
        ```

3. 某行高亮
   
    === "show"

        ``` py linenums="1" hl_lines="2 4"
            def bubble_sort(items):
                for i in range(len(items)):
                    for j in range(len(items) - 1 - i):
                        if items[j] > items[j + 1]:
                            items[j], items[j + 1] = items[j + 1], items[j]
        ```

    === "code"

        ```
            ``` py linenums="1" hl_lines="2 4"
                def bubble_sort(items):
                    for i in range(len(items)):
                        for j in range(len(items) - 1 - i):
                            if items[j] > items[j + 1]:
                                items[j], items[j + 1] = items[j + 1], items[j]
            ```
        ```

4. 连续高亮
    
    === "show"

        ``` py linenums="1" hl_lines="2-4"
            def bubble_sort(items):
                for i in range(len(items)):
                    for j in range(len(items) - 1 - i):
                        if items[j] > items[j + 1]:
                            items[j], items[j + 1] = items[j + 1], items[j]
        ```
    
    === "code"

        ```
            ``` py linenums="1" hl_lines="2-4"
                def bubble_sort(items):
                    for i in range(len(items)):
                        for j in range(len(items) - 1 - i):
                            if items[j] > items[j + 1]:
                                items[j], items[j + 1] = items[j + 1], items[j]
            ```
        ```

## 标签栏

=== "tab1"
    
    Hi，我是标签栏1
    

=== "tab2"

    ```
        === "tab1"
            Hi，我是标签栏1

        === "tab2"
            ```
            这里是code
            ```

    ```

## 高亮栏

=== "show"

    !!! note "Note标签"
        默认note标签。

    !!! abstract
        默认标题的abstract标签。

    !!! info ""
        不带标题的info标签。  
        除此以外还有 tip, success, question, warning, failure, danger, bug, example, quote
    
=== "code"
    
    ```
        !!! note "Note标签"
            默认note标签。

        !!! abstract
            默认标题的abstract标签。

        !!! info ""
            不带标题的info标签。  
            除此以外还有 tip, success, question, warning, failure, danger, bug, example, quote
    ```

## 删除线、下划线、注释、高亮
    
=== "show"

    Text can be {--deleted--} and replacement text {++added++}. This can also be combined into {~~one~>a single~~} operation. {==Highlighting==} is also possible {>>and comments can be added inline<<}.  

    {==
    高亮块啊啊啊  
    啊啊啊啊
    ==}  

    下标：H~2~O  
    上标：29^th^

=== "code"

    ```
        Text can be {--deleted--} and replacement text {++added++}. This can also be combined into {~~one~>a single~~} operation. {==Highlighting==} is also possible {>>and comments can be added inline<<}.  

        {==
        高亮块啊啊啊  
        啊啊啊啊
        ==}  

        下标：H~2~O  
        上标：29^th^
    ```

## 图标

=== "show"
    
    :dog: :cat:

=== "code"

    ```
        :dog: :cat:
    ```