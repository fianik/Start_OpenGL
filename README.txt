Необходимо запускать debug x64, т.к. бибилиотеки собраны в виде 64-х битных бинарных файлов.
Папка Include создана для подключения во "Включаемые каталоги" (Свойства (проекта) >> Свойства конфигурации >> Каталоги VC++)
Папка Lib создана для подключения в "Каталоги библиотек" (Свойства (проекта) >> Свойства конфигурации >> Каталоги VC++)
Свойства конфигурации >> Компоновщик >> Ввод в пункте "Дополнительные зависимости" прописать glfw3.lib
stb_image - библиотека для загрузки изображения
shaders - содержит прописанный фрагментный и вершинный шейдеры
textures - папка с изображением
glad - библиотека для управления OpenGL
shader_s - шейдерный класс
Include >> imgui содержит main.cpp, который служит референсом для создания GUI и не входит в проект
