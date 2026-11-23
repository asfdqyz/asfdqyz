# Josephson junctions & superconducting circuits

Численные модели джозефсоновских переходов, динамика флюксонов, спектры напряжения и топология сверхпроводниковых схем.

**Python · NumPy · SciPy · Matplotlib · KLayout · Ruby**

## Проекты

| Проект | Что внутри |
|---|---|
| [LJJ + JTL](https://github.com/asfdqyz/long-josephson-junction-jtl) | Ёмкостная связь длинного перехода и JTL, SFQ-импульсы, ВАХ, спектры и отчёт |
| [Топология LJJ](https://github.com/asfdqyz/long-josephson-junction-chip) | GDS переходов 1000/1200/1400 мкм, слои KLayout, меандр и результаты модели |
| [Флюксоны](https://github.com/asfdqyz/long-josephson-junction-fluxons) | Ступени нулевого поля и разные начальные флюксонные состояния |
| [Магнитное поле](https://github.com/asfdqyz/long-josephson-junction-field) | ВАХ длинного перехода при разных внешних потоках |
| [LC-резонатор](https://github.com/asfdqyz/josephson-lc-resonator) | Переход с резонатором: ВАХ и частотно-токовые карты |
| [Тестовая топология](https://github.com/asfdqyz/test-chip-layout) | GDSII и настройки слоёв для тестового чипа |

## От модели к топологии

Исследование начинается с уравнений и начальных условий, продолжается анализом ВАХ и спектров и дополняется геометрией в KLayout. В репозиториях собраны исходные скрипты, сохранённые данные, графики и пояснения к нормировкам.

[![Пример выходных импульсов JTL](https://raw.githubusercontent.com/asfdqyz/long-josephson-junction-jtl/main/docs/review_2026-11-23/figures/jtl_comparison.png)](https://github.com/asfdqyz/long-josephson-junction-jtl)

*Результаты численных моделей отделены в описаниях от экспериментальных измерений и технологической верификации.*
