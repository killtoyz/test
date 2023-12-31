- [Выдача документов СП](#выдача-документов-сп)
  - [Сведения о заявителе](#сведения-о-заявителе)
    - [Контактная информация](#контактная-информация)
    - [Сведения об ответственном исполнителе](#сведения-об-ответственном-исполнителе)
  - [Сведения о лекарственном пепарате](#сведения-о-лекарственном-пепарате)
    - [Сведения о регистрационном удостоверении](#сведения-о-регистрационном-удостоверении)
  - [Сведения о производстве готовой формы](#сведения-о-производстве-готовой-формы)
  - [Сведения о фармацевтической субстанции](#сведения-о-фармацевтической-субстанции)
    - [Сведения о регистрационном удостоверении](#сведения-о-регистрационном-удостоверении-1)
  - [Сведения о стадиях технологического процесса](#сведения-о-стадиях-технологического-процесса)
  - [Сведения о сроках проведения закупок](#сведения-о-сроках-проведения-закупок)
  - [Спопособ получения результата услуги](#спопособ-получения-результата-услуги)

# Выдача документов СП
## Сведения о заявителе
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:ApplicantInfo>
                    <tp:LegalEntity>
                        <tp:FullName>
                        <tp:ShortName>
                        <tp:INN>
                        <tp:OGRN>
                        <tp:LegalAddress>
```
* Полное наименование организации
* Сокращенное наименование организации
* ИНН
* ОГРН
* Юридический адресс
### Контактная информация
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:ApplicantInfo>
                    <tp:LegalEntity>
                        <tp:ContactInfo>
                            <tp:PhoneNumber>
                            <tp:Email>
```
* Номер телефона организации
* Электронная почта организации
### Сведения об ответственном исполнителе
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:ResponsibleExecutorInfo>
                    <tp:Surname>
                    <tp:Name>
                    <tp:Patronymic>
                    <tp:PhoneNumber>
                    <tp:Email>
```
* Фамилия
* Имя
* Отчество
* Номер телефона
* Электронная почта
## Сведения о лекарственном пепарате
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:DrugInfo>
                    <tp:Drugname>
                    <tp:InternationalDrugname>
                    <tp:DrugForm>
                    <tp:Amount>
                    <tp:MeasurementUnit>
```
* Наименование
* Международное непатентованное наименование
* Лекарственная форма
* Дозировка
* Единицы измерения
### Сведения о регистрационном удостоверении
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:DrugInfo>
                    <tp:RegistrationNumber>НП0001</tp:RegistrationNumber>
                    <tp:RegistrationDate>2021-01-21</tp:RegistrationDate>

```
* Номер
* Дата выдачи
## Сведения о производстве готовой формы
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                    <tp:DrugProductionStages>
                        <tp:VenueName>
                        <tp:ProductionPlace>
                        <tp:Stages>
                        <tp:Stages>
                        <tp:Stages>
```
* Название производственной площадки
* Место производства
* Стадии технологического процесса по данному адресу
* Стадии технологического процесса по данному адресу
* Стадии технологического процесса по данному адресу
## Сведения о фармацевтической субстанции
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:Substance>
                    <tp:SubstanceInfo>
                        <tp:Drugname>
                        <tp:ReleaseForm>
                        <tp:Amount>
                        <tp:MeasurementUnit>
                        <tp:ObtainingMethod>
```
* Наименование фармацевтической субстанции
* Форма выпуска
* Количество вещества
* Единицы измерения
* Метод получения
### Сведения о регистрационном удостоверении
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:Substance>
                    <tp:SubstanceInfo>
                        <tp:RegistrationNumber>
                        <tp:RegistrationDate>

```
* Номер
* Дата
## Сведения о стадиях технологического процесса
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:Substance>                 
                   <tp:SubstanceProductionStages>
                        <tp:VenueName>
                        <tp:ProductionPlace>
                        <tp:Stages>
                        <tp:Stages>
                        <tp:Stages>
```
* Название производственной площадки
* Адрес производства
* Стадии технологического процесса
* Стадии технологического процесса
* Стадии технологического процесса
## Сведения о сроках проведения закупок
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:ProcurementStart>
```
* Начало проведения закупок
## Спопособ получения результата услуги
```XML
<tns:FormData>
        <tp:CP2>
            <tp:Form1>
                <tp:ResultType>
```

