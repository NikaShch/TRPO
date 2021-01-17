# ТРПО
## Лабораторная работа №7
### Задание
1. Создание программы на языке _С++_
2. Публикация на **Github** с помощью системы контроля версий **Git**
### Последовательность работы
1. В папке «ТРПО» создать подпапку «Лабораторная работа №7».
2. Запустить программу C++ Builder XE и создать новый проект с типом VCL Forms Application.
3. Сохранить все его файлы в папке с именем «Лабораторная работа №7», задав название проекта по Вашей фамилии на английском языке (расширение cbproj).
4. Поместить на форму кнопку Button1 и в свойстве Caption дать название ей «Нарисовать».
5. В обработчике кнопки «Нарисовать» разработать программу для прорисовки на поверхности формы геометрической фигуры заданного цвета.
 
### Фрагмент кода программы
#### Обработчик нажатия кнопки
```cpp
void __fastcall TForm1::Button1Click(TObject *Sender)
{
	 Form1->Canvas->Brush->Color = clWhite;
	 Form1->Canvas->Pie(0,0, 100,100, 100,0, 0,0);
	 Form1->Canvas->Brush->Color = clMaroon;
	 Form1->Canvas->Ellipse(40, 40, 150, 150);
}
```
#### Результат работы программы
![Result](https://sun9-8.userapi.com/impf/DpTxzs5fy5B2XNb3gJMWq2jh9dXgeGT1N15cWA/xxQdsK5el0M.jpg?size=558x325&quality=96&proxy=1&sign=e20b9d3abb39bf42997f99aadea5f99d&type=album)

Проект был создан в среде разработки С++ Builder
 
***
 
### Работа с системой контроля версий
Для выполнения данной лабораторной были использованы:
1. **Git**
1. **Visual Studio Code** и плагины
    1. Markdown Shortcuts
    1. markdownlint
    1. GitHub Pull Request and Issues
Также были использованы [уроки](https://docs.microsoft.com/ru-ru/learn/modules/introduction-to-github-visual-studio-code/)