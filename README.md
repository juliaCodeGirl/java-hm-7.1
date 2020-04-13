**INSTRUCTION** 
- наименьшая единица измерения в JaCoCo.
Этот счетчик для Java-byte кода. Предоставляет информацию, какое количество кода было протестировано/пропущено.

**BRANCH** 
- метрика подсчитывает общее количество ветвей if и switch и определяет количество выполненных или пропущенных веток. Предусмотрено три состояния:
    * Нет покрытия: не было выполнено ни одной ветки (красный ромб)
    * Частичное покрытие: была выполнена только часть ветвей (желтый ромб)
    * Полный охват: все ветки были выполнены (зеленый ромб)
    
**LINE** 
- для всех скомпилированных файлов классов можно рассчитать покрытие для отдельных строк. Строка считается выполненной, если выполнена хотя бы одна инструкция в ней. Предусмотрено три состояния:
    * Нет покрытия: в строке не было выполнено никаких инструкций (красный фон)
    * Частичное покрытие: была выполнена только часть инструкции в строке (желтый фон)
    * Полный охват: все инструкции в строке были выполнены (зеленый фон)
    
В качестве счетчика использован INSTRUCTION.